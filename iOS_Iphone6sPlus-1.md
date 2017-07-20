#### Test 113351851f4ec514_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/669794BF-1E61-4114-8F97-EDD742419148/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/669794BF-1E61-4114-8F97-EDD742419148/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52345"
,(lldb)     command script import "/tmp/669794BF-1E61-4114-8F97-EDD742419148/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:47:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4374F9FE-9143-4C2D-9B,A7-7BC86F912494", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4374F9FE-9143-4C2D-9BA7-7BC86F912494
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5EEDD0E-963E-4BD8-99A0-82B8179E9C45
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19DF547C-,667C-4853-B70D-28FAB98DEECE
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2067B7A8-97F4-4EEC-9738-9FDED75E235E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2067B7A8-97F4-4EEC-9738-9FDED75E235E
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2067B7A8-97F4-4EEC-9738-9FDED75E235E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2067B7A8-97F4-4EEC-9738-9FDED75E235E", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-20 12:47:39 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of fail,ed tests:  0
Number of ignored tests:  0
Total duration:  1.488566100597382
,2017-07-20 12:47:39 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-20 12:47:39 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2067B7A8-97F4-4EEC-9738-9FDED75E235E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2067B7A8-97F4-4EEC-9738-9FDED75E235E", generation: 0)
,2017-07-20 12:47:41 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 12:47:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 12:47:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 12:47:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 12:47:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 12:47:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-20 12:47:43 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 12:47:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:47:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:47:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:47:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:47:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:47:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:47:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:48:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:48:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:50:07 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-20 12:50:07 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-20 12:50:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-20 12:50:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-20 12:50:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-20 12:50:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-20 12:50:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-20 12:50:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-20 12:50:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
2017-07-20 12:50:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are, out of the checkpoints plugin delay interval''
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
,2017-07-20 12:50:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-20 12:50:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-20 12:50:32 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-20 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-20 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:50:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3FFEF40-CD46-4220-AC4A-C103C08FAB5D
[ThaliCore] Browser.startListening
2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:50:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:43 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9BA970B1-8108-4900-9C47-AE99AA94D341
[ThaliCore] Browser.startListening
,2017-07-20 12:50:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:50:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-20 12:50:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-20 12:50:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E6163FD3-D12D-4C04-A663-8E5D063A585D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E6163FD3-D12D-4C04-A663-8E5D063A585D
,2017-07-20 12:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E6163FD3-D12D-4C04-A663-8E5D063A585D
2017-07-20 12:50:54 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7809D559-6C51-47C7-9DBE-8C73A37AD230", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7809D559-6C51-47C7-9DBE-8C73A37AD230
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7809D559-6C51-47C7-9DBE-8C73A37AD230", generation: 1)
[,ThaliCore] Advertiser.startAdvertising with peerID:7809D559-6C51-47C7-9DBE-8C73A37AD230
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:56, ,- INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:5,0:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7809D559-6C51-47C7-9DBE-8C73A37AD230
[ThaliCore] Advertiser.s,topAdvertising() peerID:7809D559-6C51-47C7-9DBE-8C73A37AD230
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:57 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17
,2017-07-20 12:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC09FB67-9F62-4D4D-A710-393E652F1,393
[ThaliCore] Browser.startListening
2017-07-20 12:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:02 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:02 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:51:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C5CDF2F5-B94E-4A6B-8828-7,A7D80CF7E17
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:51:03 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9
,[ThaliCore] Browser.startListening
,2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
2017-07-20 12:51:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67, (syncValue: U1OU8H7MMNIkmYzcKryqUAgLrjLXF5H7)'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF,54E67", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found ,peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A9413A1C-B780-4B25-A928-D927B5CAD186","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
2017-07-20 12:51:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,6EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U1OU8H7MMNIkmYzcKryqUAgLrjLXF5H7","error":"Peer is unavailable","portNumber":null}'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U1OU8H7MMNIkmYzcKryqUAgLrjLXF5H7', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33 (syncValue: TTUGOyMdLMjHHhiIkh0KDhw,46vUcGoZr)'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24,C5E8A33:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53840
2017-07-20 12:51:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TTUGOyMdLMjHHhiIkh0KDhw46vUcGoZr","error":null,"portN,umber":53840}'
2017-07-20 12:51:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TTUGOyMdLMjHHhiIkh0KDhw46vUcGoZr', error: 'null', listeningPort: '53840''
,2017-07-20 12:51:10 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,# teardown
,2017-07-20 12:51:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53840
[ThaliCore] Session.disconnect,() peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:57067783-49B1-4C99-BF93-13609A1DCD30
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4FE9695-DFA7-465E-8E9A-F0697520,2D73
[ThaliCore] Browser.startListening
2017-07-20 12:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
2017-07-20 12:51:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","generation":0}'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5BA566D9-7014-4810-A0E9-90FB098310C8, (syncValue: 1xfizoerEJFN9Kmu4mfaAN8nvSKLg3ls)'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098,310C8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33","generation":0}'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","generation":0}'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
2017-07-20 12:51:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","generation":0}'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5B,A566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5B,A566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5B,A566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5B,A566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5BA566D9,-7014-4810-A0E9-90FB098310C8 error: max retries exceeded
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1xfizoerEJFN9Kmu4mfaAN8nvSKLg3ls","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1xfizoerEJFN9Kmu4mfaAN8nvSKLg3ls', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0 (syncValue: 9yaP59z,bmYNO4LRwfULR34DJ0XLSEQKz)'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D1D7EE2C-6B14,-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
[ThaliCore] Advertiser: session connected Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53847
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9yaP59zbmYNO4LRwfULR34DJ0XLSEQKz","error":null,"portNumber":53847}'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9yaP59zbmYNO4LRwfULR34DJ0XLSEQKz', error: 'null', listeningPort: '53847''
,Connecting to the localhost:53847
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:53847
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
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
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
,[ThaliCore] Session.session(_:peer:didChange:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
[ThaliCore] Session.startOutputStream(with:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:51:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 12:51:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 12:51:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-20 12:51:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:85C19076-41FD-4A0B-AAD8-535177F7E31F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
,2017-07-20 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:57067783-49B1-4C99-BF93-13609A1DCD30
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53847
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9yaP59zbmYNO4LRwfULR34DJ0XLSEQKz","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D3868CD6-0B33-4541-B250-1BD91D759404
2017-07-20 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:33, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] Browser.startListening
2017-07-20 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-20 12:51:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:85C19076-41FD-4A0B-AAD8-535177F7E31F
[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
2017-07-20 12:51:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","generation":0}'
2017-07-20 12:51:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0, (syncValue: X8XLEtmSWWmbTrYT4BCj0O8WFEEyfaP3)'
2017-07-20 12:51:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3C,D2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","generation":0}'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
2017-07-20 12:51:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"25ACE2A0-0407-4C75-8F00-F7E349C427D2","generation":0}'
2017-07-20 12:51:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:51:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
2017-07-20 12:51:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","generation":0}'
2017-07-20 12:51:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:51:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D1,D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D1,D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] Advertiser: session connected Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
,[ThaliCore] Session.session(_:peer:didChange:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] Session.startOutputStream(with:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] Session.startOutputStream(with:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliC,ore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] Session.startOutputStream(with:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D1,D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received all data: MsOFcQa1yp6ugrJGo08kwdTvOOBLlZM8sIE6goGdVf2xZ5UzeQ4mbvfEjdW4qLHtElq8h1vkcLKXySjTqqi9EIIpgv8Au5,jGCtBfueMgtMalnue99OFyeZ8NqACT4xtwi4doW9sy6xXvIfPCEiDgpZ332RQxhFsOBDcao7Qkt1h5Wvv8iVCjL3ane0ige03HoiI2nLzBwZAYBicLYVMtznHCq72m0RGxuJINfVhjSkBI221HFJylQtvvHKAVDuyBwJMoI07fHmOF0iFV0n5sfor1DSYBUiwc49gUUFxqxrD26HFW4mHL40OF57KreywwwWRDfCEsxBNhx7kQDrkTQHdjq4BjmP,2Pu0dWc58G1rEczQQRnSJvCwkPZgFYX4F38pjmXWzTlyala30buvlamSb5hb55EsavGgUpiK1UJxcQOTUyxGKbgIx8XHppdnSsvyyinmk0G7acVyLWXLOuWhPcfMeXkXaK9lUmqG7XEDP9NiCqDwTMpIIyuYz4agZe434iqtdbXal6cgcTxC6bKB10VCjOs0EiBIRuK88XwKOyIZ8Ohqc5rmiMybnmKxuoywmXfEEzBggbiRLSgdVcsXgLSRscdu,H2wJNBGIDiTRoZ5OyPWrs6DKSYpsdpbElrwexWvPT3Ilbj8R1c86Yb5wa3EhFR3OboCfw5lAXDCNZnHznMEMb4nlgBvDJZA10HvMwBA3qQeO3DRUTCL2YRhFhzd91OicSmSEWapA8JzmvzpNgWccQibhojnRqfWFtN9Xzw0XATX4QumOdAdi9cAbZKXnpBUaTWbbjrOqxRrHcwF5QOwJzekEb3OLRwBJJJfiGzstms7zFgKOVVj8zf7cvjzXw3c,P,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'
2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384, bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (7624 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocket,DisconnectHandler disconnecting:false
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'
2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 12:51:43 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D1,D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D1D7EE2C,-6B14-4A31-A478-8001B3CD2DE0 error: max retries exceeded
2017-07-20 12:51:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"X8XLEtmSWWmbTrYT4BCj0O8WFEEyfaP3","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'X8XLEtmSWWmbTrYT4BCj0O8WFEEyfaP3', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-20 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-20 12:51:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2F0DF457-C0FF-4613-83CB-F1DB28937A4E (syncValue: Zf0mcZD,Azxy48TXtX6WvYNy1pONh4Wdr)'
2017-07-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F0DF457-C0FF,-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] Advertiser: session connected Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] Session.startOutputStream(with:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [4, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] Session.startOutputStream(with:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [4, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] Session.startOutputStream(with:) peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [4, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received all data: xLIjHoguAnqBAeSZGRcIUg7n0X2Wt5K9XEr1hEJU3XaeNG8ozZagksewkDW9g7OrknYgfWJ5sloQnxhl80ynW8xJ1y6lwAZ7z61duUVbDD3JNxpsTqJ2uf2dEbdXKW7kG1BNWzN7PtoWOCDfQnWb0UEqq0XjfKKFi0uu21sJl3Z9kVA7zipyNU36aNOhuPA1IcZqQeRlukIeXz9tbBhKgd8B6qfsgBkR34l728OCNW1aqM08naHmPoOhNY9Bo2wsbErUqWZlaU,gsMSpKv457rApRLNfK04hk7kRF1PCu38TvYvquPhvkoNRVjPaZ0z7VR66rPlkrVVThvNkI7PMG4i9rMId1XmdACumG3MRkAB1FTNGBZDQNKkATFR6IIedNV4BAqpRmL54M9N4nO2x6XSZ91as7FmQ16oBqSI2OLHOy1wRzKXg9o6qj1LyG1ZeRjaTFa8AqGgoALmYWSKvKsqoxApzEdLCleLQIGsDt0udea7TsFBWxWaRLmd0N6W4hpEgKstvlwY,Ijod7pdYcTUYV0YYzqwN8ckOW0gThwYoCWXE0rNUZVoUYEQP2KASKrmzni1yci4gWXcHS0t09XkRcXlddy6SW3HfseNa30Lr1qprFQ1tG0jt0cq8pNKJ5rbYgIPP06wRCbGENlC8BTdmmS20qyIKqIIzaKb3KLiFcUsVTsN7boQ86bLXOENWNAaeBb3eTPBjn3ikK9snjDaqsFHK0CTyfee9SZC8kzafoQ72T4RZ0azcNN4g4JnstiPNY1BZOvgC,doQIE7UILPqMxS5G0fsjnhF8qqGLWzJP5nWUtCjAZuelJBdyyLFTHDVQzQcaQiwjOX0XQoBM0SYAZSYrdgIaAbkA93KSzFkiPsHkRko2wrI5AbvFsKwFUxNQtTIHmwL8WZNHVbbVQA6UpsnJ4JnstkoXgzWnIfdZeiXYMUGo5LMDvlxqaPx9S8rUIn4VSJ9HTRHzD5w8MsKSgWazbC5pO5TMN3MqnQHP7p4BlZPJHnHSyivM74FU3FXnk4b1P7Gl,PoKZ0ztnInrc89KNcbKL9kOWzCwGq3HmGAv03M6givN8iE0L4ND5muTIGKZzDC4AFKwaJcuR1WLsXnhgVYuc9hHY1HttL9lgLlsju70d8jclkgUQK1aKOeM3zlv3NxnkmitSdMXeD4w3PrzjHeUzWDK8vEhI32RsnHKjfWToS7UxzsOZjQ5XOwpD7JYC0TMGzOs190lftNqHFyyOQJGNqiW3djMNOEwm7UcGlSs6M0ENzss3jouAiVuaNN5FvvZb,geD6jdUCgpc8t30QsqEZZcFkhQvlWMfi7die7wgkmJ9g4r21j5MK6yTuFShHSIjQXbTbRd9MODIGktS94eCFuYWYqI5dGxHWCrExbFPhkoCeEqnwgsZWkXQRIzDz1pSOK6wkHMqEC28WAd1iZne129dg7OUqBSokmGOsIVZDQcWa3t9yoWvqQvmF3fZ6BzqBYnsE4Tx9IbnCWFRYZ0XT7ic1V5eHLvdAGXB0VU6VCDHA1uLDFyywUVA1euXuHQdT,IJnaVBOGWiw4jgHk6i4bfGj3yAglK15AA6D8e3WBqkv6BAteZScpk9XFu7UNdHKHaascL1PYzHp639t1N4ZE2oZ8XskgAmkwqwn88T6pUBxZqZaTgS59RqoMNy0PZEC4wtUa5TKjLeIlhV8QRiZNWm5kbt9g1X7iVvSwMqK6qAsWWTZpyqJxXI2KOyZWbZ7yTn60XBjRgNNC8bl5dtntV2R4lVvRuUmuN20gFsKyoFoW8NGyggmjFGa6s9Npi8lB,sNL20eNG2GiaFTZKYuTcgtchhMv6MPTAa9Jels4PbeBsoYdY52sM5UvC6RrwvUURp71CAHT1eP2AqDx4VWbb1B4B99SLHXz4JIVAokCxh1jUA9LI7BRBNbsTrH4m7PRT8VE4ObZ0NlXUnOq3AggZWCqKjF8YpYetz93xbyKBDeVfwYAfqqVieNHNUOzV1ahvCcqmGxV2uSBWrhzAb3kTcdGAlyI7g9wLS5jMczEYn5fqFTZt7NudR5SJAOWewc2Z,S7rG8ON3XjDgikI6p3g9eQpwRHTRhtibq7XfCyEmSA4VVuxybDmGq0BSOTRjL3cbqHzbM8NPY9wWC8ZEI5BG4wiYYx3zzEqJlZw1psuIWaOpNiHQ9CRIcTsv6nqnbeQqorWLnP1usSN3kKcq0HktsCkGN99FvsDra1dG4vLaHx728LBYcRzBFJOFnshwiTmPmzkaSCxFh45ET6IQAvHn0nfcbTYPiB9mTlimtSd85t22DvTqsIB9fJ5Ftw4pj5XY,Lc2TizOJIybBbWRsDfobPfcsWdQFOXzlKlleUTQaq1MY5AzrjmeYAFnOQ53443buz1psDrmyKZQfc9SQQ4w7ygDsLCfUrBjuhyk0cJfAQ8xuxrZ57yaMudbh7kBRcelcKjICkw8BZO8Et1pHZOtBp5B9eHhrQGnRPp8t40XjrIWRczdRJ9YrxBqrUVwjKJ2SQc7b5O3knenoMYwr6xSgKZ9ueiuB50VUdMiqhuKmDiadTH4OCCFOCA6qIHCQ3tcf,2j7n1puI2iU0ygU0h1PLTkXazzBLvy3eUEYr1UjRsBI7o1eZmNyYDbZ9uVcDP9XxcZrMjMCWESpV9D6ZbqNITeulpDiAsBfEqqeFI6R2HF7aSeu4bRwW8lFOjaHs0wVy2GffA2GQGE1ayq9arScVIEiXpEmJNLD8PyYELNU1UWJyUOI4R5URY8A58kfWqHAKvTr9Py6X4Yi5vilCum9mIU68eLDETdQAmIOmTk5WZ4IW4WcDlBFT1RTCvlp0Qjh5,mehLqG9GZQxHt9KJP6EatpMNpwobp6w5oIspjirj0UXSVfk1qof1d1ORHxGfeMiLVmJZd2bXD9KifkYZx8AntffYJUBWVLl7QaSqkS9GZKsrN0srzyh0koqPYOejgQsulaG8Bngc6kcCdChGboOQo6W8ta7aFhYghbon17XLBQO0dePYpmw30frj0ytWSiZlPsKiriJOTIgxj1CCeMXRg4Kp31tFzMILB79Th4cNI5XEFV7cgAJsP2QYdQHAdVPH,1ho293oqGmqCYY1yewJuVbhwZUmqU0pda9MDeo90py3Jdg1w079cX70FdsH53DHrpWwoSio3A7ItcfZneDPtNSKwsrSjkGQnq8YfNAq38WhrPba49VoeQvguM3NE5VmCQ1UsYzCsIxL6EqBTsEN34wujl0PCXoVS8oi6qGFGocrgytdwRHxktPfGgbBF0BT75KGVUc2n41eeRq2GciSkOj1ibxBE8f4ZoEo5vtFeYg0fMpyxI83Lc4wqHrQCwMc1,O0fES0CG1zx9WSLeqUMXVozHvOeYHS93i7CWb9emAN9TKPjzDDWuemZDZ07GTwg7SxHSbfqpo4yPDMZoZRB9fSTjAF8Jj0JDMtKeJZ34Tmc15gwPTK3p54rRtJcq5FMOCGSpNwt3Cw91biB6quMBTttKvf7D2yrq1piBzW6OpHaUOy7DWH99dRchipWF0UcGw7ldYzlJGviymxOKRTdgcRl6SQZGEVQWS8g8fTnxOmX5iMXSjcHMCNHmX8XLQg64,NcpHKt98AYlJzSfHsMOwQ2QFUZiUePVeP9fpCzgNvVEvAcGsy2GA89UgGRITIzpRAH4Mi6sx8YyBNjxFXhTgZ9us0P7ZlnbTtlf8HCbhqodk0LEQ5XNFaakS2GJJgQrYZApCMWLop8USTZE1lKZxTx8czOHLiLWIWvFuVlj6G6FS2P2ewLmF5kH70kHWVbW62d5x1UMHHJLcMHCNBMWOLqxSBGqSifVfFt1ELfdEQnxXtwhM9MSgrSywJvYi7gkl,JsXx52kbHBpO6wEQV4dwPlpoAecsbMpAQsKhPhOQ6A4suwpxkM0O3gNdlBugGcHYtCySLAlOeXZ3VpgscDpyNQHb3OlxRjcWQJoFL4maUZub3wkVyY0sWE5wdlARVvkuOrVsMy3zqR1q4RBfTPtmbKDdjNeAQktEWMqOTXfaOGTfkQZX33ZO5Pm76HkRCeVizz8ZJP5epwe4xaqj2BAT9eiBEZSkK63MsabHYffhqXFUZTXLu4iam8C0ml7HMkar,VSnoXSINpuAEMwGSyuFwCIHqMBzLZ8437QAi56ymqIiU62fIZdUMX1cWoiRhHoCTBjV1OkqGdLpiJ5bKrjDqYywoyASToSjfLWcbmP0PAWLfNUEM1dyEdL7HFqlzH26F0ogUg9XGkliwKQzeXzt2X9aX6W2AqeiEw8mQfhGYxvlN2UqtHB0bZQS9jwsTV7zsSvKWZjHXJO5zEKLzZDeljeAQLEEm3qBstsnUVH6kl7r7GyAlMLcDg9sJ78A1tTFf,8bAlabwxs0ZpotSv6KcH1MUYnLk5jQqEuoxYYdEn2hZJHMDz6QizKCrvMg3NlxRcuTKsiauzynLNLnnVrKViJ58mqhMUrQ1GtxwnPL35i51OZaaG7KgiLVWrZunGLHB1S8oWiqpsED84GMjH3xyIfvBpIacNiTl4QTJyRy40jmDA3gFX5W0JTIYTnR9bdVuyjKJkz8nqdGRlfZ1D0W7EJF2SmUhl1XFukIg62ucs1G9JGG4P2QJPigMtRjxknbBE,N2S00iOUN7o5PfGr9bcDiY6cQyOiYzHnT4i96I7q3ZCnzkJne1QdCzyqI8NAdm4rNZK1bNnBdhkyFASDjSDR5jF5REYrl3A7fYpAzQcjzWFimU8hRzx4gdXPI2pSY8OKx7ZXj1zURVFaHBfEdTzd29CFlTm988Fn2DL9Nq0ReDFaaL8nVO4BZd5r0KPp0i2kJ21ZlO2fPpWv4yJe4nKIJZu9EbhETp1LlXbUpb0PSIZCmYLPALVbPXn9qmM58kRz,HtKQvay0O2MmVH7J3s09XAZhUxaSfzDXMAD75dL8XoG701LiY1Y0LdrBkn627ZrGaQI3m2p4bkDHsMa9TmwhQjolTNLMM10PrvaNwdAFG8d2dtZ9zG5q1NYteqsfbNMhQFN0giRF5kdpci2F6oZ5tRiERTlT7EljogMsMcJNbtgsr5bvxWRbh9XQZ6vElPvzfgEfSvnUWZ1la54OlNPug6Z78sDbC1sxYU6FeuFHYICd2HUoIEtuKg8ejPOSP4j4,9QS9b8WJRmIFP1o5TCasVJZmzuTbTi6SoQoGnq61by5QCPrwG2CdvAuNLOdNtqrj2VvV2E5fYMIIbpsUYn3KB8N7t5TGuUXD5ARE5GHrSI5EgHXsKcSG8uG6hRiQtcYdlvgmL7UnaqtjNvI0dBcuwSzec47KQRCXF4MSyE2jWLRMst7GA5ule0UIiY1sro8sY73TeIxq0nykoTvf0lbrRK5BttIJdfkVShdgpEk0dX1eDPpPxcXNG1BfgO7sEReG,nonnGnPTZQaHgeS42i9CuNK1lvFIkWF1nQp1nHP89dIILYUaPmwBENupVwx10q3gaPd6QnRQuYXMDORFWoqZBt3Jnp7F456q4Lnz3ByjulxzDylfOUslP9GseSoUkKBdkrp66g8qgi7aP8wjjLIoCufDFVSUEe0H7Ogp1r5TmZrHDi45coYm9ffrcjSjHa8VSrNRxf4ZTlVmt8GIP8G2qoIVuBvIVbiG7tL5v8DT2Ga9T0I11x3hAoXfb8v2rkSW,WSbt2KcEfkKT65EVxeCWfAravTR51idowEJZcD776vPDU1trlDGI7P6O735q8grLxDAOa4e2Zr39ELQi6OE6FPNKWE1qi2W827eNSzwFgHd1C3CiJpCUOUNXraXPKLO5NoQeX5zM0f9Bw6L6b4a8cV1r4c7y11aE5rDFPxwy8knETJTuBF1D6T8YAIA86bfuhffhm8JH5gTvs0lSAndawIIj4QIT4lv1pf4DMWESOpjy8E3x7jNOtVJ6iQuU3Met,xdcdizEtvyuVE09MjVuBcl7ETwOsg1A9EY96kgMlNnfdz2uKkagNVJVOGtTsnHbqmX2Mw5eIYoK2otvF9eOmgj0DvxeYFhj47gumjIA4NNAeesmjoo1rPvry16D0n7GxMPK1yT9CAM3kmyyKzx2Ro3K4KWdDEsxmPtvNs9BN5yGHlUnVax3phVelyUHodbmGMDqScIFS6j6JQfgWXhSK8fJTF5zjPaJWTkd6CTgqfkFoESeBpQZyd4pLVBiufWY4,2WT71UAWP1O06neGe4XXnQ80j0YpMDUrsYeeggfFsQHlgXkhU9snuktB2MzrPQ5322aBWrHCScjxm4RINO1nutqNOkpt0x8GyV9zt6zXX7BQPyoy0vS8oMRLUvscdxXa15Cx71JWUucMUDOSXc7gSrV69rGoivqaAvCX8QXH4s8umGTkVOPy9dRmHSuMDqJbGr1zoJLcdffRha4o2h0amrTU5b2fdFl5WyTajARRFdIQlBRA7oTBBeNFNsP0xfUi,wvXjNqgNyl32vGWpxzhYQPNnrStkylJpE42a7EaxKJtxVxpihY2tD7rUQcV9Cc68tU1QWqILbfJEYqWsP59TmWm5uDiV22gstfEBKsWiyaNmxY2nrusKoByKqzaW5QvcniprOPZshFD4RVhHNvjEoYYZBruRjg0y9PXyLKmKDihH8opxDvDAbak7WpHuUgbFCGZ4jOAK0dwvI5xpdhGQO4FhFHtZBabre0A8fNAxrHtbgvxaGdulcrB1ZxIhlIW1,1XzbOOPbVXqHkaOCCQRKOQwglkf2eFcqdFqA6NsljtyHpA0TGR0tnPXZfY9iQRfwiiqfr7W7v4s3q1RJG1lsC7anc0QRdSNellrM93hjxAWoi4mObwnxNXr9aks2Fld45bmquCF6mu3LLujqYK77piZk4mp7eEIoOsE38VRfDMYWaySfqP1FxWhc7faZkrffHljaVVmYIzd58Btm32VRpXAoxlv3KGLYpM5ilRTr3591VKPaQd9OU1KtlPC2S2Xj,nlBQm6rOwbrWFBOtZ82BGrb5Jf8Qy7xabqCenarJIPFBBUYAglo0Nf2zj2azJ7tr1u6NlRT6uXPCMsSivkUJcZCEAuFy4K32kQmcdkBdG8DsqM3m57EdbdgGqkt4IR4Oq6IWbCQ4Qwb8SqbGL4Qe50FAezh5duGt8GjL1u0YvMid1iM1hZyvR14tgN3GHlrWzZEpRfDQZTUK0r3Pjm92VbabXnbxCnKx4pQYk9CjShcflV6PcJ2n5iOwvs9vJ5VJ,gDcnJRe3GnAsAyVRcvGWd6yJnejmsPnfg88QYAzIlHlUQ2I9qREYewd1yeVvmekKjGsvKH4cfQx7s9OWlfrbORTUv5WE9bucGFmLyyTspQAgk4hOETcYb6G16Lop3IwtPWJXg2oU3sciYtVJvgR0sPEMUrXl1F1V4soEpRef47nwPQUpGbDLD8Xw6iazXFiMUsBGHDtLIHnqekF9bjPtb6T8tHiDiZqpllABwIsV9Ev9cbUllj4JZ1lruQCy4JlS,4gPCIzaFIT1uyjfcLnqmvMeqg2pvHh02JIg1ytdG0GA32rb8ha4lkEvKwrE7HVCqlALzbqweFK6loAlhfNiKe3H2tu29m2TS2lPSi2dt2JhxtT5EXyzahc6SVKm1TnEdchXzp3MEZ5TF5Rxn2w2T8vI91D9oZHOiHD8suvDn3F3IyP1zHvXvhyyDtzOC1g0XNr3raQlnKyuCMPH52XFLFk2NZtmcGqE9l9ebeZLz3jUmYZm0vWocQ5igmWeyjQVq,MKSqAoiYAYd8SAZHliN13XTbi6B5lBuu0FOxdWfRWybbH47RRCBp5ZvfPxe5VMAdxhD8rPjIEEaaoKBMVsYiA35s3hVkYjqhOWDJ2FLVFNzCwFTXo6LtkVreYzkJHo5B0nzYfsV2O2vQxV0nSN7DUiDTCJENsapYQhDbT2TAjS7hSe11cuuCXPOlVLwilVjTaw1mhnS7EfmIwXNFFuUpnAGe77x7uXAmYfKH6nzsa4IuFkDJ5nTgxxbtT7iA9F6X,1QvlXn76SGb31O6jfdrklHse2fhkVKvq6ErQbOn4TlvGrtyzhbMGE2mXeSoMlqaCkKbzNBrVBBHrMjCNV88zYep5q1HWTZ1J0HgEn3HtC3V5sNPYWWkJudJwtMbwuVPzd3UXUJnr9lgr09k0q1sWFxGjkfNUK770MTZA7Nr9qLuiTCnY6hVlBckikUh274cx49RokeYZ4NU3zV7VgJQb27HzwXCOEwQSsBoTkaOMFxSrU8tjgqdjAhf2yOUjJGQs,G3GloGK3MriyWpJmtZbFrnRNlb9rPRXRFmFvGJcev1GZHcEb0qsuxGKzfN9rE0HkLifaYTVDncCKcXXGmJA6W1mrbe8RiqB3Wz3U2U8rjVcVSZ6Teg5PIJdesMzfNZl0WXeYAXe9bBAZaUq3tnVpEPWeszOnGITqAEwR8ehJhrQegGKEeCVeZQeW0RKMldpVlkt3xjJZEMrYTYYVUiDMYiSZMBvR3VLZnzSNXLPqQRdKveWkmpWKWfxuC7EpK7Vc,ipLaIbARS5frDJRwtgJjZzESJlKDOrBRrsQ2VqWSWfyhDDesGcshDI2Eq3uhQESPYU1UQCaRfSLU9swhcicHkauXgYu7htz46VbeJhp4dGCr3kcsNLyHPhIarFXp1WRC4NfjzpKnRuvSHXgiGw7eqC9fnXbBekmAlXaIgFqYyFoGqQBLXup2aGnbXCyU83ID1x2RAWCjl4ZysMquqC2wpZipK6DsIMJDxtFdlzwcJq5eYEQnrGKkrPvlK3gFuHah,ASOcuz9fZJ1a00pkCrcW4MlshZM6EfcxDrAp3hJqfTLqlImxM0Jh059lSxWoeXrlZAoy0Yew2yMU6lGNoUfjsKv1eV2C4UixsiLvTcFDsOBfzspNMGexit6zapNrYefEXwn4mV5jXFxvW1DwTWncOiDZO4j6lfSJxaL1bMczjny6q5N5txM7whvUhpQY9b7Q8ZO4rS3sTkRjnx7zfxsXkIMcGMTgoznwUq0UxsNYzt27zzFkHLD4Hhu1BKBUESfM,cmd3F0zmFcdN26ugxR8Vd8DuBPK83fJI4vTOejOQH5zclNQjdmVjcQmWknEAFQRtIKZ7wa3OGAdjuNXPNieNxyacJ6hVzTgWYBscMTzRtnwqg9zpnhUOAxUI0uaGVvZDcHLy7SYZbqP314tjhWpUaN90uhUsTuAPt2WlgIElMJtf1kiDYP2IORVgaPjhr0WL3iwYte6JSol1TJ4H1pkOZRPF3VU0hvU3nlMN1ZB2gzNvfb4VEYezwHT2Rr3QZFm5,adFH2d8drtZRbdxUO8MYf9y5M7WHNXTu0aDObys2GX6rOdyIxhpfPuU3mbhtdr5qPEftlGtxp3epCZwLpQbUn1awLidQ9QxAGi6yJ41JFlSZJfpwQej2ruxNPJsyltHOc4MvHAscOlTWiFir2bzQhj65mv8hq3sCMf1lEeVtmidVveMFZSJMg417oFSp9krA1q820vXUnMNZW7znCivhdJhsdPnfYxm4F18qi052IH54aQFWfS122OxXecNnzXjn,N1O1LI2EsMOjbNmee397anLbWDvNfw2BuFyWUBRyiFAxHXRXiL5ziYcheXqDZ3rKk6ctjl2fS7OIm5o711eGibo2ln2iyL4j8ilDc2mSadNpIp3hBWQ3J2bVgDtjISppkcOC9sMThcAHMVmkCsO9rB3ElKDp4YJMSynsgQaYK4tu60uWmJm07Tp1VxjsST4t0ePeawHzdxxX20xWnPii0U3lFzTLHzWAqf9qoSoj3bZB3EXhqHHidHGZTA2YCUor,JOaH20RMH6Lt2lqhumUQHxcxITyICG7UZEv7ORCaG2dULv5dFGJsB00wPPi8MMli5MLr9hjdpv8MY8ohLpuHzwILM8TgvD82y5CzPVilEJRDbRoNENZGIafsgBIpqBilGnyOcDzk0fEwXQTeSSVPaOTLt0FVBOQEHe03e9mq45kOzAd1AeI04xLLm8yd8elJFAVmzhO78aRiXxa9n0F1XmOusYcoEOtoPo0KvcVN9igIkfNhi1ZysDWgpaEsK1AA,zyoHSeDsowTBnRR44Vgad5q66af6FKvqUYmENlA0QpVnSkNNJzVqowspMlTgBykIWsewGIBWAcHXUGHRN2d68FQUfpiMpYBIrnoAZxtRLCX2kyEN1TYyGA8njYfVCTMAolrf7VVwys31IDj5YQBueyfdXqlAgZV4W7oHELYIQ1lJ0zPVTE0tstYoo037j3hKVo5Ty51XOftBvwH5recdf4CbzTBtUtfZe7O8tL04I2RtJy3I1PXuysBxjiWgDdBf,HcQJm8E1GovJ2NQSbf9MOtCZO4C5yyRIYjxBeJe2rvFKD2XZbaYwjYx6zYGtdrfQHo3heGWrFQEJlf8prDOw4fu0REpGtxCS6ua40BCAe38GSxM52pynZ7CcEiE6FXjcnxo3HHVG2GR0rAMksx8FluRYONpIX2sbnl09jXT7aYpRuWAnNxkIyVMyxtOsM8lx6wrHnF5ISso1Qtev9nl9Xqu1b278tPVcMMrnmaK4QL5vH9YNwK6cpyJvcIqgPoB5,edj2ttfJAP0dy1ClRN4JMYrJCxdR3QCBHH4lmZGqgRGxko7wcN2R4bEVYw0kvMnaainb67pRrPp4rra2IHFvePIpQYkMn1YuZNSHlGWSSsQ8quqKQJJhxrPRb5GMG9ofooAmHYKLwiiivgIsXE83C5bxdwsNrv60eM0BZlTwp1qVGEtw5HUsyHaPecjGOjATX1eu4QixSlTa6csPwdtNLTE7LQ31ymooAnXkVACORZfRbIXdohAd4kuNeNE5HMSt,e7nPcrmvHrHfz0wcXlnYJ2T3gTeKg82XZsj8Q4v8eo304M4co5gyIYhPxfDX5hr0Jyq1ER4brHg4FSXfgbkoqpnvVTkuiXXEI5v4Uw6gdCBe86RuzMgrqhqUapYf5mHaOeBODxelaf4gurI1O03dxZeqlwdr8gTfMTU0kApegzfselLa4EsU1d957WlrtQtoiSyWTzqKYqdIoIf8AKULDeJCHlygmNasIk8EAvpvNyvNFjSSwbM6MRv1KUCQoGLj,5VWyPArgobqyA8oedQJ56PBR8pSA5G0XrE45SX6u2ZwXmXRNMl7BnT4c6v6usWBUIMWu77iLg3o3A3pmV2twrE6WuS8T6POKN3QLux9VqJlNhLQJVIgRIe0czsbJq5qp9Qk1PDsm2o0QxjJbPd1UviCi55DiTnEyJTb5CR4TsWzBDLCX9ZHs4COJWHxJaW5YWpstsCWFvLHGJuMobKSDL34GfKP6IokGRdeb3Y1UDkV9a6ccjV54bolNvi7KwfaN,c8BLdILSs18QpacHUZKlOCHsrOmxLsaHr9RQg28sxU0t2Q1naoODjjNmz0y0oMMzcj1DHfU26Uq6SH38k0zVgOhwMunmsw8tdMFTpZ7vtyLyWOUSipiMJiMitQ3DRYlJ2IE2hlFSxZMvPC45GW8mS7re4uFsKeYwfaR8TIn24bSpIkFLWRrjillxjX1QQINqoG3zf4oRyauZZ2C1Z4psgDITikavWyxlwLughKYd9Bn7pha27XfDwA2dvWnkYv2K,yAlU3gRiNYErkmQl7czPONlI8lWzl57UXhKg6tLmbpFAXkVNrEKFMtMkywGg0Bs9FON4v5uSvINVEq9EBXcdoTkrf9nvQsngWfBHvuzL7hmA3SDSEVPkwyy1eBXLru9gouAWPQbks9IMmJuMV6CAc48JaK1vXpM5VRZWPfy28AKimXPWvKSfbQykpHo8Y6wMXr6xy17cjNJKkT0hAK9ToMBAdpmH9sg18JG29kB49ZD6u9gZUMcme0mHtL7NCYDo,XbGSkniXS6Tg6PzI5jxEgBErZ4vXdKolU1VK1vvRYVIk9Kxfv40wVWgEKqQWhFgZYXudLqL6L9vLRv2QO3AMiwH2ekvCSNslelP9YLobwc4EZSPBhdFxpWKWKXSkYvJ7wriHDDZp1E6fal59uURhM4EKSkyQBBzrKvUE6GGO88Efhzb8NW7pnYClrCXljYbcjt0ELrJpBLQjIjlpCEPOr9oPF2Aik8JyAxJGzthgofFiU9VkY1l38reUt9CU6CSE,D1iltoZXJKnS3QpKiO32jLjkQCNrv4MJGZxbUdYJdlcM1wDuMv06Ed6yI3MiywkQmnwLeJcNJjgTJlTejCsO98Xe2A5KRmy8YAZZrdmW4j9hMTDgDtGLLd2SHVgt41BGf9vVVQd85DWRuiNCO4d3HVKQiwJOrwWqwvDjxDQB5TXAgDQ6h4x5w6TjVbw7F7Hp1mYGcRVeVgxgyGl38xTavtLwjgDkIZNbpDZ7I6hAObXKyatb9U4fcHyEuNRQckXU,WdWpWO9ahrwKwT4hfSdVKhdMdWbilJXkvcz8Yg9LaOhB2Fnita8WQRFKtFLNo4eQU9jYixpcwW3qV6uVaPDV8szH4gokynsh0iCYA26O4Rl4f9IZ0cUusvo9Kc9cY6ncL2OF6D6bUC2aE57ORG0kZgbiorE3kytDCy5DbjUfjCZSckFFeuAD5x28venb9jtBNd7iaAILmLvWkeTIFyynD5Pk9F628kfHWK7Yq45p91DiqVFGcrYyNufTJyK9GFxY,PYm9n7TCGq4vxHr0Z0ubhIjLtGLVzrR4ZORtf6E86zU3VENCoxc3a3Ywetdg0p1Z274J8QgQcvQTLx2L9nTsmGJMzQ06plsSTj67OtQ6eHgRWMSJAZCti3kX2sOInmYV8RpSK3wKCAMtDhuQbr2gSnjufthiHvb35G5ybrcLcpvxoqsT3HAQryel6nEhQAlYy8F00tiaqByU0H1Y32aGZzvYcZks1KMm5NzZ9feQm9rl0fRdNitir4g1spc15IF7,E0hfg99D2LC2ZbXN8KXFUej6y7WYGn3n7uWNF5KABtMzzVL6jyzxPT9WCqJU7867dnJCtLHR6qUzWUfcykdMoKbYqmQrq1vkZevUkqpbb0Y9nc18FLbbmTQ4d5iQYlpwSXyW9rV0TM3IbbrbsyUPE1rRy6j5mZyyUdLDNX8ixgwroax4lqzrum1PQoG3mgZT4ivQGyPCglmVmCW7B48MDak7VcShIm8ltqNTU2347jNSIqcjSs3Euchaa5CeRmcH,9qrASNPay98CNzxmkQG3As7GLKEdx5FpcUNaPTuP3UCqsDN0PE3aIN7kvYxbvPIhbrJZ0WUKPOTCi5J5TwqY6GmlAqFq0zbUgpmphQ9jee9wdCy279u9ak3RBexgvgP1x6mq8raiGK9lSpKs9S2p58vpPGEfBYzpz9VIyCYchVe923Llq67TcYHDyByIwq9lyeE4EalYwzubAfXuPMpXFmhDTW58lWGaRtzCbSZXoabUnAG4b7IDlYtBRQVd9b8D,V5Sv9PXYhsmev9GCCoKuXQBHwjZPVHKD8rANBqqnhDm0Bu6exYnuCe2hugoSPQcpef0yxWAvW20fu0QXkeiSnxWSeABIMru9zhea8VmpzERnCRlGHXOB6wXjptXQ7Q0x3eeoXNYlbHJbkXEYrJnuoKTpzOCzf5o0nItqES93OB6WZeA8dGCuyBqob4SzbUtdCuu4ixg71GEQUcju9GzPcn7unli2hSzRfDaYqz7qNCeStpkENTT3p2DztKYHsvIo,bOlC7c7jECPi2G8rHHDlPqwRQf50SHAD2ALLb0vKoDDWzxlXETnM9FVIgvM5UX8O94mwga50CJfXivfjBT6gx940zsSTaqmKfD3Kpt3UZ81sdd4EwZdXKrXMMWlNhTgRka5R08u3Rfstg0AHIxkk3XEYUy6LQdlqK7uuwy9LRSQ6D2dTTTtM9hNRaq2GnipuTJfz3FoaDIEyaIMoyNmOhJWFo0BoSSO8ussu0dk4VSjTZowyk3mGC8hnW5K5Onjj,SkMaKSZPnpEt5hlvUvm17xMrBj4R3WhWgYYMJzXXky8WJKVsHlHyIpcgLgS3KmdpJbZAvFFgVtc29lFPl8ZW3TESQze18vGLWxVIx4Xi7Zg1AObE6cfFQJfbAUtuMyyF6iDANw9CllGlmnEKbhD2a1AD2pBlxpUtMYc0WoyznF5UrM1Gxio4ryxaphMKAvuvPEhEFtXGcRFUbg8fEFWQxVfxL4TkOb4fDDe8Or1teZR4mU2kgBOowHSaZSfkGuZM5QoIGS9MXQZ9GDdqYoNL0NBPwjya0iUSKNZ8TX6bovpUxI8eXIyfRfV6JGwfgeuCHivMQQ6j5UkfH9zB0xvZYydHJN49y2oqKhJ01YobsRljcnsXMlJAi3Bu77i6XrXPExhKioqOeJusPDkqHhMgAV75c3wN9o8qCszbTB07M1RV3qk1xOmJb8TVgUxuR2VWfre53ctPaedRNiDblDTWr6tiw24aqTaN2i3BsfDk2Y1deHmUlSyPXU7HVEmL5NiZfM0QHWaoxe1sxfVDSrYu70Q6uYVRhOHNKlso1wfRttLwjBQBZO2nqoQz6kz4eh0Gpd5vIukLEsWGFg5PUaMMb3HdjoOIONFaikUpaVx2naS9ixyLD8KLOeLADExbTrJHVZYI94Y1mMds4M8N9XzsaFOscfuKbdBg9AYkmVEIhMBhxd6BL4AypZ6jAmxeQokQiIaOOifsdB3xw0TEQEJycMYIHxMfrFDJipcQrvNTZBDhi8tJG1JtlfldcL3fbD9G,YpfPH2Kz7m8U798nvWzShGuqmakrIWsvZLdyvUfomeBPV8zJTqz08JGbaQFJ4VUv1B7MtxRiEPCMAMmcfBigw5XQcG0r384OcoSsle3T1NE2w9D1HsJD7vET5WHAV5nhW7Zl7z6dZEpxfEOj2glfGy61QTLuMkWehTuDM31VTutB7xtIwI8Ru30cETKDAIcuUR6ErSlwLmq4jM80G6ZmPwVETDmVArKeTUchIporD9ldyxL2m1rvyeBDCfLbsXzl,HSYUOHI3zIWIwtW8WWAKBhDwmqJMnIXANPI1L9Gq2MnLUHzWQAvzwiga4ifmIRQijr2UAoHC5dCNqZ7L8kauXPXBJEGxc9kyUyOb4ehpXZ41EZ1hGz8sl8gYOqXQvZEzIAnqikm1iIKwkTKPOpwWm15HXxevFJJiOolRowPz1tf7A460ODE1ejGvngQHTS9932Ll0bdqXQQEq8qi7dNRvBh5jdox6OacEoTJ8Rx6z37I4SbgRixeryB7cQpCiK4k,4u8DhbiNYnzWZJQV7hnM5ZVN97Q7qeXRWUz9OB5pgxBiwcJ6iCu6DaMYT8pZkMNEbdiUoWdwiurHogXjc245UCqVqeRZMMH1PPTaJKj02mLwmlRemOQHpTniHnq6qokFmhhjejmH8s8TT4XsMHeYBYZhNm3iE74sgP0TKxEf1AwxWG5I6mTsyS5kUlB5LIRefyQhO4wgUZXmq2ASgcCE7IGI2K8RnXe8Bsd44w27tneWf0ig41dC3xo8DaOMiaGB,qieJRw49msOtPzPsSYWbfBNxxuyM3epwzRsRkzUtL542MzIoCLr893WyBSuRsnRJZx7XH4PGGQG7QZ4Y20oIZ6q0vbQmH8e9fSjgF8I2IjIZqRcaSimV2Wd8vsN74ObrSc4afxX11UYm0B0KHi9SI15DgiuPqtLonqwq2lZjqzUkzwYfZoYs3tmrSxxem7eyaqE8VSCjes4kiDkRP5zUKnjTC8D6VesjL3YZkenUg2fouobPd3vt6yGJgW94erxK,OCToY1pqxdTjYroGfJwBfoLSWtGb6tWVfjr99XtWK8r4ts3dsHEWeMalLJcAp8mWakfDzXxsNtgNGFV7u5WncqqP9gSt9okidJw70TybGZroH1lfp3uWcvOVWI0IgE9qF7YGrAXWrsT8a2TmmVlmPbewj6S4frOkaUQ4FGVTTFyo1ppCvT6ekCVHXTN8S1wRoz7xk32jPXzYjOkVVJNk7jJmhbzuxJNtasRACI8lRtVSzdsM4WyijfkE2RjfDmZi,YDr45Rn3FH3Qby6NZ1Kkeb6Zeq3hhpnWulGsP8q6T6R9e34L8dj3jrFk9TRnMyDgYcUgoeg47iexUyJ6d178vHjUmTTwOUBt7gzVL7D3NAshHsM3SlRWQUiTq11nlj4X9yRPf4ocirDALD6H5XGL9Js4GItjnbyvEEqH3EmId5UKhQluA8VTphKPd04AHd333DL5jW64S6jYZ9MeJZ6xxQKzHmWWYkEjMag9vwMOb7pnN6WZ5wrkifo0uEkFCxIJ,5h02UJd4mtFeYWmVDSZqLwO2cTZCv7i0xmAx1f9w1quifbVQTRKQRlN3Tig55gOoJmmzkMqnYe02uR6ZegvDVAjlr8FF017tF4dTStmEkOrDtolgwqVzVQEqdDsvAEK6gwAvVTVO0LU0NdL9oEwZvb3gcIOa8YyArHQb8trpnwpvhtXMsRUYYwzC406GxwDF7yySbtvf9JYWaH82zvh6Zaxe4MrSVJS4KDRDMHfrx2pssfnkIKzKHP'
2017-07,-20 12:51:49 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received (3386 bytes):'
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [4, 6, 8,]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-0,7-20 12:51:49 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 12:51:49 - DEBUG testThaliMobileNative: 'Server data flushed'
[Thal,iCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false soc,ket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F,0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2F,0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2F0DF457,-C0FF-4613-83CB-F1DB28937A4E error: max retries exceeded
2017-07-20 12:51:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Zf0mcZDAzxy48TXtX6WvYNy1pONh4Wdr","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Zf0mcZDAzxy48TXtX6WvYNy1pONh4Wdr', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:51:55 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 12:51:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2F0DF457-C0FF-4613-83CB-F1DB28937A4E","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 12:51:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 25ACE2A0-0407-4C75-8F00-F7E349C427D2 (syncValue: aKygUMl,8IDnekHyJNas80NbALXFUXBD2)'
2017-07-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25ACE2A0-0407,-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53879
,2017-07-20 12:51:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aKygUMl8IDnekHyJNas80NbALXFUXBD2","error":null,"portNumber":53879}'
,2017-07-20 12:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'aKygUMl8IDnekHyJNas80NbALXFUXBD2', error: 'null', listeningPort: '53879''
,Connecting to the localhost:53879
,Connecting to the localhost:53879
Connecting to the localhost:53879
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
Connected to the localhost:53879
,[ThaliCore] Session.startOutputStream(with:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,Connected to the localhost:53879
,Connected to the localhost:53879
,ok 91 correct string length
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 8, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 8, 9, 10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams,() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:9 [4, 8, 10, 11]
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [4, 8, 11]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
ok 96 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [4, 8]
,# teardown
,2017-07-20 12:51:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:D3868CD6-0B33-4541-B250-1BD91D759404
2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12,:51:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53879
[ThaliCore] Session.disconnect() peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
,[ThaliCore] Session.deinit peer:9AEDF6F8-9F36-43C1-9B5E-0B52C7DDFA76
,[ThaliCore] AdvertiserRelay.deinit
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E60180BF-4B26-4B3B-897C-EC3D67F3C1BD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E60180BF-4B26-4B3B-897C-EC3D67F3C1BD
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480
[ThaliCore] Browser.startListening
2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","generation":0}'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2, (syncValue: rVhLuSsZY9Nq5nmbBynlSLlQrcju4YIH)'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B568,92BA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E60180BF-4B26-4B3B-897C-EC3D67F3C1BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E60180BF-4B26-4B3B-897C-EC3D67F3C1BD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
2017-07-20 12:52:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
2017-07-20 12:52:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","generation":0}'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:52:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rVhLuSsZY9Nq5nmbBynlSLlQrcju4YIH","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:52:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rVhLuSsZY9Nq5nmbBynlSLlQrcju4YIH', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:52:09 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:52:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 12:52:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:52:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D60E8712-4E44-4465-9B4C-CFA9B5D222BF (syncValue: qxtvRfoEPWpUf6asSn9JcPP,1WLEuz9V0)'
2017-07-20 12:52:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D60E8712-4E44-4465-9B4C-CFA9B,5D222BF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:52:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53895
2017-07-20 12:52:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qxtvRfoEPWpUf6asSn9JcPP1WLEuz9V0",,"error":null,"portNumber":53895}'
2017-07-20 12:52:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qxtvRfoEPWpUf6asSn9JcPP1WLEuz9V0', error: 'null', listeningPort: '53895''
,Connecting to the localhost:53895
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 8, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:53895
,2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-20 12:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E60180BF-4B26-4B3B-897C-EC3D67F3C1BD
2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:16 - ,INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopLi,steningForConnectionsAndDisconnectClients() port:53895
[ThaliCore] Session.disconnect() peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B4121540-BB03-4856-A0E5-C0E220AE5A98
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:96A5EA25-D33D-46D7-95E3-0E23D1C7D430
[ThaliCore] Browser.startListening
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
2017-07-20 12:52:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8BCE56E3-D4A4-471D-B13E-1983A975CB39, (syncValue: 9wWukSU1QUx7aJZlZWLZAEjiqNoncIKe)'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A97,5CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"D60E8712-4E44-4465-9B4C-CFA9B5D222BF","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FC588A3-45D2-4DE6-BDAE-579C029A9613:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FC588A3-45D2-4DE6-BDAE-579C029A9613", generation: 0)
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FC588A3-45D2-4DE6-BDAE-579C029A9613","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8B,CE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D
[ThaliCore] Advertiser: session connected Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D
[ThaliCore] Session.startOutputStream(with:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 8, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received (3121 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server received all data: bf4MlTtHTlihcKleXrGSfdxupTvPQj5qorJQWpvViE8kOQUsto1iUgx7z5F703ugSgxhoZyyJXxYjNQEIEr764xKilPLcNqWPBiafjuMJXBZ1UnpY23VklWLcVykiLQM2RCs4TW0fWEicXyGL8qnwo7PkkjMbdOncSFtgxfxj6qHkzpFxPusvJETlpBm6v8MXefLHEYQPBHpVdYy4ygfsWVAgnpIbh5vCukzKBCzX8akgDSU0Zq4klvDOUXKDTA6OJr3wPWcXUT0yOe26vdkLemiRe4koR0vvHz4bwblfKppgna8I2AwbRaqvnYKRNuighNg7Tw1fqdBghNSI67RzylDSpKTpqZpHbDwijYHe1u4Z6s0LAtjMnQiL3xtqMdC9MP0RAPQ6gTKExtDOMoDeMFkLPDs2DOJQmRxf9gyGsaiTwtIqd,T1K8ztwWkCK85Tf5AFY2osfWYmGK7y5Ec8yWWYdTrkQhEUiFcRsqvdrr4i2VcKq2Rl5cRIGOP5DwCrTvh8IMLZITRW1pxkH7fitKPp2qFEAJEmeUJJdNT4913EY7p39LSPwj1WrxrdxWBHm6EVAuMCVQfDweKvQr1tVRwqIEPihzK1oNmd7Mup39KWrv8tQVTaSR7r7sZq3itXcNvgFP7BK500G5EHxFTFCGyiGT1uiQVcwkhWlu2KZc2IAoAovR,xgo6z3QZRKrBgvvxmvRJ6Yd6RZSYfEjblasQU9bfnsiV68iDoNDv4xTMwoyYWMkt5PGuPNw2DPZe2Y2mRa0XkQ3VIXcp7dEqD6uhIStpVczeWyvnFEfeWpqZ8ysnBK8aUAEQeSpdoBnPBGszZVchxhgFCsvEzWot5OQQlpCAsbtgYm8ZJr0E0ZXu8nyUWu7C5rY05kjeYPzRGkVDDaKww5RqzkF3cAIug5WbyU0BWoewRT6045c2UcQ4aaNGzOEb,JVwQ3r8ecdEXn7aJVdeMCjkScw8qzuQzmLkLfsxcN9YyW8UMS6Jgc48gdXEulvkrCFQzx0JOqcr4tuIX0WOyT9bcL6q0fWcn1NE0awTTa8y0fic74R7x1rR8uGJEYAjCFUVb7IHt8euQmMF7YMSI6lbA5LmIYPSaJd9RoNeNU0699f1Ca7zwViiCGD5F0eFWEKRPm31LLyjvyrFqwGHO33MtCghponngGHf2NvnONnEcDhl2th2rOlZw09o1qgCi,NcEaCOwjv8XTsbgFIs54vxScm9atHVFbzNsFI7pXdNuejOpkc5EMvbJWKmukIttuXaGKIIszJMETrXsfnned6cWgyTl6enLll8H1UuZM5wMbo4L9VYDCeLESih33G5SVLvLoFNWYbJebEBQVKCjPJ157ZUZqZNilW1hXnatbQrurcCtQof0vnJooqbE6YvpNZSvHaREQy2KoxuhFQUlqi7uMz7xrdyyVnAvQa6RoNTxQELdUPDY0zHfZ7JzsJRKi,leppsMUGhYuWYKRki7uVxiv5C530unaiBFVNngxCAP59Ak1YKuuIlad4IgcZ00NVpfRVAmMKlMUhwaLiFzKFJd0k02SMNszzyGKECCWGtFtEk9t3yGfh4kw8BY3exuOZJFGWp4a5tRzAgR2m7shOxmpnqal6iXySBYCAw2VPHIWlHNAFbFPQeJ8M6wgMVWuSOXeXaRvwkrJPrgzQTpdyLxUqVXJ7Zz8fikWWPjw7IaWcabTkjFEQ3Ewi5imzaB2i,V8UoGEF4WTwDy88l6QtcZpXEd7zhB2yZVc0BrRc7h1JpzeUwOe0qtB6x0Xckjute9b7OlXPeqral1xxCNAwX5s6t15AHKW3Du6sPWw01ix2yf3CgRwjbxLoVqsYJjxPpsMaDfl5xXHhWw3sSbOnIWXZFRoDr23zO5FxqgyAFZk7i02S5TLudbXLfLHbaiL3fQqf9z83NYoTXSebxmwGqkQwZsqfGwqOv6kYhAfhrbPY1R3VhT6a7eBSCYsxdzWWm,M3r7Gl0qH8s6zU6ANdgYANxdKGpGKTWYge6lppBHLTV8tcJqbmkXWjY8WxtlLWEw19HgcAw230N4ximTctyvmokd8eYFOiceDAUupd8zvKi3Rso52BBHFNnEmuzsPNA5WtwqFw6BqilnsiJ7sp3pugE5RTrLiO8Cj4kz4WeTG7vsHR0EqIFYkROfdNexWdP3AqJjrTMfFqh2zLBe1kZSDY4Dp6OEgQH6kWYV7iBxAPNs6RSip2YtkRYrQZts4Fug,alGxtHif2PHe2L5IyyJkOwEK5VlzDtZdGI03j4ivYrc9OFQ6mvMCaOAYRvPlVhslj3ufyJ7ETjijC3rR1mESfc30vB00NPr0Fe5zIZVRiUEwgPlyITOHsRR948DbS9dyYqGMv9VCenNukKzdb48aP5Lg3akSJnsysyTF5Kp8A4Yy41GISuXiw7GM9FySzq1WsccOM41cldGRpWdZxSfq1IZIEohokdF5AuLXkTszuSsDcSdRARTfY5ScYpH5GcSj,vnT2XsEa0YA27j9aq5GFdLxGE8ovPKlBNP3Wl2ruQ6gOgHxjlKzP5glPNyM2taddEAT2zMG1QjK1NbmQVy52TfRBuq96vfdqWzHylbiYVlI41F0OGx4KxOMpdHTsATtd6gGWU6u95QWxeY86gBNqn6krB0OUjN8knVXFyp73VC0W6wSHVmFsYKb8DR9YzF4qXZ6APgagTILkka8R0Ozkxyxk2hg8Ih2MR0M64yIvovFuTuZtSQYEIWzjxeL1mzc9,cttU292jKrOAYeH3hf2sSRQAzzoaLsLnB580S2FUXFEmyy5351thWXpqWBvDLfcODwiMkPPiAMbsS14xUs1lrry9bPJuEDB1NzRuwKytv28cyFcB0zD6slNt3ag7jH6phQTQggBduw8C00jWozytx9zu0OuTqbPuL62yNGwkpFMsoGxewNJ9WnZ4fPllXnxtT8EsYYps1AXkuZMbo4zamq5ZGc2jPezZbxI4prv98mlfDAxBZxdmIm7A0g2WOSah,l5E045jEjlFJv3ikxoVSCiX76bvvfnSAQWrROOmGIpBZZYjkagoeoEhwMp0UAwT8I6zLN2vM2kSegD9fcnGtwTCYitzUMUT1r7T59gX7Kdic81FU8nFUDCn6iQRAAxxHP2fFcqB18S4rc4PkgriMNPEWk7rkxqvS1G8Mzl6LlUfRlq8kSjkWecc8SPK3yZAKBBGn6k3Ysn3mqyohodDLIPwUKCATpPj5HSsQMzaY4lZwnRyvD2CE4vVPxjnXZ4DK,2tWe0rkaLZBl3KB9D3zcVHiLDKZ3VB3sVnjXGMeh2vzbUAxTrIFUq2SsFlbVB2pAHId1oNsJOjKM59JRDuc4VzglyycusTcWQJ4zahSjuErGeJ1yzTcFRlNAe7hNklxpfOSqAljE9ubBpn7tEEqDeCuYLeXXJxGViAtXi0sgxiuP2qtZGKm5WuB0hkEpySDXQRs6DhCX0jnZ4lCkeufTx8YtlcfGUT5NwMqRSWb2O9YfPBc31uYUHwkKSM623lzR,vrv6v5isAxmqJA5pMqvfqSniaXaHCnVBmbj7zW12IDXsB7uBydzqPM0UO1PHNgrP0UHiGjtFQ5I7emHmAFZqyNiUiirHlyFGgaPn3EuFOXooFsnyKUCwlSwGMvoSbnNIpgjaC5gcFOMGljzoRDquhVxHhCM8H4jKbyVIkVOd9ACUwZ8wHcK9sBXTxfHSfb0toE9xYTyi5rF1Frd8qoB5EjsbYLtgWwCF4eOD1dvfc7gnzbUMUO7LutqbjEdNfXMb,Cp1uReYoEPZLRfY7eUi4VTztomGTBBia7W2vXgYFnQlHe4FHFKprnQVQYPSUNcNt3lOq0VPda0dQwGoYD0qoRQZMSy2aoKhFVrLlfwEu8lL3afwW6U3TYcbgEV5lhhtLlFcCkEviBTPmv5tJzuFRBy9ybrpL2xvCrNEk8ZckRhfJTbG99ikyBpH1C9NNT8OqTsiomOzbGS7MRVHhWuKLYQ3qo7ITXfFta8B52Wijc4qr1UoGwY0u24AEBfUtgOK3,KidAAEKbLr6ySroOxe3eONjwIJ5gVJh2id2xNeDJxagC5V6dMsUVjgfXXMGdUK9sSzfTO0kewBeJsa4sewEm1KjYo7yDtQZL5608zhUgRUiRyurqrCa3Noms68AYmogq2yvmnCnSVkCpsHjQw0mnnFPFQdyaRZURwP6ICTLBq3sxtT731gttt5FYW0eJQzXuFbEOJ0bf5jh3eYKasCuZsFFw2ymzfBn9z5lsaWSTMMJwNRH6JqtTNcpja8eLkR1k,xCGzaXWfvf0GK4i8skxkSuIwIGcmTndrcRb6VlNvT6I0V8QKZN2jO4Rvw1na7d6nT3gWjHmaa030y2lGrQMXaMKqqoeXZMJdOIJOkjV8YLsGECeg819IxakCpEYqvaR0VaHyOa0dB30uufsds6j5fc8xtk6R3MsoDWfNpMGgjMjH8xmqtknwJiqhEwdeLsevjG2411SksBTFio6fRNF9GMmYzNdpcJdIroAfUaaVD1Sdwl4INmt1IlD1hsUkOyhA,sPN1tEgIzhIX9mmtvAHXOZLva2gNIKcgu4I2kzHLM9lYx8zJk3WTl3Fz3BRd6HITL0BWFgqnO0zAtXosY5MjuC5Tp16bRYdM1HetKDo6OGNRmt3KYhaoqCmY6DqSF23FVsfxRvhz0wb4T6JAomjGw9MrNn6a59pVYJROH6RzJqmxBGwqhABdzJsWmXN82Eramb1e5Nd9k34uXIG93PFytXjorvkFMrUxxWBt2PuawAoqeKY2GQ6mz4egcgimoppY,ntyrK5JOZeRM6ukabaDiXDZsAHjNSsN1OmKuYmqPhfG86CzfpgnVr5eGWFxIQiasF8cORMdi4zVNpI02H7LOjelQmfZnSSqCS6DgXd0zGJUuFjW7DihdFohjRmwsVZDoPR05KofFAPCu54YB6w1Le1ie3nAI3TIUiACn2AaacEOlX6ThW4M1ZHUbZwjAvln5FtjIGksDxMxPhb5IqHE4vUjrlhGmzDjGOgcsA1HEiKvoqsjRCiLMO2iBtNcUZExS,pnKFCl8BrOCkAM3A8D4GySDfQSq1J3HepHxTYGiPGHBqJkH3FS10LmGOYJ7mzKGMlyYzkBZUzsNwU0sx4fSuMgAiQdKtsu5ALequXIdwkxi7sWX8chHnMEATjLyQOHk0Wm5dPAHyEI6nQa9YTs4g4ydbQ6xgE7CiGi0Qt9aZPMLjmQ4tlDNXjmdIIyEmutXLCysbVrhmivpNFrq96pPP220ZMslM2FzIRi41lFNg5EF4pGkQuOt9DQj9NO1vgPiN,EPHCKZ1vzsSHMmUIOPXsgoN4vof01KPlzQFbcfZZrNFLg3CaXa137iAgVxhtUJB0o93BbGKLAFSYvMVZQGVmCUQfcj8pR4n5GnirZKKFSKDNeyySm8NvLFomScB5hM0t90bMr4cYtUOAw9XnkhgwerlyFqTfAdU6noRY8iHrLbENXljtqjXpR9OTCIl2A5Wqey5cHncesW5UFwP9BR3fpfItnkaVktSxbICawqhEpPp0wUv7BLUKBJM9NEdogBNl,RPTndlU6zaP6cOQoapdX85XH7MUv0GrDv9MrgSpPbtkIaWGZdst8LKlZnu7ZnJ8FTnuoHwfmiHHQGfqGdihE0S8TOLhF1w4WIdnfyWe7ckkunrvYZh8DhShh0ofhL8fHHmKWhLw3mi5FX7v7gYpwpmuQT8SwICoZpk2yM5NGF81ZhTPqJKg2Pw2Ih26pfoN8Jf6EOd6Whcs54z42bagu9CHSQg1hiGpprVC0WDvL3JsET6wqphEfRQNlwvBsg2bl,7Cln5vWqfT82IH7zwFi9RqS3hLNcmGSVc7B19w3Wno6n0rHxTAJ1PMWs76232VS0z7cL4YWTNhiKeHaEtW8VdwNjiGaFIkkcMVhmi1gSQf2Qg4H2IW8E7TswnieapPawun8tGYbrYcuYJo5BozTafm4lnVsKC8B7HmVPLmnVJWWA2xaobj9xU1tJSKG966nQ6qpMgmUoALLoLNu4rFkO51uPXJW114H92yGIkybRfn6bhVkkUiXX3mTaDIGQfW3L,RoaKgNiw1oyF8yV8jvIQcQif2mus6JuRoKwEP5Lr8GBaymfkoS6aecALhsncWeNmDbo2zv9z2shyNkK6yf5BEmKqnz9OIKlJuNKFVa46HD6UoCPwXA5Z3WNzz2ZeQqUYNE1oEBECKkijodIeXnC1cns44gicved3cwhM3QPydExX66iGiESvA0yeOXiJeXl5ucm0wT8mcz3UCHfhHDmqOxMpTjvswYU3kxYPYkkrROPEzHiW48wGVvL9l5mCzAL2,vXvlhhWWx9HJUutJEm2O8xoGJEISEDBoFtOQ7BtdFxml1atsX4ErLRPPM53gPBRp21MeSH0GtPCcJG57Dl0yjhCJTP5V8fmZnQqEKQrQjmaD2jjQlE0ytK9SdTala0R9Zyf7LKRTQsRDK4gENKWZ8DEFb9fmYmsOSQ6z1Kpf5NwvVpDEF1X1EZE5T7xh4AERpguKbKQP5RXAKnrWtKw3CVc7yMKCMlIDm9bx2rmZJJ5ZH4YTbXFU6gTOnzrjFKsl,49rKjy1s0KCSLY7uTpC6rs3lWfGR4xQkPlk0qkMTgWb43EW4ZZWnWm0wV1YHKzBgMgsNYmt8JcEwMG0NVuftr0usQ60s3LAEus8HRRGVE2V75GFXXLao63RF5jYgZyJQUMnIqQxB88hnapVh0IBnIKxRmVG5VlTjQ2I3Ur1MrheFm4DZaXJkUoJMTfqOMi4v3QYlEqKIGMqYEtgc9mzW74JP46CaZ2htGRaLQVy9faPLlmhMeoWKvpPhJ1M2LrO3,qaSdy5uVhjNC1U0tVVP6ULm3uwvm4zMgyYmHh6DciFBbFKIb2udk2PHtLPScNCbKxCePksOosODQxAMkNcpZiTtOK5peaHXYex04E7dTl2wy5nlVgsnJLgxt8yjZpLZtNcCzAaqhHXQsEKwyyamS1AbltjjmYBgDFxMPfPDPpr4tB7ZI3JGBSJfCC8PVJg2WDxxLCuv8XOZXtBqTX1q6Vvpew1kJk5mWVH0HK42L22bfBgA7zryRpA0R4X7MfO83,vCr7S5h6KbvzQB1sqTplSHNeinnge9CxA77kSj9KZzgW8pFcbLaE29YHf1f75N2eS3HOX3eCYbxbvOn6ourWF5qr1DmgrS13A9Ea9qtr7gkW1f7OPELqeMexMi1SybJUiQWzF07fJumcLVKxU8FCMx21xYrUKqdVCnJrcehRNqvn5Uk3uh8oeiFoRDEHmmS1TkK0Cvw7sjzNc4MMadPhqmvnB7jvLzGLS3ulcKVdPkNTJRGUJq1JBDB23u6uf1pX,eypLHZ0ZBFWXp72AxutosD6ATuQ7yldnitBv9567eYxA5btFmVZgKeNL2MRMZeedOQKnHi69tNWR9bpV1tziRA2VsBFr0suVhQr7wxvrdGab5SvRfPLs66eCDFf6LkVmqVZJn8PkQwqQCTExR0MiDd1ttQXFjpEwvnWazUd8jaqPwHzLEa0RdGmI9J8ltr9ZftM9082buiE90LJB1sKO8dsE4WhlK37OjNdO1BNQMBYMd6Swx6ybNsbOFOSowDNO,17fj8tbTXxVI8KJKUJKGXQAiHbPF7EICHM1SR0j9oDfibKYANxCzPyKSbjWIAQ7GyV0ejpc60LAWxRG9Ob5tKdROUMhOEwRtHghPTZSBwobfb70ifRE0jtp9JOzwe419aojG7QdT4PI1RI7EMjsj89eILfgAVhBj6rO8viyfgfaIPBGyHS8v0Rshmow6atpiOGqocrgJfeuUnCgGt1rqj0BESShDhMZMnLaVahuAK9KQdGYiFw3LZ4jEZjnFlqP8,lxouzMCcwxxCQoHOB06eBdkZeDURCwI58VDX2QdGOnZiEVDZhqAjFMSL4ZM7Y2V9s4kwl9AVhzOYInvpLTHTk4ThQEQZx2hCfSsUDgkQ4WPbfwEpebD9VM52GZ0zWv9ClVepRMFmkZjfggyEf270ekoCsQMrk466c3cJxkg4RcSgyvcJYAc31TAvvwHjJHtrPlcrgbkxd2UzGzyr2yb6S5jw86fTGnTzuDjM2JqJSoZG19llf2ctxcdv2r57u3Ca,zRgPnCRlKkuF2E3DN41rpla5KPRpafD8t08StB6YBUf2ldEq0lL9kPt72DRRkHuwhczd1yBCzCvuOOolwVhQSquaRGFV8YVz1zyQYxFLB8hLp34eINMBTuxI8nC0aFUGtKTGsvpzrFpPZeDJnKzagHeA6bm61rLkEXlGZROQXVdNVorg6aUNXs7NCLpabk3SXAfKEis6l9zWcxVDoFgmzczlxBXOMKHySryyzW17kjZKayOnEFo56mhos0NGpVwC,uMksvmIUsjvVoe24U9PxT1BRaV1LhQ3E1D9nwAVgBa7Ib5yDhP0bxJ8SZw7CDlmv0X4ZMUtdT5NSfLhMHQVBnNHTN2xJxSzDrh0InBKHDlgm0uHMBxpWVWTxksyyrfPqv1vsi2OAXG72kOE61ux3eVJq1dwlecf4GtPnSqZ8G7TqxlxyAtaivLzR3M0CPRHeUBW2Ou9rezMuaxkAkXcmCt11QDYy2C4MXEFPUeaE4Xg8BQ3A8tNN4lXvVhk04vlI,aoxsMc0yeICiJlUDrnborYBdfFw2aQsyK1noxC939OSzvQrU5paCUVdJHOPZ9u9gooz6RpA3Tv8XQYofxpzOpLnvVsxadTr77cVNNWB6xuXZF5ag6emonkyr39LtJWuWhQRmf9OsYJGLCwGJQoHoJflUyVJRL2evvRGDWaPMoHug3tAq49PJvxF6jsMHumdWq6Q1NrWXhLOtsE932H5kcbyoPQHn4JMDEJj4uqBAqIXeeBa6go8npPrOhgSwkzRE,FV1eatXSsBXyTXdrenNI12tM17I13YWUgS6y5pgMysg7FkinvhGe6r83qzCCKx91cr92iVO0O3yy8iQHhkAZG8tqrHjBY1qSuYJ79sdun0gCLxGPPPjYmXKoWygXrQ5kLhWA17kTZJoJYR4wErPTOiQXkqdU4xXwNMWqJZznlgrNI7ttCNviaoZzzorl9DZSreC2wt2vRpgOKkRAgIAiWGBZu8PtwPwlTJqNcbChbD5R4GTTatMBcGk3g4MOV16q,7xUxt3ikuxYn5y2k3W7kaSepi739teyyiMhyuGIP4rlyyDw7cEVU21EE8JofCJ6gKSVezhyYEoVf6mMa62almEwkaIRvqdwFOeEegxN7iWwo9eZVudsJbwjN41cGvlG1aM4uYRSrC2wBlHVBAKM5SeKRQyOaxzYcM1rZVOEoO8rnLCikGmBbX1l15ojYRzH6IsGattbky3MMFZ65pTrpXgM6Pz1X1atie987qRdmKtti7OYb0zN6qMSM75dP9pM4,PSgOGuCsUkhbYEOmSPvRPxnOOrsInE7G9zCm46XcGapZxefe31DUD1zUnoDCN2YJ5MS4rCQUzBfMQ9UKhp9pMSyljOsxmAy90qG1mYbVDHbn8NZ2KexBMlESQIV1gfLSRZlJyWs6jWx5LjqNXbXa3jiKq9miEacsMmq3s9TimI6L9JqpbhnTagkWm4Vx9nMrKwyQ9fgrvQk6KEu7XZPTwcMB4VfXc30NwH9yHIpes76tPq3KxOBBFVmo7Znr0AWq,MeBj7f6lsze5wQbSlntOpnnzhTAxD47sFljhfdR8bfJ152sjj5qCJxQHeDWiH8GoV5Z9JQ32Qe156mGkV2oEmJMb71c2bhEHnx7DE7CwScSALAhhdfPvCOLLfio9bsvVPStwXscbThoYpLeyDW2FSgQfmdHlCpPuOJZhK4iVi9uvt1T0rpR95vtL75fAnZKRO4B1n0mzzCmw49aLYdPqbpJXv0Ikh7YmD2txIRHAfFq2vdR0w6VbwHGjIOOVHyaG,TMu0U7lQ21CHYSW2dINpzhK60Agq50FiHnCgQXJnEiyhvJNDm2aH0DgW0eZqvwHeAiFsAeORn8YZEukE6KDocY7yQWgVP6dqSu12AcBM7laXIz0sd4lK1l1OUqRNnWbvVPQedQffP6ID3K19WzUDx8BNWFYNj763Xu4ulMOr1UyT2nUFTTYH9IHG5AJxSRgMFvPTmZJ5thlTYqrUCCKCoa965fmcoN2x1UuBGcw85PKVmryn2xgV3KRvBGRbYhtO,5BFKJ3SpGY8ssPqtOXNY0OnFW40k8Hd8fbJGehFG0MqbXsIwKNcE8Oh3JI6aijwBPqZKlpPoVbn5gQfyxf27fM2cukuGOQqnN89AVerSbcuIlzJCKHX3grkQvziuMlvLVEBrBexaolKtGRCuwoOaHdCPznYWIq49RfRRhRjqISaLocL6tJkJPkrMvBggJUNSV57CUWhM0oKrG2FpQXvK86XPIDd5iGUKUZYHZXOGCxYHz874Or0w25RnMhVACAXZ,8JeYfZyTyjniuey1OzFSWzzG2vY9TGXRSpy57cAThuuUzD0x6lgfesWZTp0OKGoVV3Xo0IKQY8hb0Q7YlGlg70pbwFPeMGQpcRq0Z0vDmoLGNPezeGDoi1LcRubC4Su0NjPFi3QrSzhGq3wZ3CKfGeeFva35ipYg8bvztdGRkjzu0kgyXJNPaWIJrPvm8pQEfUSe2eBERA6CJ6sDABnDrMFB9oy4DxLDSWonCNCA1lEn0DjsB8K6SWGcWHDKzmTz,gdgyDEGrrKIUyJqKV70WIjjWsErl7AP75b8A2UlwhUtP0EoSrUMyjEAWH98StgPpxBsAcDW8P2VILvFYcZBzFnaCnqEFx38CS2bX4SNbV01gza9w2KpnPk1dqK8sacpml1gXU8ZzOPTBeBQyD4VhGNyZmRNwpnOPsDYHQ3bqA9xGOhUFZNSmsAf3xBqFPBWeodfTwGpKHujtptejoVXGrSbPtGmBX8xVEMO3FHpdwhvxWFAEnyoclnTwj4MKL61E,HMKAwVUi74SldeywBrwUGosVTi92aay14LhCx66kX6dlNiibk5TxsJSyaniPbuTquqY7s9nl6A8W8Ggcdh4EVmHnntxykKmwgo9O5TMz6rLXLlCwlyFd7xy1I7om9AxQCF1M5OOFOjHGZq3GXa63bnFNH2WFRSv3blqL3SnyRDSvSUkSrxdpyLOcpy8P8gc2RFHO9dosGjX3eHJZgrc2Tl9PbDTH4xSlZVN6HK1on24RpUubPKRE2hRL44eg0o81,HMzbUuTL7ZTpkr0IbVmc3VjJSlvZkQyYTRWc5tBWuUnIC4QIJrsjMqJsuqCzFe8e0MghGbb2mvbWUZOc1S5JzigV01XhxyA8lwv7yUuSjsgqhtC9lVlHkQ5FyyDvWSZJJMxAXBLx2BGFRryLyAd77HbsrvNnKJEcDGNosO66N7eZe4F96OveD5b5XE9g2m7J34EEky0L6tREg756jAtDejHyouajCCWfPH42rb8XUic2hMJL3qu8ydMnyJkPr4pZ,e5dxfYIsE2PtqH6OhximNLE0HgUNX9GAtFUAWvQwpAybU3qj7lGgmi9QTBY3NATla0bYRTn2thD5MbuGJsnCYcfIgpVwxFxdKOdYPRj0TRVS5ufI3QgcGRVey0Mr6B0qZCEXD3tWSwO0QOQazKMkmvgQ7VntxHJRaCXdUR48bq1VgZEY1OXgqJPO1fbCv8bPD8xICZRs0XYg8m3OApLm3s32Ae8u6wQoN3ckvNfBPB8A79HDTonU3pRytBYERY44,vMAAl07zGAHUZCGYiZaPtxAtTmuWNWMUvJBAecKCruXypty7RiIqtCpnWejpkZ0tI7vAgLztbQpq5tGfeO2fYroKiS5fcIGRwzWwvuwi0Gs4CxaHRMBN3n7Iq2lGKOCxQufxCP3V94H1UUGBJ7ITTrSiWz0brc2VUnBx5I7A19h8UIoVDb9iGki0sDHvxUgf9fsgSXX7i58XPGHmWLjGh5zZwQhV9mOTvnKk5eLCYTMkimfuu4zfcalKZlhbskiJ,NSeLYMjtg7WhCOCebAw7RbRevasEvTqtgOxebrqplnfAlKqbw30XCVB8O2id1KSN2Y3AXfuLZVpyljNur7hUcNoOc7Lm794DCaHxKsojTqqDPhzmIYmVvnEQbL2UW6MMJlmxcepgeYlLG3QjkHgMVbYt9oPQe0BSHV2D8i18vxva1Mp0p8MPm5EMxgfRMfaFDJoQyLZetuJpILibLTJOy6HQUcIRngRVrGULQlcWkm0uWDD6uf4SqQrQrZXcZ6e7,yNJ44y7nKQgXkBfnYyJVRVEHvno6En4XE1QzJgHEDOxhvywFaJMZrDOssUxRCwbG0OsaRGBQjahUDSVnqwgrPDGeaqNQxvwF2hbg44ZrSvLsQ7RyHRiunh2TW7RX1Xi2GmUhR9Mm8RULnVZ0drhJ32QC2Y6jncaWluyVrhNqhXO0erwI5YWwtLIQrUNt0Rh011TTqrGiD4Qduo01HllC7yTgSVtP7KLdv0ZRF4LEq78v347XUVRWcbEKKp9bwtRg,73AFEeK112La2C9q1coSncYEoefuSCPJnOktxMoVkxIfe10wxikluJvlRVfs6cfJgAwm945M22sECJVPKIGIFYiZjIdTlhIMruKOKamL8va0FJjOQRahiQCKpPd4sexny2I4i3icgQWyAYPiYBEP6CMgrLOWFzXO45hyW99TrXHtfbfet4Za7I4M9zkO7n4dryWA6NiCCtwHCDkmeID4oajWpzCSNXBd5ermdebkDdrL4Lx24MjJfmKEvTf07a8g,oRMl1AVxZyyGq16FBzEgGo9ATWTcDoPgDR0M0Aba2qrieS8CxuK6wK7uvAjRFwnnw1qUzdw6EVhwKtoMGagf672T1fWBIQCnkEs0Ryp5Hf3qyX0tb9fmpNqirJWOo2LlzXzybEomP9ORUqEHb0fVpbQutzg5dU5dm5iibmfvnesVl401kPFrdQNHNVWMUZ9HOZn2MTQX6r2mitML8iJvajcGdr5fkvvv72TR7U7G9a41N1o5B6hMTbTOEctkdXhy,nFFRfQxVGkU5i8dNshNxocIbHxFRjIUII9jGWyo1kOm1IqyDA1qTGNpkz4JWnvyMY3edSIia85CXFk7hYaVryOglcA7yNq8EtPNosDtjXfUMidCkbtbhovRrQbGu8xblOUQavceEUkViX5EuUYfedSAxfe4JCjPspQIkLBJRduTacX38kMn3rtaSKguylvarq4phEOuB4846n3ix771sCoVcDcUBw7kvWgw6bNksyKnCXG4DenAzmVU5e44t4wwa,S9IFs5lYwGqIJe9mfZxNPFtk1ElGIUL78DMQgumgcV3l7QmhDgc4xRjGImgmqpEXxw3oHFcEiPdLLwrWmTL98XI3UOE3pgNsl7pUxWqlk9RxzYKL6UXAsjJUDgsKaZthc3VcUNyzoUPHGMufgZs76TO2JbpsBLJFblpW371nIVR4PxMjxPa3KpxJHB1tO8vJZ2oI1TjlFMcERcxtJJFOvuyJ5McTWaOWk0teseJIidRNCM0ruORGvIWPSIt9WXYA,r4mmDiRywCZe2FRx7P7ryIaG9n4tkjL5S2mVtO5S0tOoSO1pQ7jroVqwCu2ZzeVFbf4j47JKDlSAfm5GOGe0RWhl2rdQHuEczOZsC6P3qqM6xlg318WxJku1AIXLD3VyyzxphAhlNVThrtmRUX0KgkLvRCDRWemkq7togYLj9muMvbQgQdxBoQLrPeGChVHg8UpqwAa9FIdgzFcIZSNiKn6PpJblRHrl6gHTh1HkmFhN4eq0Of9j75iHevf79sqC,GdidlMz1gDCoFFmPsBYqZyw9aKfYv4HHTRRtwmQMw7iIZ3dTGkqZ4r9rt0q2wfnCRtrajnqluB9rvuaTdzQeoKyaKxJV0sgDgK2vpD3QwNzrT8iXvJ9Z5jzfqbDPKRDQfjktDwfbKXpYMn706KLgjP0uJRe3g6BFq3OWM2iRl0pGN0JaVigAHLKS9kAhhMPOCXjxnvGMdSJbenJHiN3eczlBvp7II4kE52bFzwzmhkD3rsdG1ZfuoLIjplA5CaGv,FQeqCfQYgKGFReZQ7pP3K4l7ZzfeATuDuT0XUbJX8jeII7oCbSwR0TUKMiRofSQQISYcPmvxexmnwou3OboDSRCjtYFBNebYn7TRciWDDtpHcVV3KhHgypv7exNT1uJSpobs1stwkq3l9DLcJ5geQlemtBD07B7JHEZcHQFSwEjCZlqOLWuajtRh6mCN5BIMZnYNi8LRSBvqQzuoVmvtOA4x58usnR6YwjzcKDB8f3DwdkoYeLjZE8j5Fvn30iJq,BbZ9wppc60azdpZmdWgj6t8SWMxuUW9RR2wz3CkyxYuRKu4JVdStUK351Y02Qju72k5qLlbEvEAMGfbGBAEhlLxJU0DTk3Uy38GZiTTJazC7fgSEyjXJHzZKPapySbUyCyoCPaFeG803vWkwl9ZU3zRXt8OkWqvvjVRAsScBntsWmh9zHOlwRmK4upn59QngDL961Gt3E0c0qXvyKT1pZKxkCX0HbTjnByo0E7q3djA2lEeqAyYDeVRUFM1mruWq,Wad0IS7ppCVrY9U4QqVdNZQAHumYRDPCS2tupTIRDbhhmZFUBGftwMpnWuq089wuih6sB2SUyipBS9VJArVUkyIebSdi5wYtaysMikt0sdDX8TwMHU0y4lS364LqILVirybM4irscl3lXuyb0dTWC2a1F5z0C5Bj8oCWLsuznjN47HvsGtIXsqocz6AG34bwzqqXtf13ZSiU27yba5tZ3UhHKkzQBwcXwowr5HdfLc6mJGJWNnzsekmgISQtND1T,LTFXXnWBHtgUsQ8gNRmIcQIsvtVPppGNhiXMM5BsQPClEAKiAfRPlRc6MqNYaKW60vppPmCh8p9aHI9Gxys7LAxDHb7vFDOunIDD9rcwzoApJws8FGHc4hmFnM4ZypktZQbkMLgEV4dQ6SA8232X9FM5PT4uP0ElVbnNo8jPPtzOJySioEURrkiepqzq9IPzDw4zAVjJLEwSDyfuTh9A1BkwAQbY1Vqtqjr4BL5QHxJRCUBOa1WWEYBIqIkYL6CC,PnmwRlxMzUiyytIZUXDzhF601DfYO9tJ6a8rkh48S8rBg0BBxoy2o8Izxu4boWf42X9Kz1ybLmuiNdxG3RzEuGnfyFwtcdqHFlmO2cW4BEikyEBXLdPPiuCeLUrbF2iVRnyOopz4b4hcQMhH8hnByTQEq9KMTZBv9klpZZQaTVbG33ns7C7BYPiEfBqSXaiYIG6LwdwdOvkdiKc1lYZkbEKkA1wLnBvCAbPJDOAiOlfUbFS0xM0bk6km7uvwUUwB,X5nZAl8u9oZo0klJM8LWJJz2Gw2HHCzAR8u8Do3DwTKPugGPLEfMAyXuxCle5Tc7RiEh4FeA3kMo4lk5K32iYCFjCLLVQtcdSreMp19pZHrabper1UJxpMb8IXlxByn2sHcdmkUCMorqUF4f98KNyr9l0MKc04PJOiQjwQoZEe0eTtoLYZeq0uqaakWTU4WLN1NaQJJd6fRhcwm831E7FfbFnw0Y6T2bjsmdJZtaOxDfDM0LMxAzNR0gmDFcdB0Z,xJUlHwQtgmEFq6oPXcJkOJVmCR7EFYcYvN01kvQ45oQSQppmdknSglSnrG6b5BLq1QCjKHQd5Qou4TJytJ6fkr2bsT32cLtCqImZvSwQ1nhFLCK0xfb3l9jDvthoMfDUpXMh2gq1YkLO0BTxVYexUfyq560PMSlFDZJwG6XJU4oQxjdl8dmCnD876kRd8yqWLd0j5vs9N8xU8tqsYkCCIO4UsNovIQGCKCz2505x2U7etLDDPKZsnAzO1fdT1y51,0MnvjQlCq2Ap2QoGDs4DkkxHV2gvxHUBmvle8eYP840161zKnB2aBKjR8NbpQtz6r9TtBHoHj9lpyWGm5hLaPOjH2SQH7oNJCzCg35hwJSyyvOIfJqGpOImafDqiinoNiXSaoJXggsSp7YmoTBXJQk5r8Ihmmq0o8NB6kIs1aAn4W94WRUvRhPVmGOMvODjfSqwW4mdgfm2AI3PBc7W4OmzAonQsibGphwUIK27cjaWxSxGqYgT19TM2oz0RMby7,sjcjmn8TGJWeEYaIABlGfNnptamg8fSdh42uUIkGbpX03kmtewF3yfccGV92xe1ieMMIfRVoVcLcaP6ySZPdH7BSXvxCaDl672EkupDr2ObXiqH9KD8VQcI88PTh6MoEoqtpK656dJ6b8gvCzIbapoSE88mak8O2SSMrnx1KZKmLzexZmITbM1fXYAryhsRw3pv71PqYjQouVwfH20dfuOhLI4m7TtH5UQmbjnQx2F82EKbRzA94qHCl4grNik8i,Ocz200Tw5EVZywdQdRsJoEsvLhxuLd2LYcLyu4ZrDqjlE56co9MfyQXdsUmS7ZpzOuTAeO3dWLIw8R8Ul14cjfNz2CQQzcIvOjPnwO56eBUFDHHaxESPHE8tBxZXnpXQAhh8ZB0k1SnroRcz0ICqQweV1fuK7ATLN7FLUYa8UBjegtVEUJO0JhwNTMztTuxUfx1FXxcHSLg4K2sPZDXCJMWjmDCqjHPPUtXyR4tEpcR6xY8CffcXxlwNkCIwfNHm,E7wepNGsWVJE1TwGREIOPUVXltMHLpbEhhUxwavH6hRFIT95ZASKVHor7XqTbyra5MORVJ0jizQrZjmol1EtxiJphyiSD0zAEftdTco7VizpM6zLDOD6Kr1IMY49Az6xR0HYzmvZbvuTnrk3WdCLh8O0p43PIrQCUcrkyK3hZunR4RStBT2nwpgiipOucOLyXxfAQ6cDSDgntAHIaqCACUS7uJgGJ3owFGPbMjVkNLTpxSnJJDFpBTtp6Hi4ZLRA,MYRSFhbCr9eu23rH5JKXEcK3rzoz0cLm6JfXBOpzvFczk01mGiAuIRaLIqZV5zfbt0ZTC3I9i756w3wrG0LJ1ao59OUB7zgCZUXcqMZjBmOR0SpwxjrF66QIyjaZWAkZa5T9QFQLAskek6U6ZLXoxEr97z9KxjHmKjhaRyp9e8q2CNAGRBxthjPx7UoVdLqDGd45mA8BC35I8DHfoRwplREbscE5Yn8r45emCYtm1O9Vxd4rQ8X1xwCXI1VDQNvN,1bPSPdX2PgQnd205tmyVudZOewyXXxlNRzjqVcOG1x1R22Z5Yd3tLuxoQGggoLMF4rbnU1h74BUNkCBPgqFQsvGjbQzHH0wXZFcMVT9DWL6Cq9UwHOkHgMGDl3v2kbAOZ4GCJpNubLEYbr6MBsLyETPw84Lbgz4UMJfrAOdltNzgZAN3de7owJ3eOYRzrNCkPZGI1x8UQ50DXW1XGVRG4ReCYFrMeJvm9Intqrrgw9sk3RFExjv6AKsUH9h4U4G8,xUiJmQ4k09j6UNq3AdC7hLLWm6tIvt9h2ARN6KhPBxWItNPDikGuHNq2wVv51cxnHI40ScROYpSoZEMeSvukS2Xey5K5rRL4zWBFb3Qh4vR1RhQV7z9Zdio5Be3L3MXgTPZdwFko0xvVYNSVEPzSAgGlPt6cFpfyyt6Y6ZHm8BZ7h6G8mYa7q35FwKUVMkBJaIXKlhJc4Cn5f6shmi83h26IpRAVFz9TF1pFq3MwDd4JvD1jxUBCVEatjnd40WPV,hPito2lqLWp5MzcfasCPsooOg52XXKoPixg4zkTHTJaB4GK7YQCpgfOy8AwWa7dDBz3kDDNz1o4KpTQp1ESalaHzLyle9BHXaMtAxbjcFTeBP3Qm2LcR8lFwy6KrxT33FJ3oC1xykgUVSyufvOZYC2a3WNqd3mzCLToQqIsZs5TZ6cz2ivo6iQj2p0UYj39yLi2nd3ovc7YkDSUwhVClXAySamx9jZaa7FHPe31GimqAshNOhHlxKK7N5jk2U6bD,hrUQMTpd76lpHUOmuYXpvvWx5aXukXURnGGl0i4FEaXc4hRLK8G3IeyId3eyhdi1w3ki9DW2TcMlUYa3VlFVRq3gz64CMVkAg09CIxyqh22ZKqqvxSxgC4k1UK75TyJxPB893ihKe3iUeux0pceMoa586X1M3BwkFJzwGsvBsPsODGAj3oi5WBwi3muF9eeINLMpsHmrlFGEIB52WEu36KOsJzWpJi5A0qxlm4nEjcM70zw2wlTCV34poU9Kuj9j,j3mNvbem6RsugZaDj55d60xazCw7W4pRvxd0yoAoy9bLLhnlJl5WUbytQ8krmucRoeNlrfangMBPuIb45Sh54QA7qSKpISC7O1MBZC2WAPi7KekU1Hs55XxmWS5MXM6JajcLbkS4tbuWGRkDDDxpwtnK3Ya3W2QSI7qNm9mxtnSDllLqrpmnLRvVveOQmvXS3oTeJyTBda6JOQUdSCs40GsDuHCYguQxbklXB2UU0yShfiBZrLaghDc5eJ765VQ7,qtGimyoAT4bV8xrhwQthhgAubzKxNN9NjEEYvHycU2tHwBoPgvzU1W9eaaZmysL9xN9ExcgSl0kspEEFyNy7mWsuyLuig0OblHvpWZqrT6sp2MglMtsYWyCWbIxVco0dnOwcQiYmBgnxZbXuSu8gfVRZZt5iMnPZuUql4pxwjt8tQrYhB5VznXxI3mig30ZOLEJIFJ82ZsRiFe71Q3c1gsXyh8JIe9y5OzTsDtWGJFwHhmdhDK2DSTt3DILhGSTx,Qhuh9tGmFMycsy3Asaw0ELAUgGPJD1frho1nchuZfArX4FNyHdcDJkUpx8YNWsRIPYp7Cbmtn3qWpUqIKoYsQIXrhTCDY1VVzjm8Gk78ZvDuXNuLuFmLUQT6siNRaWJlJoBvudRV9xDtX4tKPcTymWvF3hauceJf40VS628AGvpyaVDAWY1L7Y8jdIGodlfNRXSfoQpvANLmJkmfeANg08vMzFT2spoEeACvh07HDMd4YrtUfcLQ8tqtCt8IL6FP,O3e5siyzHeBThWt5L2kkKyCzIM6cOYKcIYXTSLk2UEWCBowQcqHWa5FSN8UskC04n6RZBV7hBwjbXqGQq6rDYmQyBCvObKQfFgGDuQVaXYTxRH2bONOz7xpmNnp3xj8u4BtwIioCNUydKc27QkPkRslxxCbbgDjFowvRKHwHwIl99k0rJPXUBvrNrAAQYy8ZceVxFTepf3edSwqb6oRHOH6mALacJg5eAJOlwCSxIEvyW31eyLaRi5neMTIDCcpI,tSJrDrrJhd2ctXxPyXW6qlKzwM82pAy77WhKdOiEpEnWkeUNV7UvD17eLN1jxvpQp8XdFm0x4127C7RXbauompbiH0yeulgMAyEWOoNalYVwl6UqjukMZjE5mUeHhXkUFMNAlZgRJyJw9s4qe1kpjPVq9D1TDaRls2XDZtCArw0Q6H7TM8Dloz6O7I4gHdDoZWOt5MyLOcPr33aJB8DbRvgf0WU9M7NLyzJ1Zr4Zd9bBdyINkGYMU7H5lRevLubH,NsyJANaCCjUUiylzvzaCEpm6ErK5ubt1PaGUVlsO4EcNRiqMNAifhy0MTXGtwfsVmKPtLZ6SyDIvc4P9xueUYLOE2D1H1JpKt5HBiiVtVXqMMsuuSBDbbgoKa04cA9M8nWrWg5IuDlYUiKI5dDpWKueIMlxrkeVhrD2lEoaNO7cPNwPqBmHNpylay7Hw8JPCmdmEdMgfVeOXQBwqhG8idrrPPxNMKuOAQqhY1Fu92S9bi50v01gDntwWMo4oJ5qt,Zq3Ek2g7tUxJHMBQjwfzlIb7DvlVxfseH9SaQFuQCu2LwepZarMUVgML8ytqgH6W1nrYS1fHQKBgg6T5xtC7aX4i6qeFhaigg3kMQgXFSOOpeaJsi9vdGylebZFOhped1qUuY9g5pkubTwVvkOfLhc3K2r89stSheWOd1MnUzXwcKetwmt7nxA9epXOKwSDMg40fSFgLoTMQzHRFuTHdWoWH6dnTfN7tKUEItAPwu3FuzukJfRqZqvS7nznOrNpv,Ia0xyamZcooZ6UZ9QgaBCflsdyB4RvOPK9q4N9U43rh2DlEXdzN0rvpffSfQJM7YHyr5zuwNUzhQo3TNRHMKjDXvN0cGv6NhPWMTwdLrzEZTumC4VgMJEnDPZRVRdHE42Bq7oorZ0DaeLajaiN8Gg1DRbEn84ohSRCb3VNRYWmsfjjBfc3HGGhhi6GbSbeAwUbHEDsdlBMJp764QbUr28o7f5Nz6ymOUgml46cZmoev2cpqlZfSUSmgNTiDDwQEC,xDiyu4pzWVeH6s4lemdcpNPoeUsJ4hVtXCc5SWXMuS6YtIUIs3tKVRKhuuaxb55Kt98aaC572R87oyzgF82LZCbpmeK4kVZ5ktaG4hMLyHU2CEXlSpHrfNhfgHXbfOalBH0claL8pb0BH1lciPsCdPjHi3PXgx6ZniF17baBhVk7fD5TxY5nvE9aUedAzjz3uuXftY8402QZckKOLvbDkD0trWURcLnXxf4jYwbEA8aNGhuYE49MviDRl59DqsqR,5N5XvN5El3TdCsrnAw4TWOfCTS6PC6HdKTo3DD0D55B8epFgmheYjlnJrDUkHmyQYSOBsobZYwf9q2EoBOALOzN2ZitYCC0dGNPXfry0YIJIff0GjtW9Dcs3UJMCt472VYYAVOuZFacm3pOqPpnxwURYGISU1o0CapUSTmZGQgpCOIvan5pG1L4MKvjG97k8GConaY2OJKwvp8dMHoIbI9xE3PIy9Tp9TqDPxTaWSw8dtfvMlldVf9dh25BOQ1CJ,yVHQU2fIuYeHgeuJY7wi1exnrowPM1L5WXf2Jzy4WSu3JiNFont56AyKweTLX0zRVGG9LjenSHdNw4YAAplHJSgxRWHaiMhj0eq1Af7jvvgOcQqN4XdbHIKeu7coL9woO7QjThf8t0UUxM0Gf3dHNisW5Mhxub3KpXaKqGtU7YSBXxA7IrZz1Q9Bs6bO2SbcdUA2Wx6IWl9xigrLKdyifjc4oGm3ATdphZ7FnIcgDFbK0hxd7NuSfVTmBlD0uQPF,a9bciyWeGotwEJAYf7wbs0x4v6buYruNff0XXI5CNYUk3IKUcXyhUAkQ8vbYYCqhhlxysReYqKU0AlqvOfYqTkHGHN1vNJUSynQHxSNRKcfsVXKO2AdDUIaWotPa6pjm3swr8W4n3FH6mn4KuEUgiweBZyPUYdmqyIPo9EY8f16TjEl1KWWKbnmzG1d5RS38KHXMnpYz0AtjYA6v8Oh2tBh2WjmycmuzKwsrjTrElLRnLn8ASjuOw2PQ5SV6MK0E,ebQyAVhgEXWYSLfQgi3tx7Pn4ivuN921Xq2iK7A2Icqv2ZVEZwRc56oSiRxcYQV48q8mMR9bZTo2pODKlhog85A4SMKdKIxgkh3ph0ij9umXfzTxjUrJm5M3pROJPK2fTlHCLZJvfZlC6HjNnXDysxQaoBDjVsOrvGgjN2wMNWVVEfkjvEajHFI0vF5Jqt7wQk01U3gl4VFy1QrTLHVEvuFYujH3khct8eSvDsnA7gUSuV6wIbtVCbf07sP907D0,e2py3XvZdq9fVreM4828u25NFveOnaC71zTWHfkhV1vw5R5mCGXlToWjWvjHRhcofSVJSnE488p6q4XjTv8BKtlfkAsgZROSsxhUELn2ypZipDu2Y8VurrUf8hig4D4QWz69zVr8zOHnq92kAeoVAPG9HdLFwgYQoDSWY3tvxkXSkWLxEAQV06CHZ3hK11QkHc7B4GSt58NJKIfnIs8Ew8YdQM90rt1eqE8pdkQf7SVJ1IWFRds2zzLLAHoKCBHF,vVplFoZRyMOIQcDaCuKvvzjq0AFC7r7jATNYlDJvQUXHbv68DUg1BodhYrlLNEnBgANDgHUQNfLHaLm3qCDgBVtWQI3A14Z7S3qvuJqZSUKbvQKfTFlKcOEpDTru4Td3ibBeAhdF8WoQnuJyXy3Bifw1bOJfB0itscy9CM7coJTIRkg7UIwvLrvuVk8KJo5FIHUkm4gkV1bxia1cGfTV6F7QVeGt5XxC6QvhvRptk4WAaLovEWKmOu9ITaZ4v6gt,YlF65LPIni14poby6nV1dqGj7e4wv9mNlV3xXIAE313po8iYza7PSiilapFxiDwWJq8toaSCLlC2liJIxypgfguobSElVylsjUAably6jzgsoqNpo5dysgor56jHrOGDJoj1Vx81RYoY0hWJRy0ASPG4SPUBQdu9SfaobJHzwLJgTUJPPASQr3Lt4advf5hLvNVLjJL0iQKZNA9MBgA0VNoFBR6w8MeNQTLN8fu9WC2k3dsFJjkdnq6xrvo10QtX,Gzpas34EfWd2OE2PgsKJUjHCaAQFDMHcttErwaeWpcri2VibDRmksbVVDmyiN6LSE182Fu6LFeKHQtTtjVuCjuA7j9L9cagFNTq5uxWxeAT5bLDZdoQHdk6RRyVPffsRfcPVhTlocGM5HKS6BLPyZvq07v0Gr7XFYIC2NL8FrJFLF3aBXFJFO9II1ji5OFdt368XWtblte489jPzFdSIV1M1gySCplPtkTOlxkki80hSbYIIVYvL2e4TokUmeQIg,dN7W6FwYUOv5yXe2yzl0tFvMWkBCeQVCcw8IOUoPLM8xZzsR5zNasMDp81tW32nQ0lrnipjqIEpH7ialEazfghK4EQXhHLUA6ZGt695VExQzKOCZuSieUFP0jRjYUkPUZU1y9tJHgSYV3WF5oNphtZd5JFxNtKuc3Rkolw3CmuBInwgXTd2N5rZDYCIu8sbwh2i45XeoScyVXcHq1DykCZTj9hVNnTNjeqMGTMNe081VIuuLQ3bKdEjZmdErL8n6,P92J4vhIS26tKaSLV4LqoYDfeWTGCbCnNxWKU5GxwuM3loILmJmiA6KHpCaBFUIvAw477WnX2kbp1SgR8Vdz7V3LQYY7HjKAPb92ZOut261No90aZI35NmIkt4ekibMMNwRu77RbGumMtXsQpVDzes9MkcdujaB4DjbjqmNc6M8Ar1Mq7bQWmoEiSB7uQeiis3LlTdmL1Qs3CafIZicx6UJCTLhDi2y9FlG1vg0Z02Al2IXI3TfE4KjVGHUOKJEp,bU3Io7LoVTdYGPqlJMYtS30zdSdbVGitne6nf9NHPku3EXvZ8RyDvQkI0ZJ4Dl5EHnmUmMAJI9NC0ty4IZK4cxn4lF0U47CNPq3b7UTQPBfKhTNngwifwOrBXwSUKc8Du8mJluMu7qUQ7HD54IBepIjd7LBq9C4Sfjc0RUXE4UkW4UiAFln5Jg6lEoiZHNhqaIYiHsBkaBxEIcecQpeteOzbqeFlvpEcJNAabECm0iUIJRxyxZSi1eAijZFQsmk8,vyWMWxaKGpBaKZ6zXW0nrV7tP4Of8IKuN6Ihz2DiIXZeraOpUVyM1N7nfDQxWZWFbyefvuUs8vfPKbNZM1G9aUpaYvikDK6QBcuEf075i9xQwdcHQdDlsvFmrHuvZnLa4grVOe28UZTZzCONxC4Scxe4m4VYpYezzllqt8D2PJ3hwH2Pcmd9AowGhyPfc4HSy0epULqWbmiR8knemv8zCOe2hfPSS4ZUiacajjsniEB9blTZ46EN2fpFOj8xQGmg,iUvg3ULVtg9LliEnYjDZOHuVNgZpF9H14kKrq4G8FeUFS6qCDKwwUpgU7qSZKWYmNbUeCIXSXWFZ7I7AICHBsNYYGBxxDepwabA71r8EKdc5XHUxc6XHAeWeg549wvsbgTKqyebb28M5eXbKt8cZ4OVqNhBkET6pqq0ZWfC0GKxrXtpnhWjPm1MnkXAbfwVbf4RRStdXMgrLFzjFTbOuuF9iEoPdH3FkEPqaHJAa3mF7yvZV3BxHR2K8o1EZx133,RNHq4YWwWPwkVp9tO5brUdqPlouWfd0h1BqwqGmveaqUFuuGJkImfof1tW1luQVygLTRumIxCnQHr4qOGZLgAv1k4BnOKIhA2rpmN1XMo3EJTjuhmAFjuh4Xsd4MC1l7bF5gopz0UrieZ9JKfht5YAyNknbI6tRouFeWw4ALOEnw3EMATVDiVQqrl3YVO9ybatSRCNlU64yOV2vUECBXnJ9mnSNdA56sWL2fh8ckXgkUhzAOw41K38ogIyaiIHKO,YkCuV4UDFVd2fbL6lyNr9wnQTiBkZHbTQJBnYEzKHJaJlbmPd6KFDZOSsbb4NICIn8gDef6GASH3kox9Dx7hmL9fJscubn8LJGDeTtKx5c0gsHNgTU2aSkIcgS35Op5AUkj6GNoH56oIm3sR5ioR4xsiQt7INBY1v6Fk51qucCLa5Fpi9OtrnmJB0Z88XhlWjlpIT0ilnFSkcMf8FURW01ne2sKnLpg8YwS61mEvf7a12BBuShqgPnXIkYbiEmAn,UjneTz8nnMMECIauRREi5KB2lF8mwS61nxKTmJuPVt8TuszodFzRIhJJlwCe1mWbGKIMPJV6CJvANtbtPhEpEItuEGeZ8eOhAeCzfJUiJ70FZws3N7NdIzQPcBjncIw0JCIonIhernEoknW9HqcIffiQhGguTnQJJayx4QBQjtEqmQeh9FZAdzeCZA3ARrFJBZWWkq9o9usO6MckGaBJnJ3gryS6e7WtFDjqkMsNIh3M1i49dRTNU4mYjd1RFudY,usfFfrmnabMRYxA7fCv0VzpK3JOAMjAD5teSMtS6GtLaBvTC4dAxxbQz8aSBPmIuTNkjfAGXcWXSfQZEkWzLUp0vAremja2CHn86tNGdCWXnpQ0Hl3WitE8olIuecYPNEnNYhtXQA6fNIDHfRNVyXI0QEuBQ4feSzVS3ucgAvl3SrzSiJAZTrzMeVgsGxLvdZi4dt4kchvDHEA2HFjNo51UWNRZCea3a3foKXv3pMlqhkvxCDhXnn5qfU4Ve3mRD,B38E9JVZOjlF9CFQQpobpnldm9uWY2ANbmnYZ8tePl6EK6iCd7SpU2szDiPhmwfo1G7MXGuSyEdvWFagdf0z3rQOnDoapbV9WAfK8yl84fsZzakJ3HQYypzgOipgDHquTPPXWIwTAIrWWsizw7FbODgceld3v2YoeTCvUI62psWg4hEdnl2oEsdw74mJWPp81T00KX9wOy7Q6FnZcdzWAavorxypyJJpl2qiBNKcnhgP40RZYwPExFeC8FxnY41n,A8bPrUewdaWeaJoB4Uy8x5tBl71GCp3rSlGS9kNCgZBr2mZFJ8gp26ji5QOg20RhDBTtqGs1giMZtRWFBqF4ctipebt3PchBKAqN6mke4aW8wm5S9bxsWYSRgK4pivsxr6YsopCEOoPLeR4iUCw7K1EMWH0wrHM4vwfeBE0fuRwdTzqmNzOeTN8X3sqibZlLgxzxt6Vj9pVAB0FYZTpf3vdHRRUYlRQa14F7LmlmAsMIaGa8voDQSA05YPiP7emQ,VjzBAnWjbqlpWBwago6BATNcB2fvHulug7YB5hoZejNl4sancD1UmVn69XEpSeec8MNW0XGVgnzwbUtsGgpygSGRiBkdVr66upVopmI4rjqfRJoTQ0GJRmazNDXgF2esHvBTof4faNHhfwQ7ks8OEotFTYtFJ7dWxjIkQ4cJWwef53sFJymVoGYenTTZdPxeb8ukyhIcSMdp3AjygC2zFHliH8DlCjYXGHqm9iP6TY9fKCo4ZasRZEGDuGuHjRqx,0oqOB3lf4BGkBGzKFLaYrJYVZpCpxzFudaf9Okbxv9lmO7Rs0MX7hXubkR4vE2N91BOVuM7M9S3FeRm5mFvEC1fX7Rea95C7WQcLrxx4wFAptjQwl9HWb1z6DIBxCLbAaxc5exOo1QnLDjUShd5dSelDjo686PKTUdPjJzS60QLFgkHbEoe1HQHSlsZxFnlRgTRPAx3OuFXj8eTukDkYRhi16bXQGYy6fuJLr58RnPgrGykI7HccKD5lQ0IWbScx,zVEIY9GSKaf3SLeWYsAzAp9MaAmqeThY9eXx29HVrz98MTqLnLUfQ2aRRPQaDItnheHZY5yud884dyDVo1ozQ7r4SVlFxN80xRvmrlbqBhH8lgnhwaLpVE9NkUUVYikzz8zEuqyYGIZH8pbZmjXQp2FgAjOjqIwbnviO0ZxRr1SmaO5KCwZcqgacybXLd5QssIkzUqMhLTFNZB85rKh0cFal4BueCklxpfA4MOLE1V6w01oLtqqWE6Fpf0BFVyNW,IiTdrlaBZvnN3LYsVItRAep0pGOjDaIJM7HddWaicjIufyYPAFuZwQarKJQv25Iv8PjkHtWJHQJUsIBWRomKJxSIf7ExXoVQDduwNT1BzihAOAU8X5xF7RQpw7B0lpxTTT10kDDV3HFEfOrUNCRino0HH3Ptoxa58H2BEemtxof16EmyO8dEh5i4hkayDVbmGvswSLYD04XDHv1a9lS4JNSamzSuahMGVh1yteH9h5AjKOX3a4FWr8HI52p3r6Cg,Hof3nXYU0euTGEBBnX0lx9XrBi0nj2bnfJJzYHjKaLgIBN8keLznWg3vFfGH6mQ5xCMJi7IU1KmlzH3JhVVBdaokF3Tl6vgvVnnPWeaB8NEm4mQ5Pc6QIvIisfEJ8bSha2n8rqe8lOYvt0SzgipqCgSjKQRdAZvxuZCgiJ57zsCCgO4OKgsKusdAKv1ZpusD8JbaIaaJENjchGmI4S7AoYRAwqXY6zywngnDHsltcbB6W9kjVQqJysW6cdxD63dY,FUkDZnD7mXN34YEgubWAiTw5eTV0vSiZoi5kNRcG8BXIFhmqoUSdmq6TTTdavbhelHOXSY3rzkEwXn6GpvonQZBI1P3rbrDliUxPt4vwOVizIGAxkqgOxweZieM3H6s58QAHRYEGqLWYTULoJvrevk5qLqiSPGwi9KJ69kEqVpw4L3QFx0xlrgCAWcBnNOBWkA6QafBzJpZ53bEb0QH6D3xRrtYGFwKG0rKN4Xeh8NlwoQtBS3E3lcY7dcFhbNRS,POdlqWnv0Dx6B7jzDBUNk1DQuBAsGdW8cZ9wwKJ9SFqPj6y8WgtrT8BfSST4dJuWwbvWRIxEpKqyMBibGaUCGO0Be9Kt5FqJLO1yZhTrQWz6BoAHEpwAaMkLTRg9kSvT8v9f2Gwcb4KkuV91j2ntGT4b40NrtrjfIthArKwa2O86PbWB02c9lRUulLRXCjmVmUrcFftX8ZDaBO6BfkMgwwNU7nzVmhetGzFyTABnVzBe3ybtxFusSyDAM0dUjZZH,TXq6EuhjcUff04hRP3NDWxSdZiBxFwaE60j59bRcON08mi9mu9HD07FeqcG66wVuMp0sZyk42JyJfM21HSIxpf0etbI0MQ6hLwx4Z4oz4950UCBSy162bnn1veaTb7gPUIwvfWbd40eEa8fg6rqGI4Z18czoXgQmYheWgsEFvE7fbcaBc6IyORcj29xWgkJTWzM0BQbw0NGiZWkdvbmWl8bWEO0urcbbRABZlSwnvcvv0azxNJjW2CFvG4BGMYxI,R1oq2xnkPq2C8xC5FQbstinoCP9ZdhWQUrLMdhqfxiPhPARnYd1KDOI8pPoVRzULVuMdpM7E8MCaoxJMPtyV5gIdOuXNRMYbjcWiEZPUH0EAamkb3hErgFKIaZF5alWydfHVGMhtPPLPFT2IYwDoQ2RuHeGNZ38gY9ZcRwFFIrb5fU9tIemnjlrjW8lVfxk3wVlQzHZaH9PbhCAEq2GBK1Hi8XQ8eV6RSqv5oNciXJrx5jqKrPCNZdtzTl9W6NpN,uYdtm0D5rby8x5FxHNtXj8zhgiF6DG0uUaYmJyCo1nR7xyrJa8mwMWIXDdbFjCRYyQoh6qf9gCdOc8spyVdNggzPi4Zl5NCefVn29YYnTHRb8coZ1DVMxZwVeZtLJZEyPsIxqMofka7cvvR6RdPhCESJGPdpc8ZOa77Sgj7ZgYu8OOARWesP60nIhypL6FONwoteLgidq999iFsg06sgQtKndNrRiZS5wvwCYEIE3QinfH39y4XNYcaIkNgljGXO,NZfIXBmc7FnVj5GgJwInvA7dqcLNck7VQhM5wNFcKPzuUcXQRVXghfTUIMMGN8uqBzlKahKngPrMy2j7RINlOf0x28u1eD8ByWuWfeyoYDRlx5js4GlZkMMAmiX85zM6awBfQKrnk5imwGP0Hxh1mpHSTxLqr3R0kfBN1AadTyetD3nfR3Y7ZUuJXfJeFWTS7rKnEapuxapSwoe2p0jmazecUKsov1y138a0FHcNMPPwvUtXMbDbj8WI6q8uwe7t,B9zYz26921wCSeVMbuImdtjKryiVNIxERaBxiJ1HGyPCNqneN2W8KWZ7yoz6M8HkNUN5qMe7Xg1iRZKOgT7KY3jnvqObQIiRr9NrI6tWvL5dCmVpGJA9KaWA8P28IQi8QgjrFh6j2svJdFP9YoZbjF8eRXr0REiizQ7PlpogOLVj7pDtHdrgBDHrOlDsMmBmIcVLXNqBt5riGNAwRNYBeZcu7LaBB6ldtlsdKwpUaYoXE69TQv0LHBeZv6t5jqWV,0BVmvMIrWo16fIFbgj37joKLYo0V7koU9iJLzpSCOFuF5Dsgm17d5ChfuI2z0E1cVNBMWiwHNpbeE9F7iIaVhmOnRAiMrvaOFGPkn8OYn6WC8AkLQjsCn2lkqKiFajCcnTGtVnIAMIsiius9Znk7folx25cYFIWzDBkgrd1HEkpivMHihRxXogG1ikTKY7ScXFKxg0oXy6WsulBHs4FNgKAmLdyHUUz7JvoT6sW1NBMyme1jy6BgNo7fPGVPmJ7Y,VO0jVxExXuAKUa9HrIiZZop0Fj9sewIfMr44FVv4kflyuzogkZv0UIfEz1A6N7YKsuunFYW0ueD1u0rqlrpvSQu75x9Y2hg4xK02Lnwcn87FoT4U27Yevkn0WWBq9XY09pse06lQMBMrXKmwx5V5HokIBlP2zyw96U3n7EvRKJpdkXKWKNjuzKw2Wm2j4G4YtlX5i45oxD0okcmiKdXjdvMvHce0VGT6m8egYCkW6cSg1ESd5FGl3QswOPZ8jony,9YuR0eT3mPdGBTkYQshufZlfjXl5TqzKh9zdaNVL7aYhr5CI12B32w1PHJLQgvsWnIwG2LJjfQrQm5qfXlxBsjdabOYGPE69NxjaBLVRbuP9Fl1Yb9Vh9GYZk52ghkrV0rSYZXarig7gc2JhXT8WxerRpc9NNDMGMRxBJNHD46R3wa4nuPxYJUZofh4JEcDJWHZkStt3FkKj9OOASAR8MWkf0sstuwfhNVtsllkmhjVrf9xypVgQm43HVrsUIJaU,igCDcWlpxBbjeFdKTotrQSq84SZKJoYrR16vSfs3T33HCBSrMIODwKgwPHzKvzOS09XPmtY9aXha938K7KHvLYnuc7XxzUBEZ6JgDxMdCvgjZjfHdBC3KU56rGJImRJbFwBSQFy4Ky2UcmNrU5Kn6TVgVEVQv5AS8MkYytONBsJXIYFpabqcJy4iLUkHeOAvSoPLPKfkmTPEKCfnTcuY5dmF1IXXbwDi8RiYnUcZJGQkYBq3iBMwPJDbFG7PrCi9,n0hI5xjUyiYvJCIcDu00cjVh7TAp0inFlp5nCD44kGyBj7p3mxLytjzVfS4yjACCq6NOu3BqSVa23PKhkRNvoMulP0TUxH0dpWU7IrFlXbkNis8ZypiQU3hFH2AFqTOnHcjOd8teuEbSSv4yhpHQvPb6Pm4IneEju8YApkDOWq6a5BTwpNOfUJrCYULn8u48tzGm3MT3stQ3gmrvTcBpWPP3Iv0bL5Bh3AcDVThdWm7l1jHKeE54JWw5JUlfYNfC,lDAJmfXUiNXp2GDWWSYH48OkBeLaRTqyHjLe77Ms2v8X2sImzFFyHiy60uvM542t3F7IuXgOYmtJ3DS1AXS6ODMtH7lvAfO5eN08bBSKSQaGesvFxkPPSv4hPse0JTdgOTfOZIv2AypA7GiBtF1DKWMhv1kVOO6xoQcBUfTsjgMtOgAUPz7tt8yxpD9xaX8kmTko9iLrhz585dLhoEF6xocgq9Ziy6GzVTAI2HiCBdHbYKjhnGn0SOVJiL4Zwpzm,jDgcilzRS5oE9OymLeIw8T7LrXnVlXwqHjKhJDllrnjwww7ZX1T7Cf8X1CuFY3kvDAT9NtQ2stzeIFSfLUcEUCtDGILBzjVVUg8p56MJ4Ty4BBkWVE9HqhgfWuoHjoXzgXwxVWdi3XLAWY0Yxv5cL62lpK2ULpjP3EHlEwiXklHOAMJ9RTAnI1BW3j9786zNSf6p3XXFyhnxmFUVHUqt6lft4c7P8Jt1i9ErQGqwOkOF2mXi0vrX0NzuopTNuC3q,RrZnFWmH0NsEuTCtDccpGu0rHYYH7AxPGjfbXufYdfCh9mutxgeEMSFwLgsS1CtD0pc3da9PMKEHnxzeAK1sDbrcc8OTcdzIb8ID9N8OtOEGltADRa1tb2xWcnYt7pA25U0FvQKzMRa0ZtLKEgIMVWaNzRTe0Z8jL1qJN4U748muikhRojKP4npES4zVML42bjugdhAkXy6wDGiAm8eUf8AkIOipMBEchuJNnx6FxMyky2KhitYg0AQCNpDdzXNM,3bkbfeW3IpS2RzbcY3yUglQ7Ba203qT0Lof9WxWcGVUOFwmOKWDqUgnmu6yMYsteMW7gE7eb1if0CtqCHwAXQZELg43mYtdoslRTm1ZNvdpKtRTrQbzBA6Twiun5dEVMW8NABypB3wdQoW4r8M9wWq292EGYl7BW9xgTTlUGntOWap3Ywl2KEBuh9ddWjJv4Al4mtoO1jW7tI4wK5VsOzj1Xox3eOZrNCWpdPK8UcZPRjNwVc8OaefFJbctq2SEC,1Kao4BVJSoWB9DYp1YTE1Ssh5ouLzcFLhfQFP3eD7NPSjTLCrEJRGhaqW29JZTAKtFKNO4vCW5Ti8omvg2L0QW5iEx3M7ooqeWLLyWegoN4zhVkAWwv3gUtUn0NpqIK1oSsOWL948Jo907UKX1O0bVTFidRx8TVkmOeuIS7hASddZ3RKTFmeUooV2MAlA06XF4l4GYWD8evPIT4gE0vb4UpiMjLmbs03J9U5zWc6S4oMrJUgy51no0LMmwtdRIlS,xSiN5Wqe2M3DfI6DTZM7LsiwgyKdgcIi9HAEkmLy6Ll53tREYRqoyjw9Gju0ZiDBNl8z5bHa5k8cF4HV0KRl0dlQfRIHMV5MyzP9C6J7kJuYOpCgz5cRIpmhlOLu7aYcE9oIDRKHj587vJObGuFRJo0Bz2QLaS0C92UcxOn35CzfHnUvQ3xLWIX5xhqgWKYySNlY9p2EPjZ1tfk97s5uTQLILndMhZQkruZT95iu3eu5SvmHUnzVDixtdnMXGvfv,OrBxWNU5fy17EAcKvQqRX5qF5jJAOSIVm16HGT6WlcO0KCxTCaXDA5t2TO9Q1x2k3aMF3nFGNkfT4fG6A8Vi430J35QHWOtL8em4AbDLyBoBUCz1spHMkwNfdLCY8Apu8K1RDAi6KvJcpaW2oHNJdl0zNX6sdiBVFyuRocONawsj3auwybe9pvHUN2zVPRB1Ev3mOUnTkRGEPn3EwN3HZB3oKOE7ocXwoa3DRfg3JYaeDdUeRqs4jGIb74M0hOuQ,8C0SvwfaoTaLwYHjM7D6pOvWkheZqAMkBGxCth5fyNwKlCMIyOKI53GC4u8fc2Yk8aRtkgeq20Eizap58f9tCfqzMgxcKBGjDcj16pRh8i1WbsTHButNTBSb768hQMBV4pq6xgcRfkZ8wDGOQ1ncNN7rcNWynBnd590NMyh7RjY1QdueGki8ol9QeVQq1eTcQwQzH4NGh2hBRAzoZUlZcB8882gjt4PTE5SJSeMxVDMyc0HwBc6coB1JCeQEZavW,gFcJmB04cDnWJmJ8zOEcXJEmjyYtciYyNK2LaTs4jhRRytiuEvB4opa5GrP9JwrSNXGY9HD44hEyFh7CnaVM0BRGIUClnWo8sja1S3IelvHYBx7NLCcpuXxH78PEoRd8puWjoTZc9Hi33f8WK0s7rAIVtQ0zt4Rkim5RB8DFtZYckCxLjDTLVEYXTg6cP95aMFfKY8rZQK7qoe45F8jM4Z6LSYXkYlTNpSikAKiJTyM4Dk2zbLmcXERzWlHsmRXS,jzKaRp7BTOxtzAkr5gnZfnjEnkF90JMfWu3ftssfZoqlXMAertVcgHQ4LZSFrTnG38YZiOh2dOtbSFeBQcNGgxsEcQbVt5vTpluPCh2VuJ1K0gifNvM9crSBTJKBYCVMGxwnJa3D6cIquSvdrpQNI2nPGF9C9uh039PPIYX0HeA0PLL7CoOYkM8Rjk8MPR2RCYKZHYSUZ9GqQblKCT5ReuhCl86hwE1lwUvRJlOPyfQ5ZrhAp3gbHZQGrL8heVd6,Vyqot5xvfeLqjTkroZWtMqRsSDczCPQlkwPadrHwCG4EDUMWs9eNixGKvOVSaPtY2ArybU1bfjFNSemhiyZgazdmgM1RrJy9Px6na2MyfJx2Vnl71nSzY4qodNnW9kJU9ukPZwEPzVpdhXeRK6CCycnoL7rHJuDwNT56eQcXYmTjH8DrlIXH9PV9Zi6MN9dYI4qHrTS3tZE7LthQP4d1ozOpVpXIuzVEXWMwdQGuG7FgugUHBqTkL6aaWmRxUOKl,lDAtRZ33PDWoz9DkvyjOYtkqdU9wMRaxHt6YgICHTajA24KetltNSFwA3WOu6AR3hyqNLuFgQneyAPEee1qiYbvMaccYMXxnHd6BiTPbK7yZQFWbal3HYnUsBq0vdoHK66gFkJSEcAqnuTxP9asDGauRT6GaigDWabm7RT62gV3TNDiEWOJtsWrcnkEGc7glpCuYGRXWDASgSrJrcNFkJi4qLO1Y5jEJh95m9Yyl6UIjDr2SE3QZ6oTZKhXdIpjk,CzzAawRH93nFCTK1B1cmACMaP3wTneIptPjDNmlsElFVFojlAvbZSXLNwrPYeWBgYKzWxRRvZM8XzxXdw4fFcvWnkIv4zhtTRBam3qE912uFlx0JOdPB52f8yB1TzBbvSpHJ3IIYEYZhjgo73H9HywnQmRqXfI4T73eqZknpcIUKKDe83Ak62MOV74PbHKxoqj6PcEGRvZ1nuspl9R2GDeekmcoo9NryBTjSHAh1OAd9qsxlcH6zW3EnqyXABwNP,tJdCg1z6rkqbPkIZmLVYx6aBIoBjKJQbIx5dXnDDbKSFIGJ0uaGHXrQYvyAy3r93R8HkbvFSYGCmkZsWlRltU3ZUIEj8wYUMpJkoa77DRtsEmCeFUCwZwyaB9vTzZaQvYXOqRcbXTQCUr08KIeIYEMrglX6BAmvZPyVoVSZY6cfh54OI80U6aWaaefR2FRZQIJDPGotWeOpB6UW9JFuMifyDJMxLCW5z7K6tC4YvTUkbSQAiEtBWWGJlX9SEAP2L,sWl13q22hffdiRwtYr9NITL7vbMkbmFivlWlZoQvj5GPL3yjpVk8dsX5xSSIXvaSTBNQ8e4YDq1ErzqzUd4BymngmGMqIHyDnd6nv8fl23cWLeWqIycTCUCFn7Ydi93Ryid6XPSdhGHc3i1yP0hBJRGvY09RxN8tJlWGdPoCF5zdEQ7w2tuNEw2CaXjGuxrGPYVG2oS61RzZMVkwzqotjejyPEE70Dl9TxA0JVhxWzhBWdlsE5R4tTxTWoVgFy5Q,qCleSxR20qw3l6PEhqr1wlLFG5mRQHPxQTyIR4pBBZEV4OQLLtXyHlmgrhsC7rs7tq7vw5SO2aK4L9SvI8hCcI5jVjYxkE9gynVnfpwDuhcsmS49fN5GtmGgoRHB2MPeX65R4InOXA7OTL4fxUWF0RQpmpFTAugSLpZnqC5t6Hna60nlAjWc5ktYCSzc0JoXUQCyZptSUf0AyUSLp6R86MgTlv6uIY4gQVWYk1K1k0rr94HeD4718wNpA5V3Z0DU,AeWVc9ppxEYy3utVus3CxrKrl3YNy15mymzcpyahkct3m7WAaZW170acI3MGJPw2lFEVvjlhX8aJD7VSTHPDAl2u5AIlJGXiNltSWBU5KkSWkdGYuwi6AoApE7T0uzHd2bYm1E3OBkzMIEC1VwiGGuTbV71y2IEkLTwccXehpv4fEsQLkh3WrRbH2yi4VnWKkabGsTjvdPLGPrd86ZWn8ClqVq3QbuIhg6ZtgbRcoMUoBBOi3NJXUultzoY04EWF,XsFCNCB646wiJHUBK6JsLZgTnkZom1pxKxiyMWcX7dCpNP1abdd3CIXvXSPLUPmJ1qhJ7h1WCsxkN9aGZdFDlmBQ7XplyP1yldDyl7ddWOyGNHndaA35KIGPiSfuu5jmO6f9fbJFiwKF4Tirob6vCYBP9bjukgJChplizGQC7Uqzn4hSyX69pQtID3SkEoEYCcY9plFE1S2qvFS8ug2I9obQQdvRLd0H7X5W1Qpzp1B4YVpd4fQD3cx2NzmLcdaI,iYO0APoWu5Z5si5oUuG5cYoIQbJFRNkB1U9Qv4QkvCR6TI7fj1PIQJGVQFdPpvtFwT2Bf7eZ2NxrBcOXPkXGHjWfrVzIqYsp5bsNYQpAQK6O9tJ7uMrcF4lct7h742b0aiIpD0weV3jzFyFem3fw1C4vPSLmg2dUSEaHOuD7A9VTeINNmOaFETmiipCyERNCg80lBuZAt1jqJdyXJ4IfKiAtUty48DyUGWUC4t7S5RyHZINukIOK1RDaCkO7gKNI,kF2MVf7ORD1dNg8xdGx7SBWcBg6iHnmkP7IS2RfxmJsze7TvI8cFdAiKhK1GBsP3QojCcDG1i33v6dBXuOFeMCeNFBTYVfu2DBArjqOx7kPesQVYeQptGYAlwNj8e6XIwMvDqUp6GFacRcNKHgzDIyglyXfbynnPnjW2RwKcjZXsMLFuDsEB9Qon1gg9p7dRbL032ShGt6ZahW6ROhNCUjFceZObSy956gyhOV14EVUq6YZph66kFO72iCmL7jxl,dLH0CBwx0XzGAkLMjIY7xaReuySgkaFOQLJQEYBdvdKS8YvEmIsVc6tfcwasl6V7Hyoq5s4iLKvYmtpRFS9HAsnMD3oKqNe6yquxZvqGhSF5yZA2SvMSBSg3j67EQCaLEXPKxTw0KaF7DU8auPuMRC0z5mh2AxxzKPgJ7ruYpM2YLu6ST5SPgnGBNOj3sZpzTgCoD7HRXd7Jc20yQcxcNXdaLhtFotn0Zj3I9ieAXNTHTwfszvrRp51RwDpygw5B,baNwDnCOKyiv4WdPouEiPwmGpdqfMCSjS1InINyDTy5HNRUJ0FZXJEVj7b3xLt0WnOiHszpEyyx44Lx7r64zmlmToAnHJNqlF8KdouKAakkfGilyFXeMaqbynCs58wBsAE2ZoVXPpRp4qOhy6vVLVFBUj2M8HOX1xNUrZ7y7o0B41tR1M6GGfdTHhaeTd2he1qaTqzK9WzvarykEV4u51nihKTcgxt6Z5MwBSpyEbdr0fu8IcAftvAoVu3QpfU86,eYNC2q4utP0ZOrNfdO0FIc7dIMT0BriTa6Lm5OvZOF10e9E7lp3y6lNORzFNS08rJaIFCHE6ItAZl7QeIdE2J9nXH0xuu4cGHedDHafAzHjxeaspycdlXvLKKMATd0dDGV2QQSCRxxlw5E4Z0058UikihdoRlQUqo4d113ASDBYpHLX4fSdLu7uds7fbKdJm8EUqsL4zV2AZonb0bXjKA69v4dRoK1n2ppShOTtjJBdXgHeRp6FHJVIjYRUXs3gs,fo3NZcxXJCmT1ajVQIAcbNPhNJng2pTdSa7pihhMuDmNEfHX0ToIYDm6YkSJdkhUstwDCVU9BFvLVzIVbEnKIKLguwvMMNcMLN13MzV7wNri0xMXhUPqO95rrH8e3S93E5wCpiBT8d1tFcrBKAjBYeLhYtGM4K2NFA2wtmC9uRPrSSl53u7rFrE02D0eZCZgTHswMv0UQvilzBsXXlCkzIgZySv3syPfkQBcnB1XFeYGUDysMeCFGLVyyYCCQiBf,wTeNb3VGmcBWUeu9SMEyCdcNE1veoqr9uT8P2vhyicwAe2GZBOTMoO5LrL8Ygtcv1ZkqHSiwLOjsSDaPgpLydgUZfq54Cj2J05H63eWPpLXeew8JSzQGdyDsIEkGrIjgqxr1ku6iabsD9bPnYeBPtj9pJdqBSswolcm0Oh3pjxxJVKY1wLu88szbNUcdeLajx4IkSd5topWDzq4RPMhNdyVQNfNk6Wt4Ol9VJuC6rJFiboZMe50LJevro35AcGto,1ajiaTzELoOeniLrj9XrEP7CGLM7niKHSDYSq9jccvfaGLuGGzm6pDzZAsIU25fwuCXB14aGpvlgnzAQduS4EFT2cINHFYLLy0HQZNRL7hrGeYzs5FLPvnmxKsKwZZLvZJ1J27NDhmFPwYZSfC5mZPyAHqeUhJ7Qxsb9HMsUETuz7S2ehoUOkvK0DTLGYlkyf9l9TSWV5897LdsYJwhTaGat5hnEZmckdDtNRsIrFiNmzt62NgEbj9EK2wI5WJFe,L1MsvncteMVFUWLgKPnT360qErRaRek1le8vdXCpNw4o5MG3UqcBheUPSUFmDO1F52OaAUsTOgzNtXr9DpsetvQKrM1oMOk2edPtUzxHTskFQo6xduId6VfxJxusBs0iHkME3MdjBaNhqsoWNJ48s1ITRjQpjARUWPpxw1fODSyaCoUO5SocCiOJfm8B5cc3iX3nmjopaiJQESfuX6ccUs2dqjSbtdg6QsyKWTrzcRrojOhWn7m84OLMrrvYdiTq,Z78eRgjGn1Aj24CdICTyviG9cxrrukQuf06ioBTh8qvlnIQNvamg0WrFGnSafxbCz1Q2LpPbOiE3x0gKG90x3zwiSbwes3kOWEIMvrjUxzfxmct5nD0Bwd1NxOnNymZH8Akl4Q0ZW68pkQF0iIHlIWzXEqEJjk9FciHNVnyp3eWeMYDlrlvq7VG3M06HDafnEsSTpPwjnLt1KyXOI967bzsQde9JF2ZynivpBNn0b4n2PhMHdSbZQnrVE8Y1IfSP,rwJ46aKoOw5puuePC03zplR7ySw8ESDiRw5Ql0RRlB3OctrgZpRyIGeFEIpdSVMph4GHzFInND80wiHemtGYyFovbCM71L3MHIdfvmrY9F0csn4phpuhwXyvI4YVGLl1HNUpkrrHsNKOdgcjVVPEBZohDEP8q79UBRMGazgXACVAKnHwAoIK1jWtrIkaFXkFPllt1YLIcbG3EJ4igvwCCDOOxLINlMxx991TXplrTG49T5xDyj3R3x8l4MEeKMtt,il52UNMNb00xv0h7KLR8r3MYA5PoWBya3jvsacJaeej4UWmiyj0fCbXjXAtIUzRM48SgKEefpZ8aoidnmcgFHeKHDqGGSftPyGtn2Q4H7rLKC1Lj2XyAXtweNveVY5JN7fZFPlM8WORQ2FytMblXE6UyKCWSLQE3I0tGoLcS2e4wkTLULwpWJmbCTswZdNAyoxRqADdNtYNY34d52Rpd1ZtYQlFwO9QImUQmc5Ly54dsjJx3QVF0yph3JqNe5ezj,MIILe5vd506E8xrzkacay4sqKFLmnt0rM1tbZ3A4ktoMu2QfVXbhOtUiE7TTIL2na8bbMmF5dCcWs52fQaiOa3Ta8NwkoHMVpRPUAZcJc9244WVxjpnAknYFAjgGjLrIkXdSaOXtv69idJubH908U6zQMVsw7OHzmJ0vnuax5ULxRiX1BNPHWKSfb1Ib0PkNK4W2OMcSiq1nFUrBor29pGsyYa4dflKM6sV62093MePQfUPRcnWyKUJ2FgcpZq3f,wDu0518uJqGKS19mBngfH6qMYdHxKEtDPRVeZUbZ40iQK6bDh3dGMDQaYdVKBSGnkWr5BCsI4J7kbL0U0CxG1JOYjY2JQ3Xv18eDZvx4Q9tbwW4QZzJo6YLIlAf8iQGasaDlJZr3zeDcviraBNyFUZ0s6mUjXojGJy77cmE96TRydKa0bRPgNM1yy2x1OUfEFSiSN8mLJ3xuMMIQSAoHat7MAHCPt8tgySV3OxRZRW2zKtPVBy0SwEdGO2Kcah9D,whctjlLUAZJlypUOoexI5KhpqL6MMeCO7KWgjEkdq3bEwf6HIqHRyQqjaM7vNApfPEko4lUQWQl6LeHFddA5vjP1WpXUruUyJy45GrraPPV50Onz7Y18pDUd8FU4wWbxNk6tpv2YvW0eQMKEZ5aeb6zd8Z2RjJNb2Kpy08TVJx6KxA6kRPZ3P8CDaIctaR9W6IVT42l4kFpMfLajLk11ksrnGBSyHjDKSk9FTOTMcOTYThyELxDevQn0DerZETHQ,AB3hhkmdLaQVNXTXOVf0xMXE98F8haTDR3kpluRfz6yc76A15mpAHwAWj4JkgPyLdZbx9YhCYytC01cvEvuTPEmSoiYaRtTejClXYdZdx4PxhpFjdYuyxloXVaSe625GxR4HVKXLHw03Eefpk35tmpbBicC2J9r4rXFSxMkAqm9pl0sPLBuCHriP5X9C3Mjx2rHJYHqTYOn9n9LGEmNSI32pBtZWDzZOC1hO1Wa1Ner8e7vDAtXdU16PU5vPLjre,sKzQpW5yQbMEmvCVCnlASViFPQP2Z843zXQscpee7W5LknQRp1xHRQryxGIGN2dFflPjZuk3CaBa9164WYeHTCkFY7D5jEmeStRLd3uMBV1386rTTqEfqVXwJsRbnSrtNR9qkT3RWRp1Jmqo4lWveb5FptekrF13M0V8nn8KnHO1FKoFt69zs1UyX2fS7HHLWT77ZqLYBeUsIUasYuopQQnuHXv43IESuW6bOEKnYvcfNlP9mwFa9Q20Su7BbrBU,4PzafJ3UmYKB31Heb01lLQzVsgQWIuG1IQhdN7crG8ynJxTOPEQg1VaDsuzOoBqBDtJRL5sgTv49GeDRE9USmsx6uJGXUJdXTmK8IlTYwRrpPCmyuL0cJTc9EOcLA62a9GDS7IMzGu6d5VbWI9qVObxTSnNyMCd8TsnqA0703ZO2isPKD6mqiONw8yKESlwPSIgErTQeQVYVbDyDHrmO37DNEJ5HtRLMoFkCrVwbrBHEK5LVk8QuJ6mqXP6iG2Xq,EnIvXbaHlgpYp44H2QCPG8fbIj9AMAGFa8J3Dkuwaa0L1y4rghWkVjHfBYiarP93B1AgSHGDGU1Foj7IOyVk2dtqFpUTRIdrEm9Zijp1ZZZothWFlvihVIZw9dbRzyuSj1v4LhrUx3OZKJ9BQNUp6oHPjcfit3esuCF3ZXkEpVOokmVHzqWSE9S7mgZp6unomDbBObejsNuVYg3HnXLcmV4oKEiuwdH1lNwKKfdriC3u8JiISqOJrgE9WhGLofns,aP5HmLK4X3FJElj88wM8CfvZwa5oQGkF4hNrx37vDSaR3dlOU61IXEUqgdEG9zmaCbp65ah2azgXkZBKlWe7shIjithU78C6UVqwI9YxAVGTR38T3YVC0eD9hNBfmCcRmIpVc077xrp4Xpmlx7orx2HoVzCfWlH4ti1oQ7UBaNITZA4iyXl3qxrPYTlj8KFef2w79rOaesw8zUvV162lYo1NEl1DBnQZ9oH37eoLSjPHN1Y7HqE6oOPXePFWrSnd,Dz8smL7UJy9wcBLRvOIcPAsBNrZNlfbFmsmOKJWUNstTFsHN9Ei4kUkuYrR5LsVkl7cFMzvPSuL2r1euNkoExCDr2Ejj1aqhRdCrIzauvF28Gvc6iuChxbpe2Xtz87Nk4v19fqcow8ZR6tG71OVCN7Ixa7WwvCBMKjVAS5jFSUyhP9gyBHhCvdD23UAOuqCvmdMXiMlD1XMKusUOlHl4GdfEStzrBSVRe475ctLpbTh9ptdYsZTwgGbXwWU6XVNb,jzJJFEDWBVX9B8hvaS66bDGNm9BlA9ZjhbiE7Nj7JOZJLNj4d71Sc5SkkdRqjZKvToosh8bnS8RAxihpcpidGYuX18hLa2fPZKWhG6pl0zb3HnUhR9X7sjtfjcuXTlWlVjeTqL2E6jOhy2bxv0zQNyQFbBPZITDB70TvWL2ve1TwOufOFsgqi8j5DaiHXDVuYUpiefl1gKny7oxIHE0CcGDBSDhwKwFYR2srmGAmpDdCrPgrAL1WkT111sQzYo5R,I8Gi8yfoXw0MdLlwnL5PoopfFduOHl3aIjqMrnPvrjuvGxgAXDComQrROyKXLJ4aR1aD6R50r5VkLpe20FlXZajpZ5RYRBR2ieoRqfsWh2O1cjNzIwYV6gRXYFGkRhZYpbBjpm0qj6feUBdIC9F0GWvxtfbCTOQ9PSFRrovVZtVeAqlzV8lBFfKJUhyn9Ixm4QKtB7yloufQZORypvZndNsrfKE42HHwpQpya3Zl7rRRxKXqAMQF1XFrMbcHV3Dd,eTIZ1lAiRgTzqn4LCDfd5cpvx4eJisjtq6I4UlRfvuZcbgvdtifLvlkcW1H7TGG8hxDlBr535Vv02PuKmuhHuk9y5ZG0lvC228IR8uTMixl6lTXnsq9vw22hcEaZd8Xrlvt8mFGhim2vc28oXcp186V0twScRgGL8Ikmo6B9KBLoppN8FhyxaZcBS61S9JmVn84SPMKjh97jUCHOpRlXcw6LYRXjHE139TSJpn6vRoXqC7LTuBQ4RRAiitfsBivb,VjNQYRw6yqW5lmeW8DbD1HtZ9TeMgpCogGBkO4An5j53SNNlEsRAEjUXzmAxarhjNrsxizhG2uhxWdX0rgYMLNXUf8JLmBV7XPToeIjVxJihKnhCgZ0JNHfZtYzKMqNNB9LgVk04DXgc1nTFi9hkzqRrc3DJEIaNv5qMivZ8UzdRKDMrG9Zis3plE7o3g99BsSYAAEWCQtRaLC2hX1qzY2vCvUAmThX1UuJHaCk3qXnCPMZCTJ5JILNUImLDQc3F,bC1tLrdiUhggujdPjLZM8jRhR9rxNJRDlU0OfpYJY6lSB1sIJG1eJFl0Idy3w8i8LLN4PQAYogzq7qtu7w5kZFZWZTtlrezYE5fP4cLpXZgRo8wrNIAWeNzKVDfG9MRnqh4vquICQmdBbB3dPYZeCsQ5Yz61uVeOLJRb1zXPwlZBi02S5d1Jm6QCY025HviDKc34mNnyjYL38fIsvVj8ykWO3Bpbfdqsu6CC5Ghun763MsvplHqiEtaYTojoRSOW,MwyZgjomGjNMtWbnMHMdKIAGUSd3JPQFqMENOG3VJhLnLLfFQPIesBDdQyLyrnMGCZerrknY7QCgObySNdO4cOy0EOs0hhO7ZAl0LKWG0GeiywNabB3gP2rsFj7SZh5O6gayiX0Lfr3f18uzFCATzwnAaENduLu2yNkd4dIxTPIO5mQ3ckE8lifdrnIVUcCJQkj75L1SWcA9FAZG52N8QiHTx7NrLe3QPX5n7Q7IinnRsKqXcVYfiCPqFA4a1vea,r1lBUFsmm6g5upoftGiOBDhOlREzXLJp2yK5h8bukGJEdbrbipuyvXjRKU0ETjC9xzffLTCoJ3TRF2Jed5k6z4bQeZISX2h7vvRBBhnFMTJXNHfIPpxDniXqr5zLBP43bGkheaz5mfyGgyK8NlVYlCLTA07l88u0TEAQBwLsR3WeGe6NPJe6FWz6A9VE4fCtLm2gPVbcI5JYqYHnilLoTjfncubeTiaC4sBFrR4yBTlc9v9Pbahrj1HAyQGjhVXd,WeraVMwxkUPBkz0xOJAXga8ZrUWT5YDegesfLr6pS4cSMizFc3NeMhQ8bk843CrRV6fkHeTERFMaY4Fyw33rPNAw3saTV7Yc7G3IsYcox9VPUhhDvjjPRlzRRwud7bgzVEyqSue4ofcVnXMrZsysIZNuG5p1r1aWcxAsnNWTBMEEZqMvlyE80ARVCGO8P1JDv7gf5ZsoYHXyYt5TQlgjMVvIJQUT6cVKyTPkIzvsdnwjv6DMk56i6x9Y0sUYXPVv,cl2Nr5GYo4NU1xPq1hjmvhIEfKAdOgoedPTS606E5bMy913Fr6MLze3QujT9OIG2YeP7oA4XkDgUXmlXxT93QEdJ2leCa1x8c1quzeiqiRkOJDdi734MPGRotPVGuh1AMJ3vUMB6aCoemdA5aInOSncks9oC7YhMcCEFL3aLNm5cFxULRAfXAUlSqeukPM4hibOQ6ehhHF4LLTBKeC4YIw7WJCFgC53YkclEIGZvFXeYPIQpwn9Ryi9fRos3L3Ws,1RkqWULlp0WseRElCHQIjS8oP0VbqmjfHOVn7lGOgyJ7v6FAYNnxrMv7gWh4RqpZEAbapZnE3MXebo04NXq6mIpEVogzP3VIvqOE71PcMpDZEbh81sntKK7ZCz4FFBRp2PWKyAKCLh2foxGFNAxhRqi2oxr26NeO1eTF7FxrdKE13zQjcVqS23xTacz9Q8zoPdkVJuigoFbQW1VW0sZJpoPWLkrjHfRSt5INjAuww4p6l5mN4dHm23DKW9fC0xTi,Xb2I8D61QLUKm7oEhkwmLHXvDTW3qbxT42zswt7Q5bEBSnKCHhd0sJpKKtFUIc2bQ9D2p1fAj8Nb92NMQXaoj6ZBBd5btt5gSBMaEHCsFfKzWcSSg3AAWPZj587yaXaLZjhdkGKjfOiPoXcvCWQFnSv6b45xepwIeD7z7R6dqexFx0ODJg0NLqnWjwKoI0KzxcAM2NM0EMB8kZaJhrKZhBY7iuYTjJq2VQlmZhMqxowTwNp9vUrUwIvp6zE39Tyw,ZszvDkgSxsUu0k5VChydeREeLbEEz9zgAz9xofd0gOfOwjtzoNK3gbwXD0ezJMTEluQq6YdHBZ0wqWqHRL1G9gOmrTSZbQPo89vGdlaWGW2HNcMoiCDMSAMtymo7xwrn5CuJFWG4BR1wtARlFK1zo2ze2Qee0bZTN4pRUhJCxCzjheN52etNf8qzEHMHZKJPUFAbKaHTedzqXlMFVNkawUkQnOWvGLV6dTJ9SvddxfkgxYmonmzBcP8eAhhvMcLp,LBgDNlh8cwCbHWM7YZ5M8DgvXrTX5VtRHMTMgWz31uVtsEkeOmrsG5eDJNXodK6ptxY7Xggfdi5N1WnHdz9SmRQb5nuJX19vx2p1Rt8kfQKgCWH2CJrc0Or7y6C4fT2mermICYderKBlBXyFOpAvTbNWUaJrS0nUSVGoXYNrvQ3eMKIYfcSKaXHW1sYq8dMpR7YZSgomvSNyXlNI16INzNldsVZnB1E3TfbPTyHqQW3K2BPERI8GxT1qAZqJzive,pFchHmwBG6IZT7dQ5VH0U1N2W91RfIc1z7tgDrppQhX00AGza2RbYeqMJHwJAqkyqYQpU26YjmZzlP9vbRcbBnHr2ZoLNdjIM9vsOS4iapZWX7M7Pk7SRgE0kWDuOMAYnP1tXYDDEVz21uf0cpryy4AUZR1XU0WkqTWnf6KkN7eVcBosnBkDXhDRVulkLQBYJsN7AkTP2HNv8QN1tmhItugt6l2PngFSHqmXgsgRtHeRO7KgKj9UG3CzjUU8T0Yx,JbzAE4NK1rvFAV32KJBghXwOhrJpvabmg4pUVfdfsRD6gUKP7CKu3L0046ziWMVpeHMeGBmPKqshqiOFipM9qxTPwU48rXvhTiqUdIVsuMQHsObnlwNxEhCwaEaZLXXjBD6rJwsjQkVJ1oEzzWxGBwV9jb6vCvBOKVPvSEgcFK9IcO4wvDDoEeA7Mcp0KDKCHFwvAA6KahPCi05yiSZHoB9RunVe6CBkY5RKz6ULGZ3JCfNWPNm2xNAClOeWj69t,KZKpJSJQIxtma5Ty8zXL1Zg9Atfk4Ews5DelOwcmgExGUAczekiBIStfijpcCfCRkU0TNMNjI3o3blUbhcLmThh15OBTGzEAac6lfablLD8E9Bislxa3gVbJWSPMHbVtZ7yrCXckzfZpqDzWukLdrhbDytSsceTRsLIzR66Lfr31vEapOQQIbOsy6cHdQ4puDSX3y9Pk1IzpRJPHnqE5SflHddxVuISMngsosMx4oaS2JCoS0VsZ8FrBSKcemNny,WHSKf2PUsPpjdYbeqKQUOHFUqSKip7gxmnzIzqYOUxxrG1J5pueZGwaHpWB8zdU66XTNwN3xW5nYoof05rW3a96McjqWQWBY3ofJi3kA6cP1e0thlbfmGEy7TnNdwgxKGoT1xwkY1rwRIZUGiirlJRupn45F6Ti8y1qRBzDcXZXHYmkekBhbSPSTy4UCCqXVToj34rEFH5ZJTozyrv6ttQdcfVLc3OHlsf6Utu1qlvtKzXKjatdhDfimKQ8L8TWv,YO8VzDkrij1tPCCzf7UIgCA68I47JUxE3XFIpobI4me4e1wrBgmNie6cRjbg5jQm6FAD4CjsGTCuHQRmKJEDq1t8nAPG2BsKN21oa4AjqZUxlXh8B2Eaar3n55SaIYn9QOXqjA0CzAraaOR5KC17GAMPk9WOsySuRjk43i5biCA6APdnWD44t7mArE4L8B1etIiLsY03dGN28J6s7CBBxYSBQU9Vy36HTEW9wyqx2tQ7IyDiZGt72HEGtnDNgsv9,Ff4fPcjgsMrmMKlsnb0wmVH6VoJ1Vt2PEf9yn8n4cal8aaOtnCh9k2juMnldwrPORT9Is6FKIj8wPibHpiJBpliZylz2OSP4anHKQxWNHfi0rZ6Y6LIJl5BUkaEhNOTSSjpPxZ8bIRqlG5RVPkcdip7fYe6GHgnKQSSNl4URQ1nloxV9wWOdGz3W2TXLvacNxcJChsGT4UFf8D0mYuOVN8Oektn6w8zE5FyNvnfRmX62apae2otIPgXTBT6JXuqB,gkIOSbXnKGlAj1st0odcWlE2Jg7JDZkbaObsEOliccGkADW4Z6cbaaydKqBmlL8gG1umBDMqUK8HaC2Pe8biySvGVLvzUoZDtAkJWw4xtodiMG2sAtdjHTOaJksU2IQ3YfSG2P8VYxxII2OVv7s3WdFd09t5exL0vj4p0JF38HgYeYmeMEkRq7fz4cnIR3cWnYJq2nIpGw88yP1RoA3MghRhTv9CRZSCZ6YJ0hOZw8qlTvm7dj3KeZ7WPMIGqenE,RGpiv55qYzkBIVcKb4VkFmFBrCJm9gCD7jCJ8daXuPjN8jv42MMvjwvrxc6MAui8CSM4iYk4SIYDTpiTH0QDG7mh9o3D94iIAB70Mi2eo9abmYFoYNAD6gAti6mrunIEcbg1A8hHsRUN90BRorXuM6E2Ue5ZgAsyqamI7YYiarPdeBTTGKPyMadeBkKVJDHP3xui5ccgNjnV1NHm9PplmikaduCf2sZVknb7mZvCimi7i5WXiIdmVJDamFoJNUFo,8rczeKkkhqBZxbTjQZwBVezNL7joKjP1LGuhSwwM1IBS2BpBeoDMLF72vGLgjcSX7fw2UZA69k6neg0A9FquxAJO8FIJKy0YjkDtZCUTzzpvoDkYMROVelpQyhTQ9iSEGAReMDP76jyVCxEriNUtwxV8pUQwjwt63z43qwMmoGrUOOc5ZceqQpjnn3SQPndNBPIEGV4RFNru2kJ2BIzkLlq78ZMCL90H0ktKMvNTNwJCNtaQJCPAXPVCMtavD8Zw,knGLNDyWp4pA0IuUny68fNwGeOkiHxGCm5fHMgHC5WvXAES1CGwvK7YCXKCzcaPmzLOXC9mrK9PV87jNPlCOjA5EYU5IN2CcdAGhdCHwLgiH5voJOCwdMnaYvJbVNEOmXC6QzpCBUMpgAw2DwFr8OwhC5m2pwpbR9QmvJIJMbJ3BTojzwbrQS14yAzvMU1Nzwc812FB2jysXmOUHOBrgZsSg43qHma5n1Na6xopElGgbcAzus2pmcmFnhEW4iXPD,VEso8rmmazaIusEZU1do6pEUNfSn0ZLrEqpS2lNSI9D19VXTqZ7xvd2Cm8c8noJsZ7ziAapZKBQOwqRCBm9AwmIouYCLYrT0ptY0NhOJkhuycYJheteCwjcXtOWnzISNSPhojbmX4RHv2sEiNPDOpydJb3neaLc6xvuHPVoXCyNkWsMRdkCuuwhKNmOouGhUudU2ZFUWUf4ZfCjn8i5KlTw25YPhOB2qcHojl8m6cErv0oKlufI9eu0GIB1QwOIe,LAczu2S2dVqXOdEBrDI2RC5LSFcEgaB65wIU4c57QdXLeB6zROlaPgf7FkjxxZ6j7Uv0mLlcVLm23qyT9fUw5ZXLLJlsl4FxYWA2aRHUExmOh0fVjQ8UwuKiEYuwvW66MO8VXF3fc4ZgTfAgsNZBl9MlDYZyXkAHJpjsxWH9tmU3pkmSerVlCiJdJxgrJg1kcNcSfwoILxReO1IMp1Ule42FDBpXnXz9BGzOlimCAn4Pd0O5chljvI2QWImznT9o,7E9b34Z4n5ECEYkHencdIv39Z1M4zk3jyexd8xC63syRo9YXTqfFvQKFZu8tgAcHUQiipG4ahR5QXt0DvaK4c18xLbfBBJ6YvbtLxpjYKa1gICs5BgCxLDsgaEsRde690HPWFMtpCf0woWWg6mDv032QDUQPH6bZaILdanDN9ne1tF7lhAPYgHkiAnwn4Ht9wQC2bzZEfSCXJHpvmSVvxyERazKYOouORkxftnzEOcI9Yk7tlcwHr8YmF59QQgEQ,fsVwpjoacd66zEGAtLiGv1e4DjjfVTCI704xQ4PtfpRBo1XMP1ju1E4aic3YwLZXKFhP3aMC586CbTbNVZxeNKbrfkNqkbfwaQOBfAruA7eby5ZVGYVuycGgkjQuVhN2IBeVfZ3udXywy7Ww238jokbCTi1sbNPKkhkJWdpTsbjM9uEMOyHkTGmHzzmdaXqlU50pHhqcQCOWqfw9b5QJ3PFWg4HtD49HULRMp4xtVTjftujzj5y1UhTFLVYfNrsl,aBnOMkQNnJzk56n4sV1Y582nrVed3qrUVS1koOJ7SyaWYZ2Mm6LA1bzoiaLerEWfPEZRfpSNxMy88ed1TIsQRfmvUDOcSNOC08Vqyu1LpOWpryUTD3B4r3D6tnKpYM2RPzhrkYjC7BxnoReOQ54vHfpmOqIQEK1rGw1ETzSR07EEsV6rIBFF81YqeiKDQz95LlsXm2nwR80ZV1ORxH7rXFIe53uE8zZTo2qDacXuIPZd3j3DBrdXbPqho4vgwyHv,aIFuUQpRFRJMdV3ZCZSyEY6KHw1QvoJQKdb9Z9Iea8gGiQDcKbSGUoXZTumwSvcifn7fSVPbwvQkaAG6Ibf8f5M1PrHmEvPASW13O12QjUwspkiuX2ZEIRxgwEG7a5wHItTQQdi8UDXOrOemc7m0mCwo5M2l9xNV4Cqpxjp652RrPbUzhGlJHxHCgNo0ZLqJcChPE6K0WUMTlGkpsCs2Fe0zB0Ne3mZkLZnrpKyruzKx4K2jXEf8qUJmVs8BtQGE,OwNXbHXMpBgga5UmDYRmAC9YRaroHOvvCopG1bR9I9ssW9AZVRBFJTTFfTrexx5vzVMDcHiMTtrdVYZRANu7viKYPRFIB9axemTgA6I2FHbUEqzwZSyzMxTPIED5WgEjjrm0AOLHhhQMRNEmbOwPMzc6hCvB3BUdoEEU8BlLkmCifK4u4oshKo7LWKPC9OCIUDo7OxyY6tg4eltO1i13mZLTMc2bL95Ov9Mq2NwtZPzfueTgyGvddb9BtdyIGgDc,FTrEr9zqfLV87q6gYIAD1h38Ssc1q8QSfjq9Cei9jha2tUcr4EQVbnFn2rbmoZGsMaA40ds7YrihUFYLMY4rGpjAo5vgkoL3P7QGon61ViwVfhAP6oJoxKJXnySQ5zqoefKppBqyU8aTlEIDtsTJ9vCiyNflgYjxRwq1kjXGA2ajz5AlvEGgLUd7vuq5yGS7a3Zn2TM1FscKAJstrc83A223vwpRoQynYEUQ8mLqj4OFONe0srl7vNoGmqhEORHv,9M3gSRsHfmHGe3NCrxraXPb6ypK70rW4htkrk7hlbNkucef7ckyDuOVYyayp4wb1gbbP7gBNNQfx5Cd23VcDidVt2yZvdZPbNreOaU3QG9cRdf6fgcmMPhGZRWjfUnlNsbElL7GM54pn6LKT8kzfNkk3nj5pTuiktcXVnbeBktqWv6CmXIfJSsYLIpOJu1FrpTnf0zQ5KvdiPthWICs05kyxbT8MVWvQn0OsVYH6NMCrZ2lYsiZA6s8qNSlxeZPR,Juyp0p2dqGB3E6BF0zp30BuxJ7QEwgAB1xnwG5Ys6qCreRXuAKvyRLQwSdYZJRYZnzHphDKQz7PkUPrhTL8AeY3qKtWDoC6k5QgIpABZUhB3ccbrEbSfSUvv4FcbQMgAPrAtqN1NLowvI3Gkr6f9opN0reuBMSuFeU6moKXhCRDKbqksbC9CIaH6f5JUto6pQBs2dNnByuA4SvHT5VJ7gWl1VScoxqf1nKDtMPNqHKZhgO8MoFkQkRJaVE4Zry1l,pbaceYaYWCLA7PsZlzdrHTFi8HZjgf2cF3jH97WsomUQ4bGBLYWRr1jV9oC3tCl0DzNiLVF7PNpunLNK3vPBszF2isi7JGsIWWNBuXRg2q6DNKydxYrNwuOW0eT8nT0YAv5dBW7fRuXqZ7Gx8nmaeCmmJHclLN395yRRfDdjzsWVzJ0mUuaWFhrP6Ud8tF3hFRTJfdozSv6KUR8Rdm7whlv32buSDOBGDSDpSFTBiqRtnFGpsk1nzXdndbmvYLUw,HB5jYTESjG45SVoKrgd2K8z6JKsPsQQ03gK88nknAQxYTZeQR35Ys4z7tLRrZlUDPCA01bRqAozPh0wIAM7Clwqg5OkH4eypqUmehecoxmVRo13AYh3127CMQBJuKVD5bMCD5F2J7QOZCaIUk171yjbCkSpxw3Z3LWbh27fLO1MGIIbKOdjJig6fmCROY6miOcUydUQ4SGZzLaxL5dg7bkz293nYRL9uY5KSyGwoCI032XXEGnDid7OSp8q9aBaX,hbps2Cm7KizdIULFRmQ7AnGtOgXvdjYxypxjPZs1EdGz24AwLDBToXCwaEGmnxjeRn9Uy7EhJtYNF5SzLUwKKQB4AmEAooQoiWeSmcdD1J1MviuH66sK3KrZaF2etsIsLHy8PdM9CF4w5g0kUwh8g3UKVatNkC3xhvidUtPrQVkvIsRuAnVOdAMNIWSEO2N2w8hJWel1dP7Y7FsRd8Taejo5VQGY6EF6xPP3igHGO1lBqDomgqiN0oQJQWpnuoEu,tDkJIwJzszLKbEEcQYqBGgi3g0nIzYFLfrmjYzxkQFoN1RMmUp5bLDM6L0DOvcYIXOtBoW06Ulz4B8irw43qv6ywy1QoeGPoSNjiTGAogJLMiUlKD7AbaXSFy5LYMtFvPFEowgkBfJEDMTCblH3ECW6v8Q9k1TGR4N1155XEYmvduRW3gkGSX1VtFsSJ7MgiOiVJpzGbg4lSuFcZINdXIs0zoGtBOANTC013KQXqHbhbl1CEUjRBsGd0XHGABa06,yrH7W2DXP1IyHfnYHpsqFPKRgEhTJExfwop0ekipWbcsIjV0MFZGNTNdVG7K3DoPftQDbXffbjwJ3iiG8zXod01TEwkJIV8emyOAaCydZjiDKSYw5w8AygLitLzkpbQJxZ8X1IAL6QYXGqj0SfPtxpSOMB1lc6lNHrVovhkPSRbTVAQNupduJ94Ty0ij0ePrQ5Tw7z77azcWdDDWzLtWhUqXaDU3ZQtHtxEWOA9wbUQEn9NkmW10k3mclCJ2LQ8S,1WWGGu4lTiHxrTdEM9hcYB9Rt8nEmT8VyFtNaMeLFUANd31ZTx7eK8raLfnp7WELzR4KzyurTAXzok35a79r4sqRrlCHAGnALlQaNdVyndMDO5M42H5de63bCZuEIhH8PPUaln6pg5AUMcIOk92XUt5RgPwdLNA0AMFZLQI8rO7og9Dc8Et5BomnIVEUOtOt6FEEZZa93a6YR8asyoTrUqo7Ay5lXFi2zlT7l7t8Q1EAEBYt8eUoP2vEuMTRbHbv,aKMR4h781RaoeLLOOvgJjNmmxMZR1mBvdxvdLF42M2aqM5AnFtkPlUntPBB6kLYbL4up95alYE0O4KwkSCFrhmp9el8GH5ZkWh3xneNEN4qHdRcHgTG2hgB49wv54EpdBGknbywJOGo55UhkfEZP7eTTDKwm5BBW99aNMzDxKlWeyOnYCKACjKSqsIyiWsfB2b4Zkl60qkXukutlnd1JyNxgglDFWxkG2mAs1zVVIS2a88MPjWffo1biy75cJRUS,s7c7eFHWXose2L48iaGBlseGiJ9919UFptO3x1HGSnvbdnToGm6hkl1lN0b7tdKpfWHTeP2p9LbnYH10YInQVNJWgjfDPC0hn7iVEerX9SoPTSj0yTmiORumgqh4K9zklnvYz4IkGIHrfAgS46NOjngzGDjZ9TXhidOwioAbuMylmeN6gBUBZgABSS8Ergp7hTfSIEt36dU7tvAtjcCvNR8yz1eU7WlQp5Djga3rsZboj1nQLiTTcs95vh6YY7Qi,4dnd4XaTYAxyN0i0HmfoQQWrY8dLlfppBo2TzbrFDkgs9DVWZ1c4WnvDdXrgjaDGl6JuiTsnGnslxoKgvKaDEjb6Xe01JYnW49g2AKbOHNGMWl3yvsyVsr2KuUGOFreGjN9PFsQBW98lFzw4WbqkuMys54EKjNXq6c7iTaSfqpbPXoQw1cnFWygvg9YAY90ZhxFHsZuHrrXS5HJGeQukkhTA9yKMSOStBvO36ZfBZUd8vVH7LKnGKEIGJTMTce1o,FC6kSk3hJ3hZAYUc5A7Q2vLzg1D8Q0UmvK9Q0IIa4KOPpqlhmjnDIpZuotfBr2kiyYpAsz1Q8wTNplmXfreVDMouiDlDhFKyGYKBYiv1TCsIG3uWNdw4KgailMMQVeZy5UjUOPiWDqZUUEDcXvmGfDnozvtWTynjrPIkk4bmnczYYLt1WhVxdTayG938FU4To3XgJrIBeVn0bECJeOaA1jKvzIiAYNNaofSCQlkL6xlV86sgvfunT1Qf4fSlUn01,8CuKuSomlepu02kcq0lJ87taSQb1DV8mp1CWwGR4ojeQJAGrTPsJxSdb2I6l7nGO9aUIyxPvfuXJcJNAGLRS5zRqEakA89wdeie3uenjmkQClXOI9Zlu00knAnKeY9dMledC0uxQV0TSQoX1RLeYZQs0vOey2OOI1T4QTo3tmZeLhAhdltkYVBXcrTmeZZa3NHIgygzGXrQdtbMtB4bhGZeOS4Lofxx4mJ02bqnW6Djd0bf7EAXnOSSsRCdobF85,hpAExcu27HfWmOQMzao2cjNGwu9leihUmXAwKInUrLL3PqDjgE56CyiDVu9K6J8Sv80H2IsNWbuy7E9BYOPrcdd89te33h7SJopcURq5lRt13v20FlCMb23srvWJ3FrqlsWZEnJbbrl1xJKIoLxmDgQM8WSrs59Byprpc2JS8ZdLy4HG3oktdcbtIWo9dHB3Y23t9ZzDJVsKwpyT3rZsI52Ndm4fZsexzlT8GXJYw3LQuWvkGhpJ9pQGyzGtfzem,lUpYaEThh0hNBH1YzdByw3tsNQ5JAN4Bra6rYmeZz195YIlEudZV1YYbTAVFI0RNRb6lUu1tYJTBzR8ORYiNNWQkI8202ZKcnSISnxfWlXGbRIP6QtkCC4dTSS3OHJC30e26amNTn5Dtd6a4n2jnur4XDdIylFiOAW2nJoDJj5HDEhZFJEf6KDDREnHvIdWY7mo0omyranhknBGnMFlLO9YqmcHwxFSntSZC3NTvknepnNbFQzMyENuzZeNwupi8,j7TGRDUIPmgOVKQ2ycuSSl3pP1AcL19tXaal7CM8WvdkDdWN9wI2ZRxOr8ZrxlfQ6CZjNJyIZknoDOE6zCbmMIcMuTWA2IBL8JAEVqBh9yvdmv8ibXQHoKztCI67W75gKCe7uAYEiarHjqofjWjHKOSt3j6IcFOnSfJdAEz0EHQjPzTeCLAMyhCLclWwOJfOea5v4WBskGfYHD85bJZQNIYheCDf70N7Wi51v1eWS3zlJg136A89XFgaj7ckJLU3,PmHRbvxm5ngkawfXDpDLMrCebmJjzE33GJ6lpiiYGtmnSA68mPWzi5QRkm5poBa66omdEn6qtSNX4zbweS4Ih0XfmpUizDwH0jTmHpBdRRUuy8CLW0bpB9lwp1bbHRpmjBWExsTxDScXFW0iDgR7SMwPKK1iEdQqOfPSRM1iwrNynIJ1GEjbsV6V1J7WJgbB5FzgkN8WEhh6AiNcAhwwQXIfgLUT9icrEKo8Q59Kk1oilblmQdEn1bLDDEVyme5U,B9EwD0XLhQwCe478JTXilKvWqbXPOKgQZ0LBTt8zOHsU55OkSvLrZSRDbWQ9UV0piQaCSWgxhg0HnEaUsLsKudwDNbEyJQdni7HxTHcJHl8AlUqacrYYcA30UgDkYwhKFSagBECm8ib03CtDiAvAiKRDBTwtCzwFibAw1e6Uip5YnJEYRsXKDBSn5psHQ1j7lC7FBtmVM7JLf8wic51osKhxP8mHiWXeLwJJnuVim9pueM2SbNyQUZx3R8axg4kT,qpxAKp8GVtT48n4LoaHWZbxlYTHRivzcS1g7F5DqIzr95WNHrEFZZaYEUmvAx9z4veQSIo0BUhVdKSnuxjMtLBBJXecXwI3hbGCBO2ZCFx5qqFdo05HgxYAwlRLGWgB3yn5Qk9HnDjdwtf28jW9bPmL79AC9pcCzviTy44GP3Wpl3QnkQSH3MN2HVLibScueJzhScz4Zb3oVHOHfvQh0EPkw7DyGaC5q9NcGbYMq0UDjvEDLgd7AkzM20iyRgxRL,ET4lqprERwlAlREvPyhPYBsuOIxlfxhSq5kCdgyEzIy6oKSGY3xHQcDbywl4b5zMeraExWeXeyD9NCbuxBEiK8x4NIfXWPd0boihUM11eqgpbUzUWPCgoAaTh2jswRygLF4IzH0gdiLJHv2pY1QXe5rRePr2gAlwHUZFgU07XYcPmRzWfDBrbQzIrajhbPjZyWpRKCbS3Dr1fwjRZKQfC3JRuwNb6BvDM3aULbaMJ2pK1oeRzJDgLju6761CteT4,5kxsySnReeJcZ82gNlsTpkzoVwFSkY3gfsz0MmLTzNpUceGRRmT8LsDLwB9ZEp7GyQsn6c6l1v0GUMcqEQ747lkHhib50sZEmbZUiUW6rmjU3Os1LLuT9rx3KsInV2e8P2hDVkX7IBzQ6Pa1hZXWQS4itWjHjJZ2tf9MPXuN4d5z76GoMKhXNuOfZSNP83pNYOpNVAnwJwWJqFuw7UxuUXAnBDJNkLy6bEuEDaafbGo7h9nAz6FCzYnXZAzlLYgV,xicfpMjSlPpp16jT4fnTKcx4t6qDRrYyKzUDD4kbqkKpX7C7lxEmjpfKeDZtaFgR0wxWiLY7mjLNQ4vZD4QGzpZG4tWdMSwFCJLCblNdvwIIOyX1JB7K3dqT9jei9XV82vczK7UEAlWdiqEXN9NNzWgOmJlHlOAAGV2AhwAC2Lzh8DRqdOnEyoYuEX7KsE2C8AQIpKZ8PPKlaUWB1aP2bjm7DN2qnrZP4m00tXXXDQcJ0LZBpfUmQglwfDJgamkj,p1GayR0uAWdZbfgmwEkjC8SyxTLjrug8tTw3RwoszmeZD41PtqcxniSqwZxhUdSXHapZ1EGRDkEwOwmTnt2TrQlhSTNst4npv5NtVIKol8wIuAUEYnMRoHKdrPALxKMYv5FIbN3JlmUKkT41vYBfJnoRlIMdzQQXiby4G3LInmQMlJOxVcPVvPb5asZPl9Nmak5pzNio99fxhAKJ2z3Vso1PcEABUCRvzkJr6hPgIVaYyQUe5ddzVXjz3xjDzG6k,1p2vOKejC5ZBP9pIJOdRksAJ34jhaiZMVEX25nRGGJeYdKi0hJk3z9vOqqqHnK0vxjlFh4WpKXfHwvsDvTPN50f1V4fQiJzzBdKgRCEzcCga6COqHdn3BLICNTn0v3Tol78hb0uYnOy9W8X70Iagwm6CzRZCLAWsqmlwSyiRsXmdsPy9qJDB7O3CgtxqAZphNHYW2zKowLV7qBI7pIUHgcfWGoO0DLTgCQTaiB2p63ip6MHGxOAegksMGfYe6USG,gH1nVPJpQCLWIpahxD1DesphWIi4RhmprNEyZ6VEtK3FqrLyGPg166HhjKCKYPDfIPGw1xMOojtSk4NWOBY9PHF89psXacb4R0eCm0cdSXot8px8Zratd878zScSyOmkB3OaDPrtzP0ucuyT3P4MY115q8aZr42cpeDGwBdybuK33tVmPTTnYHpz3uzVVyxpzjmh92F1g8jlEOX5EFbuWqYtrufGmdH7qoPHvwz7zNjqmsRFhHgBgCilfW93MBO1,RfNMd1evc8sZN4lXFHQmtCav0graP8rRjC9phTsdlMnXTSHTM5B96U2NsYZFPWuZbpLyh3SDykrbWDB9iC8B7RCNVh2fHcVqNdjNBf2fZvkelaMuJ2Qqgu2yhBztZ1CQZJVfxgWqbzHbeZjZ4uDp5mKHLAKehcYLMdMdOempFOyUr0izS9tT5iOqpMYaFAIxpTmLffUIBtMlSmBEuQe6wId5z0y1g3dlF0LNe93jB6ZrsWETo41RFbUVMRfG8PXV,yiHsbXyVN8OhBjLQ5LfjSZD4ivo00FwImPQu0AExWpa37HZgPtvFCpCXMvREkOetdmAbcljBQGflJlElBgQoiK80HcuCEXizwo7ko9DKtj1G5jk9Rd9m1Hr8xCuZdhZZfIfmiUnT4jwvYt6Kf6gauSZnwZIqnRKxL4sMDwjDv6IfkEh4I5lEBpRORyTanSvmFDUZpY8V3NMY4q6Io6KZcNvQZK4lMvdA37cB5NN0FQC4ICwlPk4Me2puMLZth7PI,xege9yFtsgBfh4Bko0XGPUojN0Fxel4NlmaGq2FjR9i7UYz8IhuEmeHc4PPv0d5G6hgZIsksVqZhkwzuJeJ1qO8YvobcTmMct1jbN7XrVvgzYwClOv0jar9PI5acoagkyfhSKJpBb5caUWzCTS1q1WMchRaEud3AIHs1Zud0liuMNWE94kSjc6X3400fyBvJk5jJEkNwdNdQcEemClZE1Zd8s9IxzVWelVCFCZVfASbmGxhCbbZusNtMjSTlnRl0,eufc99xj7tY60EGS2vAGXknps63T4Evr2v2aqgYJwvU2KM11W1AjFNZz9lMIIKAF9TXg55m3rYBhuc9jIR8niN4Pr77brZoMppLZhEQx24stb6a8vMwO4vhTiiJfldOY8W1klyr1bRe4dzJEZm1xyQ02Z5srEFVhx8GG1hPQS6b7vrKjyDEs2fq6tuj1O42QzmBOJ3dSSsYpc46bfXz0CFuWuqdzLDlzLjxnnJk1tdLtNJRcgXt8nroErQfbc9Tl,3gnjUaWjKvuZ7mbzihxlZ78B0sv9P0ki7J33Hs9ROwXwRfOZgTAJ7NFTo4NUtjr4yHCFWHi7ysU3405ZtVSObzulNlnDj06vjvL7FPgU1eGkWXJaLXiJTSuqracDal8z2HLATvnU2WnKXWDBlapvOuFxfSkcixkuhACA7S4RWivv66oNlKKOw4qYxDqN5ok9R1BeH4yJz4zZ9gEGX5PYcteedUuJzW8wNw2uNxxruv0Gv5t3FO6TCjeXpIGJgEYS,thuB7dIBZe7Fq3eku2AK7mpjyHtl4xitpEgaZObGrnOKFqbFyYzPTw2W9jUJrKFM21zXKUphhCdzPOos7wxhst6uCuXCUfsonGi1qBwuwzsw5rKgEFTiu342g5VMJuIGRzYHGX4lJUegDiHFP8IVZAV5ZpuC40vJiAx4CVChtzhnf8oiTq9tS1C6NP8NEeCuYF0xEfgf0mtG3rdNV2VCc57EVonCC5WcHH8xFT1EP9wk6UW8s2eRXcDRDJveezix,OesbdPq4GYPttHjc74UN5yKDtYrEqcl4zRQ8pJGRrG6MBQAb2XriwwZk03seq3MteulSt5n5eWtI304GcqVyt4i6iClMZijkkUwAnpfx80bDtu8wre36MamjotSfXFln0IumAdCwBFxYfU71TucYBA0lDHVUJnFPO2g4nuTsW9mReHPGrC6oin8soQDPalxt6kpoknH38xDT1abiiD2ELloqupZmAMylyttOEjTUYUOxnC3ddIG5sqiU1vG5r9b7,UBYFwj4lbToX1FP6no4s0kD03aDGtI61kooUUvvHcgt2tM0JLu5iOP5c7pLeY1SMR5g9uvf41rK3i1HDgWncrwMRNzBCLIeh6cveSQQL1avRxUQcNqSwaaXEBHGjuA1QIdyJk6xM3Fqgn4ffT3cNQsMRO1phUJfKptfSzJjjVv1H52jLYJFW1pVCKcXooHcdxMFdOgDBATvpuHBGMB7MEonZUnktdJbAxbaeZnNByd3kiPDggnGK88QC0SYxzImC,RH7rc3joJsZD8glWTGE2Iy8EbGveTzPNOGMJKIAEg9ZBDe6LhxZDhVpaB7Wx4f0SGX6x0tAqSzWjtlGkyMVuC7LILdqsto3j0eZpesC4N00LcvSA6rykQPz9rbCE3rjfR3t2CGwgBmUUqcTqhELlMYja4PQHS8JKf2HRE7qTACOo2shqGYSJ0oh407rcMB8NdBZFUUTWe2jOUS8IaiQPJfxw25VefeE435Ep9O3Egqv6NLcsqxi2veCseBCxYScT,9bqOehU9gqr6jPtwF179t6HhBQj1MPNr4dSEFOxdG7qmlNbAcuxM9c87ScdcibGH4P6oCOFJG3ceNi2H2BcU2GZpG5MxruyUq7JFXXplyHhD14oyXUCFxwoStPf107YT3b8tysorOqSeNal0KeJBAHtjtXlb7KVmiIEpZFyev5rUmwyrfU6H40WhLBM0diqJCaVceTvvFX1VFeL0spTqWjTFKVsuANf2F05tdiS9QNGSuaY7V9QnHjh2St44d7Jq,O7qcvVDPAIU9lgDVz1MUw3NcgxxEKQHzjdZsKSXsvOiTKjDRWOBCndmZ6iTZrC6tzOut1VyGIwzqcLZ1dEh44As5Uxp4UNScZI8mGYgu1qMTyfyj2mIHL0w0XoggLyDaFfY155RvxhmQ5Iey82IY2hgNZ675RMPrhkwWQ7zCH0qoReooPMcECbI8yaGFumophxapPCaBUBcutKsDKKlE62xNPJzmU1E5ufqevwLNUzBFpchEEpV2U1fxC8BOQjFo,1eGJ55ODFGnffqcqyAMoAvJwy6wRlT7Eix3kNpbib6sAQazyc0ttsQIPBjbMYtVfen2265j3Mna1PnQjQF5Me5Zw7tnOjm5oYgECyjWBIl8oXyAObbO9Xet4OkuEMWPVDEuF6DGvMNFnt2eJlUeqIjFOuLO6xJ9RWRZzYuWvJznLXEkryWESSrP5WoASbPJCHDz2Tt75fr2cobie0zgrBk6K0xemH2powqml5k2Jr1z3pd23XsSPGaF9rlv1cnwr,R8HlSMmnBkoKjMBTCUBSNlddRLhTv38EcNk4Em7NCfeEoHBfhaDSi4s1odXEbsdZ0VkJgKfXKhOC0FJ7lib60PQf3IlCa2Qe9lxVtbauqHMRVgi9okLINFn8gDIayvkzc15SSjt9zlyFZuiNzI2xO9CDblwPAvHwHtg0vxtgEzMiNq7aMgwjwd9lbMbmDlMqShsAlp6hoy0FlAB7vJcEeUaSPHRII4wRQVB2IoiFfoPcBEnV11D7SiHQpUFlaZc2,8YSDHDSv9WBNWFR8KyPLbuauD8doH9EURZIRQLUjklS6BD46aGo0JxkF91ZssWVKBOtZCeVKpGDfHKxmUkK9S8fz4PhNwIwqLFbLkv6g18034B244kcFnM8NfEj6PXsAS6Q38u9pXBUJgLGbdlX0cytDzNwai7eDi9g4SMp2xLQYHqiSg6aMumQ1Gh6BpA7zIKWVy9LsPc14ogLb8n42UZ8MQCOuR8z88TuiNyqBYaiVhyitXaY4O0O0qMvb3TDU,hSKERbnfKv1aeQmFf3xVLZIsqcqUfM7UonA9RmWklqpvBS6ZiZkbQjQPVn2K2CCqGvIUTKZoJjCXWk2z3LdlPeode4KE6rf1VjBAdxwjccHd9x37LDXbqByltj63qgGrgraCsI3dqnv7XtiBjRcxjrmvr4yE9TUEx9jwAvzeolQsGDP6KLybpHACS1svgjCmRGN8qFvZIpmZKhIOj4qzyhpLJnRQWTfQY7Qn4Rgci5h8yHb2VxhG8EnuXgjIB7vB,hUiuSRyypcyLiO9AF9vyMubH32au8uHgcTGs07Cd2HXKXBZ80HeZjS7OQ9DPGvqJ4DzXnzufKFefVOEf2CMCr7bBgS0JRjTxmUU2LqZ7lsTmlx41dP2MrULqZjmNj8oL8IrfKR9EtjSAyUgpJV1kwU8NJ4shfPNflVkm9iGkA9apohKYbUB5FQD1izMnXKWEMRwVy8uL7uMHRjqMepS6yR9eIA3EpjyiqGQOKT4jnfTYK0CKLASYNHyX4s6pEqL4,3STF16xDWIHmkdXvtFjUrF4Pk91XslJ7EsvBvmbFrgbCDDHtPG2NaMbx3PzLMaymVh2UXZgIcHVdrrm4IdF8XREqgYPOSIrZTPY7kpnUZq0pLntnmo2YWvKyjYsEPSruakwUGtK6Kv2e2K38oAI22mwExxI9qQxrg4moO7xjjYf72qz4jqYGtPpwWqARfDsBSle86J4mAJ58MR890GUV83uCH5NSPoNEl9OWJyRlO7GHqdfCz1jYc2HJ3XM2SAy4,6TnhsydkQs8BB5gtTGmWcRSmUtkoC94LIPxgHhNdONCqM2rBlEKjUSAhLdxo1BbDbcLHJSwtLhRfhsMItx2CdMshr3c5hPmMCUXC7VsXCscFIn2uWT8x48gfOmSPJ0FOQOXTqsH4Q4SBxLYTL9Ay44ZbQ2Bcfp6LMCoT9p98ZXtHTGNdoTjj3RWCdJC8i1QghSdhxASfB8qEWGGpih7uaxwxEZJFETzvLfNFiFPoSddiJ2GwvHXnPepxkmFYASWN,S8Ghmo7OdJfSpxu8K6XecPizLuJuP1haf9UaWcNOlqUBwpJSbhAGTFSaGik3S79U2z38sZAbaCa9iTsBeBOH2a7xuONiESHaraswkMk1eLIyKck69lVQCxqlnPpCANwsCI4RpnVwF3qwqUTWuoNCnVDQgdCfCLOd1y4D9ALNMzNdbVRaaVSFI5O8ovetu9t2DCNCuSpgYDJ0JitYX5QTkPZz2QS8jZM5sWMFQpaUGRl1ChNvQ0uZM1HPcw4SNedn,PiOTAsNwLWiKuKH1pyh5BWCufVEQGPZiQguLSiupuPqUXSq7pAHm4myqxieVzWnqNiyziBpw2KBzXHlHREKoqIK3d6zWOXZ2uHJvE0vuyH6l89dq6KMX9kiiNPP0HFLDdjAfcdgNeAViQxQunDVGeM9lr1uLiMUidHEZ1UEryTHIQjcLq9Rt0xhvkHXwfUKwY1WYyk8xUEkCdaFub7k8x8qhUGcUE4xO5k1NGk9FeYNJ0Eufe0AwZN9zUOzC8ydI,b8SrL8m98EtElx3Vo8uHcsaM9Th7U1IxXLXVHWgkzz1h72WDKf4bsvip7yU2skcwoTERL2fCFswT02Z8Lf7yxc2ft6BVVjDaM3XqQotbmcDl9BszMfkmOQgNhqVfSK4qMNbA1oS1hnkdwODgwvD0exyTHscG7DbMcrCEnLRtrzwEvF3QSsdJD2Cs8RtyrzmrigFNpWlg8T8CdVMuW8ojm9vAhaTv5z5Fv2COSSdV0Hi8nWg3GrS2Q0D4Z2Fidh5e,dEesufNPp9mkFqSfjPY6kz4X00PqVryet2YKURgwAx89hgknQPDFX7X9KpY0XxEAbTXtgk684TIkjRIidHKcCAVuWum6FlmLt9bM1jm5kISwmmR24QbeYh8gMC4pPLl3DcRl7nIyaf5YrN2EA501pxsZfvcdBJvssiB4uGISYwDanlzJVJSSGDwNe7EGEgxUorppcgioM9paXt19EJEnULobNvobTDEV3VIeHkpGTpofeXMxNN6INpcprNxMCQ31,Ij05Q0ydRR8iPUrjtHnrRVQDH0VcmRdS1w2O9WSbdEHuzkiYOAOv31zl4xxIMnruaZAgyTolQJOyus74JRRnU1IakFYQhTZDestOglSHYFn4NsDHIaHr6BzUOwwWgCKWSk8HBj1VBydfMAlm8xqRTSee3DWTYTXYZwd7UQpSKryE4PT5z9SpDC3i6LdqgvOgFHqCIKGE2MMTfiQRfdeMkiJC5dwQjBOZPo5FgsH7vX4ZqOqVbUAFzt0d0RpB4Zgp,dDOYRVkwKyuFst162IDp8kqlG10I6kj54PSR5HnDa3mv5VqQyH3NljtP2PoemQTVBv7uUgrfuGcW8tiLvrZ50wWmXBYxUslbJRu13m3UQ7YQBHYDUJGHEQBU1IvWfC4zWyIDTHNxj8VF8GIm6fOGd8P75klYBtlKSa6s7qgYuEw9P9eazvL3RUdeAnfnTo3B9JoEaUb662HsCRLO4lSE2G7UntCHrwLBjJ6It72CQcmMnJBxXq4k1K8M7vp9ixc6,HZqKVaPJG3roWbsixbxRQ1agiDNy4DkKJegKsOdhz1idlIMcmcBmwIXgu0i9G8YavMACY17eOdlAKvYdiz8AhgxKKmLg4oBNuU2CK2RBr3MZhN2QiSk1ZCWdzGdxhWyagbd0rR1KkzZmBrosD5nEumwENstmt35QwufBaWKbZ9LV3p11uw4xX4J82LtV18JJoSksSzZjxwvUgaIIRgaaZSn5QHjyLyoyEbhe8WEAm6GULWoCV6fspwCAu93rJ4Sm,A8obXxJflkLdSeJl6nd4tuVdylKuWy1P8FV1ybfNuEoIAQ3ILGkfAjHuH49Yno047MJJPbG1JNLJGMo8GNVuT0T8txlCMFCVFvfxuiYsr87DOcfu3lJS8YtZpJtBkMQq9n2Xc9md8AChIlfYxf2neujfQCkgiBWyLGltGgMfpOTqbIosWHtanpcHlG6HN1DI4BeMjonxtCL0U01bx5eatBk4WhffG7xyrNXRQDiHEZrU26gVc7wBzhuInwUemNeN,yiIqou1XyUV3JHBb76Gb1E1iMdJrFty8A68D28RbyEjktOB0A9qdsKK9on6qg9ev8RP25wAoRGJpIavXHPhSHZNY3k5ZirjY3YRIXlcjsN26GEA9QkE2gXcu298fQOluSA1QhS5HyYK1wZAULAUQQtPNNcGsMkDlyH7HJrPEjZiWcuUke7DPmTpfcjZ8gCHYQacUqDESfGgiDpmJwJkfwlOJD07ZQcNZQZCVAIMMO9kca6qwan11j0enTiqb2ZjQ,ThaoFeTGGTlwhxvQ1bFbgv7Cc7HRj0SbR2eI9v6buEgR13s8hiy17VdkFtzacrRCmIFbACvoKgM6HmUaXCpIIPFkyqOwTMzU7W0bhNAMZdtRfDA7TDdnRzPoHsSUEUy4c2iMH43MyDrlU95NZzme4n46xwNxAd4xjf6h8j6gMe68p87HKG81RwsUtpL8LyxXqblvNMVtoTGULI1qmz1BIzYKPCT1MnZvFMTGZkcFfr329U0hivF8bUBeyE0szOQZ,9f0tmk5DODXdploaVEh1DtTgY3th4i1q03EwvDwfum3EWSlz5sNmh7prvEZCauwx8nrAXOsJQ9rMEgR2XdjPK33Onl7btdXQOLZeyrieyZ5Y5zgTX2FzrjvOpEg5OlLlxMRxEABYjCpRccLCCEzNnhFQhuCiRGFKhnVntq0q5JPqweatAPwkk84oCwmReErsfgSN7J5Ym03XNxrgzcLusW5Iyg39nYejkNk7tt9Il2hmM8m1GYNEddTimH5W9uCP,ecZbJe8Y23MFOt58OCqFEeahM8mB5C4PHqY7WUyOn9jeebad1nBRr4qDUskC7GLj0GVik1ngKKhhC7n5d19lssVqBSuJpVEqI3xmPe3KLmYFa4ZOjynOG8cN3ci62d3eDHmoKgcCaV5guvL7mbWQX1MIStcoDDmRsd5iZAqfY5LtbmXN5MYRMvcNfy1WXLCntxv4lCyu4wQ4tKdR9WvyXPlhtMsENTU9ivBZ21WzzaWYYlPncx6mlZ9LKbUZKY30,eKxYAkA3BNr4uNYDXlSnQqtgIciodpyjFTbwaef8lIhF2Uoqn6NIchTdZp4B7V6pQPpCVaxDfi4ZHfwgeuUcJEtDko0JUed6GbiiK2NjEpYOjL4W981iy6MIJWhz50BUtbgTC35SsBBoGVziodXETLZ6rtUVuUrRUtpYI6SrbDcP8UFc6rs68mZuHkhXaeYEIzeFk1sAZgtKltn8TA2lW2J7P2QyEMRM6TfsfW6Q1vd9xOtRnaTIfCrCXC2NaQmS,n1HwlfXGLglY4ZMavIu5scp0XUI1Pp87gTCazIIwgSiYSID8CTVX6uiBZzvTbCaFkjmwmS11dSyAvUZqzQwfvQnzAXgV25wvX7l9p0xuqBlX8rg6FeRikRAj5x8NHbF1q6VN92XWqMIunoR6ISXrAlnIYg7dRfNiA9BUGiuBFtyedUCnJPD61SbBxIgIOlcph6KJeFQqN4WhvsvpGkKW70a4OYZDZIktmmPERTJeE3Kj4V63NhExFjT8Mb842dZ8,dtWeQdvmpaWE3JOKYsMH4vnXI1S8iWR8KfaIbwnnPQuuGpCN3rkbTizHe71jAkwNlkCAJtMPaQg3P2gicaJCOZxxskFVUOUdqhq2kfxzn3n3UzQCaGO9ziFKVOKx1Kf0mpaONA5JbiX5Li8QeyahQm5on5V2yOONtLBOwrw39hB0sCyZBqOg0QfwMiV9vAgPzVfzTLtiJK2vbbQPmuiWJzvE7c2UvWzgSeCUC95RsWaG18n2QqjvodbcIlzpCFO2,VKfOLsuISIkNZbMUcmn4RhM9PWpDUT9LyI0KUk7lm2hlhRwQiZSOKJ7eGVcMFikfdF4FBW5hMnWmv5vc10W9vDCd06dKeolwVWzJdbR70yepMflo6pRQOR5diOUtZPK3JfVmQ9MlBCdHDL0C9gwcdfuaJXOG24bFRbXduEn0iNVAkgM0ghDl43IyEwi0dMsCduArdFK9LbIAMtoOkE8c5iq7XIOdwoyn1ODWczPrTYDNaF5tpnHglF0JnVhFDz3D,zMNC0sXTfVwaYbLCJaaYNjPlr72DkJl7VeSzmZnqz8o5SBnxkJAEN5YGe9UKzI1GaZQMV9QU7vvsFU6pekhnGx0PgqC7CknixhlqZp4yaPhicz934NT2QxD5TJwKkRfMMExFa4wuC8DHI9qsLWDu5y2vZl2gTTqyOlBSXC64MocoI27hg8xbxQQcN8ACGvlPUvyDChDz08p8UuhsmlmZ5GjkoWcMXXVx7B8zHiIYSzayhwjF0IeFpyAq4GiveiP3,eGaO9vmpfj7FsdGdLjJa0NkmPlGdjWm3knTrxqLkYfOl36AIz8zUswzSI7ylHwxAkqP3HeiBcQevzAInpv4YqF2nbWceGQeCHd3Pw7c0rkJGyWaSQl12iZ1kc5ho5ZOTH2yAuyyOOy77muXjPXsFCjX1fprfxUkBxJhmtYyYquPUNUp7tIwGHRpljwsOVW93n4ar4abQ7RS9SuLu54W3AqVbsOgX6VoQflxWNlnPSwIyXn5UJSDf56rDpbQeoM7V,IwYU2V7oblkwmoAngVzy4pBJSUwTCP7wHNKONGIALEDGdkgnEcVVYlvx1JXUtxRgslqEdTP7kDkCjvpp2IP0pY57qPfbS0Y3YRlNepNnxFDtUxRZwDNZL9kVJToDQkfsRjWAmApyS9KKsANfof1JccXG7hI25fWFSskhGYjCsNdDkTi7QR5L9VMJsvyAAVOKIcyuLosCFu5dXKmPKHaQZAdaRqxXQyId7QyFQChjrZNetMW8FcNbjigy4jmNXDIS,zAHFVMIQA4uLiAktxYaknTcT8GpXs2CJ7yxGCJr9KV8WaA6SHyqVNVVTbRAUog4KsbiFwi1YreiEsQu1bK7ORejWFwOq0gaMHcFVQd0aaKwD2gbYsvNqhk0XcQvCqv6XWZ8d2tpXnZ3PNDh2M4YlbMhNV2PFS80BES2VF3ezi7hPtCPJERCJp9LdXUehcncWM3sSbPtfcfyUif1zTm8fdkneoI5HRtKK4KYtxNu5yXVTKvrkJ0ILN9XmIV6sfU7c,u6YbfKbs4DexvMflN1nPgGc8jlAtMKSNebgI7S3Bt6jVi0omjNbyeu5vTtzJ8l0KTs4KMqqE4TbvYjIyeyWT7wtTYwUNG7YRVDeLIdFcmKhVwhBS4fWV3QHx9LhAqMNh7urEqe7pUO9UicFOyAuAsDCGYp4sfKJc0urXNgRpEaOUWA0zVZq2q0t3E9tjd1oveKdYrLdCEDpZaLp7a7NJjTFIwOHOj5dPiwxqPloJFCMy0y2biSHii0NGbEAeZPV5,H831nDMgFBudx2sSjvlIB9wGb3uFYjAa4XF2tTlC6e4v6yjdk3S1N47uoT8vQqCf4cnv0CCm5SNaIHQ2v4yfSv2nhFRqKHKzoTE3NY9Vf1yMGSIxyfzpa2ZjQMR4COxFTd4voJUMmNeJDNyjSR72ukkVQTsdhrCqRM0YjXXudcRZ886Zo1uCdiRGxmcd2SZAgJLznNZqlkju4VXOSgtGPvDkHwd5M22cf7SN73TEQ2jTFRnuCkp4tmUKJurjq0wS,rN2f64TZyQZIqRtXV9OHGkSZ1vjy6M7KVbyHtTyQVw9jZCTcZpiz6zJ8gkzBuox0hAJiZ4uO1626sT02l2lU5LN3AVepHOh90eLhtFzUjpRjnrCGBGwO9spcUv8hPTkLDyyFlaVsiig8Sa2xZgDNTawcILBVukWDWpcjJ6KFvX3aSV4GUprW3uaDMMI2gPm2mPv4taPwIYLgajuEDlcHxDOgQZuwu1J2S2UrVMFn8c9ykklrsOLBauVuxPcZyR7x,U1f5VAUkze3slqLVf3cXD9qxP3XiTFqQBOQGrdMUJnuJoMUqT8YguXi5Lcc6gX8voI6ZBhSOATgcUBmAONZRFZ0HZR4rlQK9Fca0hCCCfo6e63AxWrMq8AAJmqHS24L7ZzjD2ZkEAK5FupcHHjjQXyrAuzDfq0ZvL6nRfNLV88FQ9x0ZpU1divJY8KB8BuHs7wzaDz5qBKtnW7iOhxTyCGGQNKaFmFzLyClKPOSIaszeA2SU1802WaC0TpteNc9n,NJr6viQ95YR7ePlT5d9jG0XjqDRRuLXsm6AiIVC0maDrEqsX3gZywiL4engU4OPiTjZM7ZzwZwKQgtvJdWzREVenLGE8zhB8mogZJ6RKfWVD4W0B6hKroRhM5VTj7ggXLkOshngWvXtDxRQbrRVoyvvOtuL5eLTi9NNuORH02GiWV4vrOems0w2ZEKN9dq06AsvTevzys9TF5bFxdhSRo0XlWQv8TDwbjWFKxsbPFG9AiAd6fQs4kQ4qGYvj7YVE,K9IN5SpTtrBIW3AQcgV0huQK8hVsUyl7WcVfF1ZGKky7LwlKOPbZFngSRmpFP6yacGqx0AQP6dDKPdYuLcCKVXL62oP179TLEIxPji9ZAWvSjqIf3izF3gAmnisiJ9lTQ5SoGOaD3Svr70ATq0DFFElRL7cN4jJaY9sF533z5gsXEnBnvdl66DBvY2B0c1tEgAmOEmCpjhx7vtugiZMZrDE9gsQOtYe3MdbQfYqdGrxrD4JxH3qWF1eOl5N6FneY,7D4IsH1oNIkjRiioFdRrhdu1oOW8HWcCQ5a4vUkMYyVYqsZStyK8Gad0QYrnQ2xHugopHN92UG9guZ1tZ4p9n4IHU5HqukTZL2NGpNqKUiv7KmWP1gpM0MCHwoibmlJYa2D8Q8cNg5T5w6dVMq9P7k5jGrU9HlXmRlfycq9gm1li2CMFbwTfDMPOqm6Ka5ObQg5rv05DySgUQKZMyLWgC1ZY3FR5j1btjmUZFzvDxu5gxar0Co7Or5T1EsREFGQA,58co3Pab0rcUwNw6TL2HSJhnTosBaj4EbsprggKMy85uIxxNqgH6cD5xqTgzFfzC1VVmgtABBQAtBW'
2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [4, 8, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8B,CE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8B,CE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8BCE56E3,-D4A4-471D-B13E-1983A975CB39 error: max retries exceeded
2017-07-20 12:52:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9wWukSU1QUx7aJZlZWLZAEjiqNoncIKe","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:52:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9wWukSU1QUx7aJZlZWLZAEjiqNoncIKe', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:52:28 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7099301E-F445-486E-A603-9612A1AC58CE (syncValue: ntJNxl1evXVqUsSylsvbdRfrAjvu1cYk)'
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
[ThaliCore] Advertiser: session connected Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53912
2017-07-20 12:52:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ntJNxl1evXVqUsSylsvbdRfrAjvu1cYk",,"error":null,"portNumber":53912}'
2017-07-20 12:52:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ntJNxl1evXVqUsSylsvbdRfrAjvu1cYk', error: 'null', listeningPort: '53912''
Connecting to the localhost:53912
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0
Connected to the localhost:53912
2017-07-20 12:52:31 - DEBUG testThaliMob,ileNative: 'Client sends data (65536 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [4, 8, 12, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
,[ThaliCore] Session.startOutputStream(with:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [4, 8, 12, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (6641 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received (3121 bytes):'
,2017-07-20 12:52:31 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:52:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-20 12:52:32 - DEBUG testThaliMobileNative: 'Server data flus,hed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [4, 8, 12, 14]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:52:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:52:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B4121540-BB03-4856-A0E5-C0E220AE5A98
2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7099301E-F445-486E-A603-9612A1AC58CE
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53912
[ThaliCore] Session.disconnect() peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7099301E-F445-486E-A603-9612A1AC58CE:0
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.deinit peer:FFEC3634-E867-44F8-975F-DF9D3432CC9D
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B408377F-7B20-4960-9927-B47F3FDA3FDC
[ThaliCore] Browser.startListening
2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2,B,71
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FC588A3-45D2-4DE6-BDAE-579C029A9613:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FC588A3-45D2-4DE6-BDAE-579C029A9613", generation: 0)
2017-07-20 12:52:33 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1FC588A3-45D2-4DE6-BDAE-579C029A9613","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1FC588A3-45D2-4DE6-BDAE-579C029A9613","generation":0}'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}]'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}'
,2017-07-20 12:52:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilit,yChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}]'
2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}'
2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:52:34 - DEBUG thaliMobileNat,i,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71", generation: 0)
veWrapper: 'Received peerAvai,labilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"668195C4-AF2F-4CED-8392-5A206791E4AB","generation":0}]'
,2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"668195C4-AF2F-4CED-8392-5A206791E4AB","generation":0}'
,2017-07-20 12:52:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:52:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7114A0C4-6ABB-4EFC-9D9D-3,A41FEDA2B71
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:38 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-20 12:52:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:39 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FAB7B41D-0331-44EC-B15B-9D0E8A9C999F
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E929154B-05AB-4624-B8AE-58F85BD2BD1F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E929154B-05AB-4624-B8AE-58F85BD2BD1F
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E929154B-05AB-4624-B8AE-58F85BD2BD1F
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-20 12:52:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 12:52:42 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3b29b72f-0abf-4f3e-8a28-27feb3f20174 error: startListeningNotActive
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YIYHWDFyl1CWUkRi2KcItyuTaSeLqmtK","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect retur,ned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3b29b72f-0abf-4f3e-8a28-27feb3f20174","peerAvailabl,e":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer a,vailability changed event with {"peerIdentifier":"3b29b72f-0abf-4f3e-8a28-27feb3f20174","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due t,o, not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:43 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9EC2973C-CBD1-489E-A62E-433350A9A95D
[ThaliCore] Browser.startListening
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8iNZ4lbvmmDdJF272jL7cjDBOhD3YIPk","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect ,r,eturned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-20 12:52:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A5942958-3800-461F-A839-B80DE03F3CD9
[ThaliCore] Browser.startListening
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:52:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:b0b0fdd4-5f1b-4f31-ba44-c69961774d13
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:69525797-BA3F-4E13-AF0F-E86172E8CB6E
2017-07-20 12:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:47, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752
[ThaliCore] Browser.startListening
2017-07-20 12:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,ertisingActive":true}'
2017-07-20 12:52:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"ro,uter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
2017-07-20 12:52:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9749BEAA-3E3A-45D7-9075-645C99E7D51C","generation":0}'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9749BEAA-3E3A-45D7-9075-645C99E7D51C, (syncValue: UGDkrmaTu2oZaGjFUvGHp7pTznYIuEFH)'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E,7D51C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","generation":0}'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:48 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:53920
2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UGDkrmaTu2oZaGjFUvGHp7pTznYIuEFH",,"error":null,"portNumber":53920}'
2017-07-20 12:52:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UGDkrmaTu2oZaGjFUvGHp7pTznYIuEFH', error: 'null', listeningPort: '53920''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
ok 143 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) found active relay
,2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"h890uAHUHdu3EEmPkNLDFhUFYd1qNGbH","error":null,"portNumber":53920}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0) found active relay
,2017-07-20 12:52:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eLAQDfHV5SRf2V0z5XapBEWWcctmLU9g","error":null,"portNumber":53920}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [4, 8, 12, 14, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1136B49E-97B2-4E22-AC90-4A914404E861
[ThaliCore] Advertiser: session connected Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1136B49E-97B2-4E22-AC90-4A914404E861 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1136B49E-97B2-4E22-AC90-4A914404E861
,[ThaliCore] Session.session(_:peer:didChange:) peer:1136B49E-97B2-4E22-AC90-4A914404E861 state: connecting -> connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:16 [4, 8, 12, 14]
,2017-07-20 12:52:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:69525797-BA3F-4E13-AF0F-E86172E8CB6E
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:53920
[ThaliCore] Session.disconnect() peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1136B49E-97B2-4E22-AC90-4A914404E861
[ThaliCore] Session.startOutputStream(with:) peer:1136B49E-97B2-4E22-AC90-4A914404E861
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [4, 8, 12, 14, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [4, 8, 12, 14]
,[ThaliCore] Session.session(_:peer:didChange:) peer:1136B49E-97B2-4E22-AC90-4A914404E861 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1136B49E-97B2-4E22-AC90-4A914404E861
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:1136B49E-97B2-4E22-AC90-4A914404E861
,# initial peer discovery
,2017-07-20 12:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-20 12:53:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-20 12:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 53924'
ok 149 Should throw
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 53926'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 53929'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 53933'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 53938'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 53942'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 53946'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 53950'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'listening 53954'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-20 12:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2, - 1 - closed'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 12:53:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54006'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54010'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'listening 54013'
ok 196 port must be in range
,# teardown
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54014'
ok 197 second start should return same port
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54016'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-20 12:53:09 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 200 Passed bogus id
2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
ok 201 Passed good id but bogus port
2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
ok 205 Ret,ry should be false
ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 54018
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDC6342C-BEC8-4018-A009-92C5CCA,D5617
[ThaliCore] Browser.startListening
2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","generation":0}'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7EACCE85-5177-40E5-B094-99AE50B25DB4 (syncValue: 08PA6bHDHaxLG8tEweJmjxBqL1XrQ11B)'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
2017-07-20 12:53:11 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","generation":0}'
2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,ACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,ACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170
[ThaliCore] Advertiser: session connected Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:13134C84-C172-40B2-A179-A5442E4B59D5
[ThaliCore] Advertiser: session connected Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7EACCE85,-5177-40E5-B094-99AE50B25DB4 error: max retries exceeded
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"08PA6bHDHaxLG8tEweJmjxBqL1XrQ11B","error":"Connection could not be established","portNumber":null}'
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '08PA6bHDHaxLG8tEweJmjxBqL1XrQ11B', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA32759D-73B0-4139-BC54-9CBBA9318A85 (syncValue: Z8MVyW0Y6NY8Bcbbz5ifuE5mQQi4f3Ig)'
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:13134C84-C172-40B2-A179-A5442E4B59D5
,[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54032
2017-07-20 12:53:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z8MVyW0Y6NY8Bcbbz5ifuE5mQQi4f3Ig",,"error":null,"portNumber":54032}'
2017-07-20 12:53:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z8MVyW0Y6NY8Bcbbz5ifuE5mQQi4f3Ig', error: 'null', listeningPort: '54032''
,ok 210 should be equal
,2017-07-20 12:53:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35100B8F-5608-4D74-85AC-379CF9FF5614 (syncValue: Op6Hb4ZdNWBI1k0dYXWRjiIzintjiFJk)'
,2017-07-20 12:53:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54036
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Op6Hb4ZdNWBI1k0dYXWRjiIzintjiFJk",,"error":null,"portNumber":54036}'
2017-07-20 12:53:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Op6Hb4ZdNWBI1k0dYXWRjiIzintjiFJk', error: 'null', listeningPort: '54036''
,ok 211 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:53:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E6222F0B-BC09-4C60-88EE-3,F2C1C1244C7
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:EA32759D-73B0-4139-BC54-9CBBA9318A85
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54032
[ThaliCore] Session.disconnect() peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:13134C84-C172-40B2-A179-A5442E4B59D5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:13134C84-C172-40B2-A179-A5442E4B59D5
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:35100B8F-5608-4D74-85AC-379CF9FF5614
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54036
[ThaliCore] Session.disconnect() p,eer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:13134C84-C172-40B2-A179-A5442E4B59D5
,# Multiple local http requests
,listening on 54038
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:88535592-00DC-406A-B6E1-682309662B75
2017-07-20 1,2:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
[Tha,l,iCore] Browser.startListening
2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","generation":0}'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 35100B8F-5608-4D74-85AC-379CF9FF5614 (syncValue: YXY7VjuRUiFAxE97qO3ETpnlslE9XSTR)'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","generation":0}'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
2017-07-20 12:53:30 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88535592-00DC-406A-B6E1-682309662B75:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:53:30 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:35,100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,5100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6
[ThaliCore] Advertiser: session connected Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: notConnected -> connecting
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YXY7VjuRUiFAxE97qO3ETpnlslE9XSTR","error":"Peer is unavailable","portNumber":null}'
2017-07-20 12:53:32 - DEBUG thaliMobileNative,TestUtils: 'Got multiConnectResolved -syncValue: 'YXY7VjuRUiFAxE97qO3ETpnlslE9XSTR', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":,"35100B8F-5608-4D74-85AC-379CF9FF5614","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"35100B8F-5608-4D74-85AC-379CF9FF5614","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:53:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA32759D-73B0-4139-BC54-9CBBA9318A85 (syncValue: pHikQzzwq4iElH0BvhF9ib9ejhOaOVun)'
,2017-07-20 12:53:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pHikQzzwq4iElH0BvhF9ib9ejhOaOVun","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pHikQzzwq4iElH0BvhF9ib9ejhOaOVun', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1F70EEB-FC68-4F13-8138-43E08E22C687 (syncValue: MV9ZsIgv3IT04YRDrvCkENt,HXq9XvxNj)'
2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D1F70EEB-FC68-4F13-8138-43E08,E22C687:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-20 12:53:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54052
2017-07-20 12:53:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MV9ZsIgv3IT04YRDrvCkENtHXq9XvxNj",,"error":null,"portNumber":54052}'
2017-07-20 12:53:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MV9ZsIgv3IT04YRDrvCkENtHXq9XvxNj', error: 'null', listeningPort: '54052''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-20 12:53:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2AD1575A-57BF-49EF-A14E-3BCF4FE28514 (syncValue: xZ1ZkDuBgaa5O1XQQ630CtF4UcBv6ZL2)'
2017-07-20 12:53:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
[ThaliCore] Browser.i,nviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
[ThaliCore] Advertiser: session connected Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54058
2017-07-20 12:53:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xZ1ZkDuBgaa5O1XQQ630CtF4UcBv6ZL2",,"error":null,"portNumber":54058}'
2017-07-20 12:53:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xZ1ZkDuBgaa5O1XQQ630CtF4UcBv6ZL2', error: 'null', listeningPort: '54058''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
,[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:88535592-00DC-406A-B6E1-6,82309662B75
2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D1F70EEB-FC68-4F13-8138-43E08E22C687
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54052
[ThaliCore] Session.disconnect() peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54058
,[ThaliCore] Session.disconnect() peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,[ThaliCore] Session.deinit peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
[ThaliCore] Session.deinit peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'listening 54062'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 54063'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25F428D4-1BA6-4445-B778-8DB00CE7C840
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 54065'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "99A35391-9BD6-48CB-B0BA-1665CFC37DF4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:99A35391-9BD6-48CB-B0BA-1665CFC37DF4
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "99A35391-9BD6-48CB-B0BA-1665CFC37DF4", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:99A35391-9BD6-48CB-B0BA-1665CFC37DF4
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:99A35391-9BD6-48CB-B0BA-1665CFC37DF4
[ThaliCore] Advertiser.stopAdvertising() peerID:99A35391-9BD6-48CB-B0BA-1665CFC37DF4
2017-07-20 12:53:48 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 235 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method disco,v,eryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'listening 54068'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:49 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-20 12:53:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 54069'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C38A06A0-0624-4182-A344-6E35A776D245
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5FA3B61-45F6-4459-9922-47C35DC15C55", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,D5FA3B61-45F6-4459-9922-47C35DC15C55
2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:51 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D5FA3B61-45F6-4459-9922-47C35DC15C55
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 54072'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0DD7F99C-4A28-4EAA-B4CC-C3F1607B99D1
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EB2AEEEF-D1D8-4464-8558-7096346E4194", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,EB2AEEEF-D1D8-4464-8558-7096346E4194
2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:51 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}]'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EB2AEEEF-D1D8-4464-8558-7096346E4194
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'listening 54074'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6BCFA88A-E867-492A-95DB-69AF09397B3D
[ThaliCore] Browser.startListening
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F71C3C7B-099C-4394-8E3C-6E55F4D7C895", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,F71C3C7B-099C-4394-8E3C-6E55F4D7C895
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:52 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F71C3C7B-099C-4394-8E3C-6E55F4D7C895
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrap,per: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"lis,t,ening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-20 12:53:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:52 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 12:53:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:53 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 12:53:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-20 12:53:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-20 12:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 12:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54077'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38C610FD-3929-4D7B-A888-9F02CE5252CB
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54078'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "655D400F-80FD-427E-B444-4D921DD1DFB9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:655D400F-80FD-427E-B444-4D921DD1DFB9
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:655D400F-80FD-427E-B444-4D921DD1DFB9
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54080'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'listening 54081'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8445DA00-C370-41B1-8E09-C330211D7070
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F97DFB70-CDE1-436C-9362-16B2022559F6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F97DFB70-CDE1-436C-9362-16B2022559F6
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:54:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
ok 277 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F97DFB70-CDE1-436C-9362-16B2022559F6
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-20 12:54:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-20 12:54:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'listening 54083'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:173A8E1A-8B33-4704-86E4-A6BCD393D858
[ThaliCore] Browser.startListening
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ADB21495-5A54-49DC-88F8-51FC343DC59F
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:54:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2AD1575A-57BF-49EF-A14E-3BCF4FE28514 (syncValue: IZThsemi7OUDNQ644FlYevTpDM04fqC3)'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
[ThaliCore] Advertiser: session connected Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:236824DA-F1E1-4D80-B7AF-2C19AE7BC695:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "236824DA-F1E1-4D80-B7AF-2C19AE7BC695", generation: 0)
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
,[ThaliCore] Session.session(_:peer:didChange:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
[ThaliCore] Session.startOutputStream(with:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [4, 8, 12, 14, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,D1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:54:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IZThsemi7OUDNQ644FlYevTpDM04fqC3","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:54:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IZThsemi7OUDNQ644FlYevTpDM04fqC3', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:54:06 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:54:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:54:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-20 12:54:06 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:54:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514
2017-07-20 12:54:06 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-20 12:54:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22488835-A637-4241-BF70-B8FAAEA6FBCB (syncValue: qsoQggw4jiozNrxjBHuUCfOBfnlp2UcU)'
2017-07-20 12:54:06 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:s,essionNotConnected:) Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] BrowserRelay.init(session:generation:creat,eVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54090
2017-07-20 12:54:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qsoQggw4jiozNrxjBHuUCfOBfnlp2UcU",,"error":null,"portNumber":54090}'
2017-07-20 12:54:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qsoQggw4jiozNrxjBHuUCfOBfnlp2UcU', error: 'null', listeningPort: '54090''
,2017-07-20 12:54:08 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [4, 8, 12, 14, 18, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler,
,2017-07-20 12:54:09 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:09 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:ADB21495-5A54-49DC-88F8-51FC343DC59F
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-20 12:54:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertis,ingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserManager.disconnect peer:22488835-A637-4241-BF70-B8FAAEA6FBCB
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54090
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listeni,ng socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Ad,vertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [4, 8, 12, 14, 19]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] Session.disconnect() peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:dis,connecting
,[ThaliCore] Session.deinit peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] VirtualSocket.deinit vsID:19 [4, 8, 12, 14]
[ThaliCore] TCPListener.deinit
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:85F39250-2FED-41F9-B0C4-DCB5E27F5FD1
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-20 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 12:54:12 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"236824DA-F1E1-4D80-B7AF-2C19AE7BC695","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'listening 54092'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'listening 54093'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26873F30-8887-4421-BEB5-644BB42B72A8
[ThaliCore] Browser.st,artListening
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'listening 54094'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00107B49-3B61-4F5B-8791-B1BEAD7833E1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:00107B49-3B61-4F5B-8791-B1BEAD7833E1
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00107B49-3B61-4F5B-8791-B1BEAD7833E1", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:00107B49-3B61-4F5B-8791-B1BEAD7833E1
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 315 error should be null
,ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00107B49-3B61-4F5B-8791-B1BEAD7833E1
[ThaliCore] Advertiser.stopAdvertising() peerID:00107B49-3B61-4F5B-8791-B1BEAD7833E1
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'listening 54097'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 320 error should be null
ok 321 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,ve":false}'
,ok 322 error should be null
ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-20 12:54:15 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
ok 328 native router should be bad
,# teardown
,ok 329 error should be null
ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'listening 54098'
ok 332 first call should succeed
ok 333 first call should succeed
ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b1b3610-1c80-49f1-89de-17fa4fb04756","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be called once
ok 345 should not have been called more than once
,# teardown
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7b1b3610-1c80-49f1-89de-17fa4fb04756","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
,2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6a4a9589-9f34-45bc-9108-af5e6d99ff37","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 354 peer should be ,available
ok 355 cache contains native peer
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6a4a9589-9f34-45bc-9108-af5e6d99ff37","connectionType":"MPCF","peerAvailable":false,"generation":0,",newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
,2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5edc8dff-c234-4f37-9b92-c04a75251519","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 362 peer should be a,vailable
ok 363 cache contains wifi peer
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5edc8dff-c234-4f37-9b92-c04a75251519","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 364 peer should be unavailable
ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"995829f6-82f4-450e-af69-53c2bfa3cf43","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5b8b54a9-50e9-49c2-b065-8f63dff76aff","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 370 second peer is available
ok 371 first and second peers are different
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"995829f6-82f4-450e-af69-53c2bfa3cf43","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5b8b54a9-50e9-49c2-b065-8f63dff76aff","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3db66e71-9361-4e92-a6ee-2b51155ec6cc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 376 peer is availab,le
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3db66e71-9361-4e92-a6ee-2b51155ec6cc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-20 12:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-20 12:54:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"02b7a6cc-430b-49e8-acb0-ee365d812887","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 386 peer should be available
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"02b7a6cc-430b-49e8-acb0-ee365d812887","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 387 peer should be available
,ok 388 should store correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"02b7a6cc-430b-49e8-acb0-ee365d812887","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 54099'
2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"41bbbebe-3af6-4cb6-ba6b-c39d20050509","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"41bbbebe-3af6-4cb6-ba6b-c39d20050509","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 394 discovered correct peer
ok 395 got correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"41bbbebe-3af6-4cb6-ba6b-c39d20050509","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 54100'
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c3508e61-2697-4d4c-a70a-bce6e2fbb492","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c3508e61-2697-4d4c-a70a-bce6e2fbb492","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4568fe4f-e204-493b-80cb-e4985d0e622f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4568fe4f-e204-493b-80cb-e4985d0e622f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 405 peer should be unavailable
ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 54101'
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2cc4434-d7cb-4ea3-86a4-8df9de5f01c0","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"413efa7a-afcd-4582-90b3-2a0092519dd8","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"413efa7a-afcd-,4582-90b3-2a0092519dd8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 412 peer became unavailable
,ok 413 it was wifi peer
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"413efa7a-afcd-4582-90b3-2a0092519dd8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 414 we found peer again
ok 415 it was wifi peer
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"413efa7a-afcd-4582-90b3-2a0092519dd8","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,# teardown
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a2cc4434-d7cb-4ea3-86a4-8df9de5f01c0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-20 12:54:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 54102'
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3f7f1de3-b288-423b-8b13-673cd47b37e5","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 424 first peer is expected to be available
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"659d7f35-72a8-48e1-ac44-91d00f8c67ad","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 425 second peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3f7f1de3-b288-423b-8b13-673cd47b37e5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 426 pee,r became unavailable
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"659d7f35-72a8-48e1-ac44-91d00f8c67ad","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 428 error should be null
ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a715918-ebc6-4058-91f0-5c46fffdb95a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 peer discovered first time does not have new address
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a715918-ebc6-4058-91f0-5c46fffdb95a","connectionType":"tcp","peerAvailable":true,"ge,neration":20,"newAddressPort":false}'
ok 438 address has not been changed
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a715918-ebc6-4058-91f0-5c46fffdb95a","connectionType":"tcp","peerAvai,lable":true,"generation":20,"newAddressPort":true}'
ok 439 new port handled correctly
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a715918-ebc6-4058-91f0-5c46fffdb95a","connectionType":"tc,p","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled correctly
2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2a715918-ebc6-4058-91f0-5c46fffdb95a","connec,t,ionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 newAddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
ok 453 error should be null
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
,2017-07-20 12:54:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
ok 469 the same hostAddress
ok 470 the same portNumber
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 54103'
2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ac522d9b-8964-48e0-aa17-976fb201a92e","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 474 Got specific error message
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ac522d9b-8964-48e0-aa17-976fb201a92e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 54104'
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7c022a42-d5ff-4622-a009-4aee69f55f76","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:7c022a42-d5ff-4622-a009-4aee69f55f76
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7c022a42-d5ff-4622-a009-4aee69f55f76","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
,ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 54105'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A3AD7E74-E962-47B2-9A12-4C7A0E9AD4D0
[ThaliCore] Browser.startListening
2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"affe659c-f505-42e0-932e-2b576a22d78b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"51075a53-8281-4179-9874-bbd47eba89a5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"affe659c-f505-42e0-932e-2b576a22d78b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"51075a53-8281-4179-9874-bbd47eba89a5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'listening 54106'
2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eaa6e4bb-f85c-4b75-bfc7-65fc5c41fc9f","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c6f6220b-7f48-40e3-adce-ed1a7711acb1","connectionType":"MPCF","peerAvailabl,e":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"eaa6e4bb-f85c-4b75-bfc7-65fc5c41fc9f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c6f6220b-7f48-40e3-adce-ed1a7711acb1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 12:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
,ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'listening 54107'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C355728-450D-4AE9-898C-AC65C78ACABC
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] Browser.startListening
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
2017-07-20 12:54:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","generation":0}]'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","generation":0}'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:54:29 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 90045F83-13E2-42E6-8B7E-9138CCA74D8C (syncValue: 0)'
2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "90045F83-13E2-42E6,-8B7E-9138CCA74D8C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:,notConnected:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
[ThaliCore] Advertiser: session connected Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] Advertiser: session connected Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
,2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","generation":0}]'
,2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","generation":0}'
,2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport,:54110
2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":54110}'
,2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 56CC6A57-6C82-4856-8C19-30E36C8EC7B7 (syncValue: 1)'
,2017-07-20 12:54:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [4, 8, 12, 14, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:32 - DEBUG testUtils: 'Got response data'
2017-07-20 12:54:32 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
[ThaliCore] Session.startOutputStream(with:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [4, 8, 12, 14, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] Session.startOutputStream(with:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [4, 8, 12, 14, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54116
2017-07-20 12:54:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":54116,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [4, 8, 12, 14, 20, 21, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:35 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:35 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,2017-07-20 12:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"90045F83-13E2-42E6-8B7E-9138CCA74D8C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0C355728-450D-4AE9-898C-AC65C78ACABC
2017-07-20 12:54:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-20 12:54:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 12,:,54:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:54:36 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:36 - DEBUG makeIntoCloseAllServer: 'clo,seAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote, peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliC,ore] VirtualSocket.closeStreams() vsID:21
ok 527 error should be null
,ok 528 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,# setup
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [4, 8, 12, 14, 20, 22, 23]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [4, 8, 12, 14, 20, 23]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:23 [4, 8, 12, 14, 20]
,[ThaliCore] Session.session(_:peer:didChange:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
,[ThaliCore] Session.deinit peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [4, 8, 12, 14]
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 12:54:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
,ok 533 getConnectionType
,ok 534 getActionType
,ok 535 getActionState
ok 536 getPskIdentity
ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
,ok 546 agent's destroy should be called
,ok 547 agent's destroy should not be called again
ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
ok 550 Entry exists
ok 551 Size must be 1
ok 552 Entry counter must be 2
ok 553 Entry exists
ok 554 Size must be 2
ok 555 Entry counter must be 1
ok 556 Entry exists
ok 557 Size must be 3
ok 558 Entry counter must be, 2
ok 559 Entry exists
ok 560 Size must be 4
ok 561 Entry 1_1 should not be found
ok 562 Entry 1_1 does not exist
ok 563 Size must be 3
ok 564 Entry 1_2 should not be found
ok 565 Entry 1_2 does not exist
ok 566 Size must be 2
ok 567 should be equal
ok 568 Entry 2_1 should not be found
ok 569 Entry 2_2 should not be found
ok 570 Entry 2_1 does not exist
ok 571 Entry 2_2 does not exist
ok 572 Size must be 0
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
,ok 577 Size should be MAXSIZE
ok 578 Size should be MAXSIZE+6
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
ok 586 enqueue is fine
ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
,ok 589 first enqueue is fine
,ok 590 is an agent
,ok 591 second enqueue is fine
,ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
ok 595 good enqueue
,ok 596 Identity should match
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-20 12:54:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
,ok 600 enqueue worked
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
,ok 609 good enqueue
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
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
,ok 617 2nd good enqueue
ok 618 we are in the pool
ok 619 We are out of the pool
ok 620 Action was killed
ok 621 The original kill was called too
ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
ok 624 first kill
ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
ok 627 2nd good enqueue
,ok 628 1st action is in the pool
ok 629 2nd action is in the pool
ok 630 1st action is out of the pool
ok 631 2st action is out of the pool
ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 12:54:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 636 Got right error
ok 637 Start should not be called
ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 640 is an agent
2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 642 Got Null
ok 643 Got another null
2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 645 is an agent
2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication, response with no error!'
ok 649 should have gotten null
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activit,y time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startErr,or: eeeek! - failureButNotAvailable'
ok 651 Still looking for null
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2017-07-20 12:,54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with n,o error!'
ok 652 Yup, another null
ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 656 is an agent
,ok 657 Null 3
,ok 658 Replication not yet called
,ok 659 Notification 2 not yet called
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtAT,ime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
ok ,671 first ok
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
ok 673 second ok
ok 674 third ok
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2017-07-20 12:54:52 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-20 12:54:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-20 12:54:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-20 12:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-20 12:54:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-20 12:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
ok 686 correct error message
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 689 must return null after successful call.
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-20 12:54:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
,ok 695 must return null after successful kill
,# teardown
,2017-07-20 12:54:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-20 12:55:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 12:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-20 12:55:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 709 should be equal
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
,2017-07-20 12:55:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
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
ok 724 good beacon
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
ok 730 secrets match
,ok 731 We have an entry!
ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
ok 735 keys match
,ok 736 secrets match
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
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
,2017-07-20 12:55:15 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-20 12:55:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-20 12:55:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-20 12:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-20 12:55:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-20 12:55:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-20 12:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
,ok 771 peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-20 12:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-20 12:55:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-20 12:55:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-20 12:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-20 12:55:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-20 12:55:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
ok 805 should be 204
# teardown
,2017-07-20 12:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
# teardown
,2017-07-20 12:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
ok 808 not equal connection type
ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 12:55:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
ok 814 first action kill called
ok 815 second action kill called
ok 816 first cleared dictionary
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
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-20 12:55:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-20 12:55:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-20 12:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-20 12:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 848 right error
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-20 12:55:44 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:44 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-20 12:55:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 12:55:49 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:49 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:52 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-20 12:55:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 12:55:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-20 12:55:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 12:55:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:57 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-20 12:55:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:55:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-07-20 12:56:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-20 12:56:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 12:56:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 12:56:03 - DEBUG thaliMobileNativeWrapper: 'listening 54243'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Browser.startListening
,2017-07-20 12:56:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:96241CD7-C019-4F98-A006-9D7C1BEFED19
,2017-07-20 12:56:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Advertiser: session connected Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Advertiser: session connected Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
2017-07-20 12:56:04 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","generation":0}]'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","generation":0}'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:56:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22BF9314-137A-449F-AF79-3F7901B86A34","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 22BF9314-137A-449F-AF79-3F7901B86A34 (syncValue: 2)'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","generation":0}]'
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","generation":0}'
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:56:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] Session.session(_:peer:didChange:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [4, 8, 12, 14, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [4, 8, 12, 14, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54248
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":54248}'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 39C4BF82-C564-4703-A987-5D9BD291B6A0 (syncValue: 3)'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [4, 8, 12, 14, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,7 [4, 8, 12, 14, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vs,ID:24 [4, 8, 12, 14, 25, 26, 27]
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [4, 8, 12, 14, 26, 27]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [4, 8, 12, 14, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [4, 8, 12, 14, 26, 27, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [4, 8, 12, 14, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-20 12:56:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-20 12:56:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 39, 40, 42]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:39 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 38, 40, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Th,aliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Session.startOutputStream(with:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:44 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 42, 45]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil,
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:42 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 45]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:56:10 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:56:10 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54271
2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":54271,}'
,2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2AD1575A-57BF-49EF-A14E-3BCF4FE28514 (syncValue: 4)'
2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 46, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [4, 8, 12, 14, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 37, 40, 46, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [4, 8, 12, 14, 26, 27, 28, 30, 31, 32, 33, 34, 35, 37, 40, 46, 48, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [4, 8, 12, 14, 26, 27, 28, 30, 32, 33, 34, 35, 37, 40, 46, 48, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [4, 8, 12, 14, 26, 27, 28, 30, 32, 33, 35, 37, 40, 46, 48, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [4, 8, 12, 14, 26, 27, 28, 30, 32, 33, 35, 40, 46, 48, 49]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [4, 8, 12, 14, 26, 28, 30, 32, 33, 35, 40, 46, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [4, 8, 12, 14, 26, 28, 32, 33, 35, 40, 46, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [4, 8, 12, 14, 26, 28, 32, 35, 40, 46, 48, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:40 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50, 51, 52]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50, 52]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClie,nt.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [4, 8, 12, 14, 26, 28, 32, 35, 46, 48, 49, 50, 53]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,28
[ThaliCore] VirtualSocket.deinit vsID:28 [4, 8, 12, 14, 26, 32, 35, 46, 48, 49, 50, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,32
[ThaliCore] VirtualSocket.deinit vsID:32 [4, 8, 12, 14, 26, 35, 46, 48, 49, 50, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnect,ed
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,35
[ThaliCore] VirtualSocket.deinit vsID:35 [4, 8, 12, 14, 26, 46, 48, 49, 50, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStream,sHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [4, 8, 12, 14, 26, 48, 49, 50, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Tha,l,iCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,D1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A,D1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
2017-07-20 12:56:14 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}]'
2017-07-20 12:56:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","generation":0}'
,2017-07-20 12:56:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-20 12:56:14 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 12:56:14 - WARN thaliNotificationClient: 'peer is not avai,lable'
,2017-07-20 12:56:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:56:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] TCPListener.socketDidDi,s,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:48 [4, 8, 12, 14, 26, 49, 50, 53]
[ThaliCore] BrowserRelay.didSocke,tDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] VirtualSocket.deinit vsID:49 [4, 8, 12, 14, 26, 50, 53]
[ThaliCore] VirtualSocket.deinit vsID:5,0 [4, 8, 12, 14, 26, 53]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [4, 8, 12, 14, 26]
,[ThaliCore] Session.session(_:peer:didChange:) peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2A,D1575A-57BF-49EF-A14E-3BCF4FE28514:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2A,D1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":"Peer is unavailable","portNumber":null}'
2017-07-20 12:56:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:56:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:56:15 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
2017-07-20 12:56:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":false,"gener,ation":null,"portNumber":null,"recreated":true}'
2017-07-20 12:56:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2AD1575A-57BF-49EF-A14E-3BCF4FE28514","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514
,[ThaliCore] Session.deinit peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:59:03 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-20 12:59:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4,D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4,D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4,D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-20 13:06:03 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-20 13:06:03 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-20 13:,06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-20 13:06:03 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-20 ,1,3:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-20 13:06:03 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 13:06:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
# teardown
,2017-07-20 13:06:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4,D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1,A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/98688D2F-F9FA-4D1A-BC67-23144EE5FE74/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
