#### Test 113351851e5b8da0_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/AC85C64D-056E-4373-98D8-1AA8BFCBA688/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/AC85C64D-056E-4373-98D8-1AA8BFCBA688/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50580"
,(lldb)     command script import "/tmp/AC85C64D-056E-4373-98D8-1AA8BFCBA688/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:26:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2F3D43E6-CCFB-4FF1-B086-AFB81620D141", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2F3D43E6-CCFB-4FF1-B086-AFB81620D141
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F39A346E-484C-459F-B90C-8C0410F42D87
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:1011A93B-4BEA-41F8-AF40-1AE112D964C4
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-13 09:26:38 - DEBUG UnitTest_app: 'Running unit te,sts'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.297897934913635
2017-07-13 09:26:38 - DEBUG UnitTest_app: 'My device name is:, 'Apple-Iphone6sPlus-1''
2017-07-13 09:26:38 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DA92EF70-81B7-4FA8-9ED4-3A9B9FC5B39A", generation: 0)
,2017-07-13 09:26:40 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 09:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 09:26:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 09:26:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 09:26:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 09:26:42 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 09:26:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:26:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:26:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:26:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:26:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:26:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:26:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:27:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:27:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:21 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 09:29:21 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 09:29:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 09:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 09:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 09:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-13 09:29:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-13 09:29:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 09:29:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 09:29:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
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
,2017-07-13 09:29:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 09:29:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 09:29:34 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-13 09:29:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 09:29:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D026806A-F577-400A-ABB5-B8D76613A04F
[ThaliCore] Browser.startListening
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:58E054AC-30F2-43A7-A48C-0F55F3096E5E
[ThaliCore] Browser.startListening
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:43 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DABCC1F7-18C2-422A-9A2E-8BE942296D8B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DABCC1F7-18C2-422A-9A2E-8BE942296D8B
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discovery,AdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE794819-51C7-4DAE-9507-A7719FD7F702", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EE794819-51C7-4DAE-9507-A7719FD7F702
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE794819-51C7-4DAE-9507-A7719FD7F702", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:EE794819-51C7-4DAE-9507-A7719FD7F702
2017-07-13 0,9:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:2,9:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdv,ertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:46 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:46 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3893778D-A108-4402-9972-01688608596C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3893778D-A108-4402-9972-01688608596C
,2017-07-13 09:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69B26747-542A-4920-8B78-2D84517C7,0F2
[ThaliCore] Browser.startListening
2017-07-13 09:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:29:47 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:70431CAA-E8FA-425D-A5B4-088C35618AEB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "70431CAA-E8FA-425D-A5B4-088C35618AEB", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8CA63532-F679-4683-AE6B-8D8E453DB975:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8CA63532-F679-4683-AE6B-8D8E453DB975", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3893778D-A108-4402-9972-01688608596C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3893778D-A108-4402-9972-01688608596C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:29:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,09:29:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 09:29:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:29:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:001FF42C-B081-4001-A9F2-6BB3561908F9
2017-07-13 0,9:29:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53
[Thal,i,Core] Browser.startListening
2017-07-13 09:29:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:29:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:55 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
2017-07-13 09:29:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DEB213F8-7240-427B-A28E-AEECE8ABFAF9","generation":0}'
2017-07-13 09:29:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DEB213F8-7240-427B-A28E-AEECE8ABFAF9, (syncValue: yMNNXkgOPVsBN84xtQnDs7ydH1MnvBaQ)'
2017-07-13 09:29:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEB213F8-7240-4,27B-A28E-AEECE8ABFAF9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620
[ThaliCore] Advertiser: session connected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620
,[ThaliCore] Session.session(_:peer:didChange:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49579
2017-07-13 09:29:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yMNNXkgOPVsBN84xtQnDs7ydH1MnvBaQ","error":null,"portN,umber":49579}'
2017-07-13 09:29:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yMNNXkgOPVsBN84xtQnDs7ydH1MnvBaQ', error: 'null', listeningPort: '49579''
,2017-07-13 09:29:59 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1976180A-C610-46F2-A8BD-B82D54205B98
[ThaliCore] Advertiser: session connected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1976180A-C610-46F2-A8BD-B82D54205B98 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCA5C49A-1B68-480D-9939-27D9A9088049:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCA5C49A-1B68-480D-9939-27D9A9088049", generation: 0)
2017-07-13 09:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BCA5C49A-1B68-480D-9939-27D9A9088049","generation":0}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1976180A-C610-46F2-A8BD-B82D54205B98
,[ThaliCore] Session.session(_:peer:didChange:) peer:1976180A-C610-46F2-A8BD-B82D54205B98 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:1976180A-C610-46F2-A8BD-B82D54205B98 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1976180A-C610-46F2-A8BD-B82D54205B98
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:1976180A-C610-46F2-A8BD-B82D54205B98
,2017-07-13 09:30:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:30:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49579
[ThaliCore] Session.disconnect() peer:DEB213F8,-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7013A18A-B3A3-429C-A561-7CE2E3F66643
2017-07-13 0,9:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
[Tha,l,iCore] Browser.startListening
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DEB213F8-7240-427B-A28E-AEECE8ABFAF9","generation":0}'
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DEB213F8-7240-427B-A28E-AEECE8ABFAF9 (syncValue: aBOW1YYh4tAadLOGFY4wU2wqlskfvkOA)'
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
2017-07-13 09:30:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", genera,tion: 0)
2017-07-13 09:30:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aBOW1YYh4tAadLOGFY4wU2wqlskfvkOA","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:13 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'aBOW1YYh4tAadLOGFY4wU2wqlskfvkOA', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"DEB213F8-7240-427B-A28E-AEECE8ABFAF9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 09:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DEB213F8-7240-427B-A28E-AEECE8ABFAF9","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:13 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C (syncValue: iRJJzaaJRwjdPWVvVMu1jdzRob4uNwcu)'
,2017-07-13 09:30:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D
[ThaliCore] Advertiser: session connected Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
[ThaliCore] Advertiser: session connected Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D
,[ThaliCore] Session.session(_:peer:didChange:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D
[ThaliCore] Session.startOutputStream(with:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
[ThaliCore] Session.startOutputStream(with:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49587
2017-07-13 09:30:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iRJJzaaJRwjdPWVvVMu1jdzRob4uNwcu",,"error":null,"portNumber":49587}'
2017-07-13 09:30:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iRJJzaaJRwjdPWVvVMu1jdzRob4uNwcu', error: 'null', listeningPort: '49587''
,Connecting to the localhost:49587
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
Connected to the localh,ost:49587
2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 []
,# teardown
,2017-07-13 09:30:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-13 09:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:59CCC3C4-7D77-,4AA0-85BA-EAC4EC5EC63C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49587
[ThaliCore] Session.disconnect() peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: ",59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
[ThaliCore] Session.session(_:peer:didChange:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:272EFB28-A62E-4CC9-815C-88B09C2FD833
2017-07-13 0,9:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[Tha,l,iCore] Browser.startListening
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","generation":0}'
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C, (syncValue: T3pE40mOXTSRaz6gPOg6oq31cfZEyoYf)'
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59CCC3C4-7D77-,4,AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
2017-07-13 09:30:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Session.disconnect() peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", genera,tion: 0)
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T3pE40mOXTSRaz6gPOg6oq31cfZEyoYf","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'T3pE40mOXTSRaz6gPOg6oq31cfZEyoYf', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59B86F41-C2BA-43DD-9AE3-8F3EAE11736F (syncValue: JmBDcrC,hhl7D2r065SpjqaNQxZgwVi6W)'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] Session.disconnect() peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", genera,tion: 0)
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JmBDcrChhl7D2r065SpjqaNQxZgwVi6W","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'JmBDcrChhl7D2r065SpjqaNQxZgwVi6W', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C (syncValue: zJt7oft,z6rhT0SaJrx1PpvfOhhGom7Te)'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Advertiser: session connected Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49598
,2017-07-13 09:30:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zJt7oftz6rhT0SaJrx1PpvfOhhGom7Te","error":null,"portNumber":49598}'
,2017-07-13 09:30:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zJt7oftz6rhT0SaJrx1PpvfOhhGom7Te', error: 'null', listeningPort: '49598''
,Connecting to the localhost:49598
,Connecting to the localhost:49598
Connecting to the localhost:49598
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,Connected to the localhost:49598
,Connected to the localhost:49598
,Connected to the localhost:49598
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [5]
,ok 114 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Session.startOutputStream(with:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Session.startOutputStream(with:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [5, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Session.startOutputStream(with:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [5, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (14194 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [5, 8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [5, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (14194 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 []
,2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49598
,[ThaliCore] Session.disconnect() peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForA,dvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
[ThaliCore] Browser.startListening
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","st,artArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
2017-07-13 09:30:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","generation":0}'
2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0F6381F-42C6-44BA-8B84-8E89DDF7C407, (syncValue: BwTDYUy7yaDiFSHyuVcUjulDaTZQBiiu)'
2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0F6381F-42C6-,4,4BA-8B84-8E89DDF7C407:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
2017-07-13 09:30:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
2017-07-13 09:30:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750CF6A3-B1D5-4221-85F0-7689E1747463","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] Session.disconnect() peer:D0F6381F-42C,6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", genera,tion: 0)
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BwTDYUy7yaDiFSHyuVcUjulDaTZQBiiu","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'BwTDYUy7yaDiFSHyuVcUjulDaTZQBiiu', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF (syncValue: WoREqLK,YDb3U6pfAopL33uLBNthvpDnr)'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22D,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4
[ThaliCore] Advertiser: session connected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4
[ThaliCore] Session.startOutputStream(with:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49613
,2017-07-13 09:30:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WoREqLKYDb3U6pfAopL33uLBNthvpDnr","error":null,"portNumber":49613}'
,2017-07-13 09:30:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WoREqLKYDb3U6pfAopL33uLBNthvpDnr', error: 'null', listeningPort: '49613''
,Connecting to the localhost:49613
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [10, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49613
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [10]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
[ThaliCore] Advertiser: session connected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
[ThaliCore] Session.startOutputStream(with:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [10, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [10]
,2017-07-13 09:30:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 []
2017-07-13 09:,30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49613
[ThaliCore] Session.disconnect,() peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:56E84AF2-239B-4D22-A375-8C1DE6AB0579
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0193AF29-BB70-49A6-9678-9B2D28BC8830
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
,[ThaliCore] Browser.startListening
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","generation":0}'
2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF, (syncValue: BriOUQUE1Yx5enNp4MjJnJ3dMpwHrcSZ)'
2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B1DC9E3-5BFB-,4,FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750CF6A3-B1D5-4221-85F0-7689E1747463","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0B6584A-55E2-4F22-9640-4ABB1B359C49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905
[ThaliCore] Advertiser: session connected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generati,on: 0)
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BriOUQUE1Yx5enNp4MjJnJ3dMpwHrcSZ","error":"Connection could not be established","portNumber":null}'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BriOUQUE1Yx5enNp4MjJnJ3dMpwHrcSZ', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 731C2C5E-0539-486A-B543-8DB415F54546 (syncValue: z1JK4Xf3HtjQa3cz7aNQ9LhWsDRYYwcb)'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "731C2C5E-0539-486A-B543-,8DB415F54546", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
[ThaliCore] Advertiser: session connected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905
,[ThaliCore] Session.session(_:peer:didChange:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49624
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
,2017-07-13 09:31:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z1JK4Xf3HtjQa3cz7aNQ9LhWsDRYYwcb","error":null,"portNumber":49624}'
,2017-07-13 09:31:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'z1JK4Xf3HtjQa3cz7aNQ9LhWsDRYYwcb', error: 'null', listeningPort: '49624''
[ThaliCore] Session.session(_:peer:didChange:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905 state: connecting -> connected
,Connecting to the localhost:49624
,[ThaliCore] Session.session(_:peer:didChange:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0
,Connected to the localhost:49624
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905
,[ThaliCore] Session.startOutputStream(with:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
[ThaliCore] Session.startOutputStream(with:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[Th,aliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [13, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (43800 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (21736 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [13, 14]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler disconnecting:false
,ok 124 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [13]
,# teardown
,2017-07-13 09:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:731C2C5E-0539-486A-B543-8DB415F54546
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49624
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:731C2C5E-0539-486A-B543-8DB415F54546:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:731C2C5E-0539-486A-B543-8DB415F54546:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C406573-00B6-4912-94B3-B0CBE00D25DB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9C406573-00B6-4912-94B3-B0CBE00D25DB
,2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Ready to advertise
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8248D49F-3330-495E-BBB6-42B9302DC516
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:31:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14FF933A-6407-49A5-B304-4E3B0E38C0F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14FF933A-6407-49A5-B304-4E3B0E38C0F3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-13 09:31:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F69CA319-33F9-4286-A1B4-068BC860B38B
[ThaliCore] Browser.startListening
,ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8E3E1107-5F0C-4571-A5DA-B69EB02ECF31", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:8E3E1107-5F0C-4571-A5DA-B69EB02ECF31
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 d,iscoveryActive should be false
ok 140 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 141 discoveryActive should be false
ok 142 advertisingActive should be true
ok 143 Can ,call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-13 09:31:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-13 09:31:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 09:31:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:6ae8816a-fecb-40e6-857f-bfbf65020542 error: startListeningNotActive
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XjE9jSyZaCxxSnltgUfq0R7CWpCngja4","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 159 Should only get called after multiConnect returned
,ok 160 SyncValue matches
,ok 161 Got right error
,ok 162 listeningPort is null
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6ae8816a-fecb-40e6-857f-bfbf65020542","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6ae8816a-fecb-40e6-857f-bfbf65020542","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4EEF4DE5-8EA7-4491-9BC9-4E8E5A3AA643
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 165 No error on starting
,ok 166 Got null as expected
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"n3T4WYMLQGIRHR5FDD8PneIPFc86uhKG","error":"Illegal peerID","portNumber":null}'
,ok 167 Should only get called after multiConnect returned
,ok 168 SyncValue matches
,ok 169 Got right error
,ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13, 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:13 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-13 09:31:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 174 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C5CE9E5E-3B98-4579-92A9-5D3C2224FB46
[ThaliCore] Browser.startListening
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 No error on starting
,ok 176 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 177 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 179 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 180 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:192b6e81-2616-4e39-aebe-6c7f1ac99675
,ok 182 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 183 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 184 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-13 09:31:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 185 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 186 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-13 09:31:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-13 09:31:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-13 09:31:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49631'
,ok 187 Should throw
,# teardown
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49633'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 initial connection state should be CONNECTED
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 189 final connection state should be DISCONNECTED
,# teardown
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49636'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 190 tried to connect to right port
,ok 191 failed due to refused connection
,ok 192 routerPortConnectionFailed is emitted
,# teardown
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49640'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 193 Send/recvd #1 should be equal length
ok 194 Send/recvd #1 should be same
ok 195 Send/recvd #2 should be equal length
ok 196 Send/recvd #2 should be same
ok 197 Should be exactly 2 client sockets
,# teardown
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - close'
2017-07-13 09:31:18, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49645'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 198 socket shouldn't close until after stream
,ok 199 incoming remains open
,# teardown
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49649'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should not have gotten an error
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 socket shouldn't close until after incoming
,ok 202 incoming is cleaned up
,# teardown
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49653'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 203 stream was closed
ok 204 incoming should survive
ok 205 mux should have no streams
,# teardown
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
2017-07-13 09:31:19, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49657'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 206 we should not have gotten an error
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 207 Buffers are identical
2017-07-13 09:31:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - close'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 208 native server is nulled out
ok 209 native server should be cl,osed
ok 210 incoming has been removed
ok 211 Incoming should be done
ok 212 The mux object should be closed
ok 213 The mux stream should be closed
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-07-13 09:31:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49661'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-13 09:31:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 214 native server is nulled out
ok 215 native server should be closed
,ok 216 incoming has been removed
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-13 09:31:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 49713'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 217 we should not have gotten an error
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 218 Buffers are identical
2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 219 server should be fine
ok 220 server should be open
ok 221 incoming has been removed
ok 222 The mux object should be clos,ed
ok 223 The mux stream should be closed
2017-07-13 09:31:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 49717'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 224 we should not have gotten an error
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 225 Buffers are identical
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 226 server should be fine
ok 227 server should be open
ok 228 incoming has been removed
ok 229 The mux object should be closed
ok 230 The mux stream should be closed
,# teardown
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:24 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 231 serversManager must not be null
,ok 232 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 233 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-13 09:31:24 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:24 - DEBUG createNativeListener: 'listening 49720'
ok 234 port must be in range
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'listening 49721'
ok 235 second start should return same port
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:26 - DEBUG createNativeListener: 'listening 49723'
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:26 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 236 we should be connected
2017-07-13 09:31:26 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 237 now we are disconnected
,2017-07-13 09:31:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-13 09:31:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:26 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 238 Passed bogus id
2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 239 Passed good id but bogus port
2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing co,nnection called on peerID foo with port 900'
ok 240 Passed right context
ok 241 Right server
ok 242 No error should be set
ok 243 Retry should be false
ok 244 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 49725
,ok 245 should be equal
,# teardown
,2017-07-13 09:31:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
2017-07-13 0,9:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 246 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[Tha,l,iCore] Browser.startListening
2017-07-13 09:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 247 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,2017-07-13 09:31:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","generation":0}'
,2017-07-13 09:31:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 258A0987-3B4C-46D2-8465-A55E41EB0EBC (syncValue: RZDvmSTHMmSbK6Bg7yg5R1D59VSQ0f3w)'
,2017-07-13 09:31:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
2017-07-13 09:31:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}'
2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940, (syncValue: Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03)'
2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-,4,51B-910D-A16CB2A3B940:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}'
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5BAF6D3-EDB2-4528-B144-7C271A324831 (syncValue: 7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML)'
2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-,7C271A324831", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Advertiser: session connected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Advertiser: session connected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] Session.disconnect() peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49734
2017-07-13 09:31:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML",,"error":null,"portNumber":49734}'
2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML', error: 'null', listeningPort: '49734''
2017-07-13 09:31:31 - WARN thaliMobileNativeTestUti,ls: 'multiConnectResolved received invalid syncValue: '7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML', originalSyncValue: 'RZDvmSTHMmSbK6Bg7yg5R1D59VSQ0f3w''
2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7a3wlf6DsigCLk,Q,8HUY6KpXOQxA6PMML', error: 'null', listeningPort: '49734''
2017-07-13 09:31:31 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: '7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML', originalSyncValue: 'Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03'',
2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7a3wlf6DsigCLkQ8HUY6KpXOQxA6PMML', error: 'null', listeningPort: '49734''
,ok 248 should be equal
ok 249 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49736
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03","error":null,"portNumber":49736}'
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03', error: 'null', listeningPort: '49736''
,2017-07-13 09:31:32 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03', originalSyncValue: 'RZDvmSTHMmSbK6Bg7yg5R1D59VSQ0f3w''
2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Pu0ktZdPuAMFcCeKN7uf23tJcu99Ui03', error: 'null', listeningPort: '49736''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connecting -> connected
,ok 250 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", genera,tion: 0)
2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RZDvmSTHMmSbK6Bg7yg5R1D59VSQ0f3w","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'RZDvmSTHMmSbK6Bg7yg5R1D59VSQ0f3w', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 258A0987-3B4C-46D2-8465-A55E41EB0EBC (syncValue: IGOVl2e,mfdsXwjaDDhLXldGShv9d84z1)'
2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IGOVl2emfdsXwjaDDhLXldGShv9d84z1","error":"Peer is unavailable","portNumber":null}'
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IGOVl2emfdsXwjaDDhLXldGShv9d84z1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:33 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49736
[ThaliCore] Session.disconnect() peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] Browser: session notConnected removed relay, for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] BrowserManager.disconnect peer:D5BAF6D3-EDB2-4528-B144-7C271A324831
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49734
[ThaliCore] Session.disconnect,() peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:9705760D-02FE-451B-910D-A16CB2A3B940
[ThaliCore] Session.session(_:peer:didCha,nge:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Pee,r(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple local http requests
,listening on 49738
,ok 251 should be equal
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected ,Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,ok 252 should be equal
,ok 253 should be equal
,# teardown
,2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
2017-07-13 0,9:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 254 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-13 09:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryAc,t,ive":true,"advertisingActive":true}'
2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startA,rguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 255 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
2017-07-13 09:31:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940, (syncValue: MEdRb6rX8MJLiStcMrqMG3oIoGI5MN5L)'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-,4,51B-910D-A16CB2A3B940:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Advertiser: session connected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Advertiser: session connected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":1}'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5BAF6D3-EDB2-4528-B144-7C271A324831 (syncValue: dyEu6Xah4hP95mgFQPrLxOYCdhwiEwv5)'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49746
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MEdRb6rX8MJLiStcMrqMG3oIoGI5MN5L","error":null,"portNumber":49746}'
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MEdRb6rX8MJLiStcMrqMG3oIoGI5MN5L', error: 'null', listeningPort: '49746''
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MEdRb6rX8MJLiStcMrqMG3oIoGI5MN5L', error: 'null', listeningPort: '49746''
,2017-07-13 09:31:54 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'MEdRb6rX8MJLiStcMrqMG3oIoGI5MN5L', originalSyncValue: 'dyEu6Xah4hP95mgFQPrLxOYCdhwiEwv5''
[ThaliCore] Session.session(_:didReceiveCertificate:fromPee,r:certificateHandler:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connecting -> connected
,ok 256 should be equal
[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
ok 257 (unnamed assert)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:comp,letion:) port:0 localport:49748
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dyEu6Xah4hP95mgFQPrLxOYCdhwiEwv5","error":null,"portNumber":49748}'
2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd,yEu6Xah4hP95mgFQPrLxOYCdhwiEwv5', error: 'null', listeningPort: '49748''
,ok 258 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:9705760D-02FE-451B-910D-A16CB2A3B940
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49746
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,[ThaliCore] BrowserManager.disconnect peer:D5BAF6D3-EDB2-4528-B144-7C271A324831
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49748
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,[ThaliCore] Session.deinit peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 09:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 261 specific error should be returned
,# teardown
,ok 262 must be stopped
,# setup
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 49750'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 263 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adv,ertisingActive":false}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-13 09:31:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 265 must be stopped
,# setup
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 49751'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:505B164B-4107-4EB6-A7E6-4FF5CB56F5E2
[ThaliCore] Browser.startListening
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 267 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:58 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 268 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 49752'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3D77D7D5-E5EB-4CF9-8589-3B993EE2874C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3D77D7D5-E5EB-4CF9-8589-3B993EE2874C
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 269 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3D77D7D5-E5EB-4CF9-8589-3B993EE2874C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:3D77D7D5-E5EB-4CF9-8589-3B993EE2874C
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 271 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 49755'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 273 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 274 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 275 network status should have certain non-empty properties
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-13 09:31:59 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 277 specific error expected
,# teardown
,ok 278 must be stopped
,# setup
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'listening 49756'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F2BE6FC5-77C5-47A5-90B1-4A6B5B6C514E
[ThaliCore] Browser.startListening
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "303B858B-4A99-4AAF-A085-F1C47A619DFB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,303B858B-4A99-4AAF-A085-F1C47A619DFB
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:59 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 280 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 49759'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6190F9A4-BBA1-47C1-AECA-045404127ECF
[ThaliCore] Browser.startListening
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "934B1DD1-C497-4AD0-B896-A4D2BBC7B837", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:934B1DD1-C497-4AD0-B896-A4D2BBC7B837
2017-07-13 0,9:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:0,0 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-13 09:32:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 282 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 49761'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:242112BD-3F07-47B4-82DC-4CA726B09AAD
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AD5CA790-6DF5-4933-B78B-F412A46DD736", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AD5CA790-6DF5-4933-B78B-F412A46DD736
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 283 is stopped after calling stop
,ok 284 connection should fail after stopping
,# teardown
,ok 285 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-13 09:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 287 error description matches
,# teardown
,ok 288 must be stopped
,# setup
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-13 09:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 289 must be stopped
,# setup
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 290 error description matches
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
,ok 292 IMPLEMENT ME!!!!!!
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-13 09:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 296 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 298 NOT IMPLEMENTED # SKIP
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 302 must be stopped
,# setup
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-13 09:32:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 303 must be stopped
,# setup
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 49764'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0065A84B-4844-4998-890C-E5F04B0ED6F9
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 304 discoveryActive matches
ok 305 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 306 discoveryActive matches
ok 307 advertisingActive matches
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 49765'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FD60C81-0C1F-46AF-A7E8-8008C081BB3A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6FD60C81-0C1F-46AF-A7E8-8008C081BB3A
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 308 discoveryActive matches
ok 309 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 310 discoveryActive matches
ok 311 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 49767'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
,# setup
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'listening 49768'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2901E54-3F4B-4DAD-B822-15890F56A48A
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:06 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,2D1BE89A-3F6E-4C07-9680-7C097E53E609
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:06 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B,940:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIden,tifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}]'
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}]'
2017-07-13 09:32:06 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 313 portNumber equal null
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-13 09:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
2017-07-13 09:32:07 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}]'
2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:07 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:0,7 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:07 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:32:07 - DEBU,G, makeIntoCloseAllServer: 'closeAll called on server'
ok 314 must be stopped
,# setup
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests between peers
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'listening 49770'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}]'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}'
2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B9,40:0
2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer,(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC (syncValue: 0aTyTb5SC4kr3dvVlHKNIRJpJsKqDqIp)'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}]'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}]'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:08 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"generation":1,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
2017-07-13 09:32:09 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}]'
2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}'
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:09 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:09 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
[ThaliCore] Session.disconnect() peer:F636408C-81C,5-48E5-BF5A-0AB8DC3CB1EC:0
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}]'
2017-07-13 09:32:,10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA,0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifie,r,":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","conne,ctionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B,0CE-C2A671E93E47","generation":0}]'
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapp,e,r: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:9705760D-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
2017-07-13 09:32:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}]'
2017-07-13 09:32:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"970,5760D-02FE-451B-910D-A16CB2A3B940","generation":1}'
,2017-07-13 09:32:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:13 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", genera,tion: 0)
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0aTyTb5SC4kr3dvVlHKNIRJpJsKqDqIp","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '0aTyTb5SC4kr3dvVlHKNIRJpJsKqDqIp', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC
2017-07-13 09:32:14 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5BAF6D3-EDB2-4528-B144-7C271A324831 (syncValue: hHiGIxuje7asSPhhClsieFM5jK3iq7JC)'
2017-07-13 09:32:14 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hHiGIxuje7asSPhhClsieFM5jK3iq7JC","error":"Peer is unavailable","portNumber",:null}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hHiGIxuje7asSPhhClsieFM5jK3iq7JC', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received p,eer availability changed event with {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {",peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-13 09:32:14 - DE,B,UG thaliMobileNativeTestUtils: 'Issuing multiConnect for AE6727F4-D361-4B1F-BB82-6390F9AEED26 (syncValue: 9e2urJ7lgMaU6naaqVKV7utsQs1SPRfh)'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.,connectToPeer(_:syncValue:completion:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: ,0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppe,dListening:)
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:1,4, - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49777
,2017-07-13 09:32:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9e2urJ7lgMaU6naaqVKV7utsQs1SPRfh","error":null,"portNumber":49777}'
,2017-07-13 09:32:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9e2urJ7lgMaU6naaqVKV7utsQs1SPRfh', error: 'null', listeningPort: '49777''
,2017-07-13 09:32:17 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [13, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:17 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:17 - DEBUG testUtils: 'Got end'
,ok 315 response body should match testData
,ok 316 must be started
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPListener.socketDidDisconnect(_:wit,hError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:2,3 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:23 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:32:23 - DEBU,G, makeIntoCloseAllServer: 'closeAll called on server'
ok 317 must be stopped
[ThaliCore] BrowserManager.disconnect peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningF,orConnectionsAndDisconnectClients() port:49777
[ThaliCore] Session.disconnect() peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange,:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(u,uid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,# setup
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'listening 49779'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:24 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,49058887-1F08-49CB-9D96-189287BA7435
2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:24 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
2017-07-13 09:32:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}]'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AE6727F4-D361-4B1F-BB82-6390F9AEED26 (syncValue: aIoE0Fu8oNqoGG1RudeMBmng068sT6sK)'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
2017-07-13 09:32:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}]'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvai,l,able":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","connectionType":"MPCF","peerAvailable":true,"generation":0,",newAddressPort":false}'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeW,rapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}]'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ev,ent with {"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] Session.disconnect() peer:AE6727F4-D36,1-4B1F-BB82-6390F9AEED26:0
2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}]'
2017-07-13 09:32:,29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}'
,2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:29 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", genera,tion: 0)
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aIoE0Fu8oNqoGG1RudeMBmng068sT6sK","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'aIoE0Fu8oNqoGG1RudeMBmng068sT6sK', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F,9AEED26","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26
2017-07-13 09:32:30 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B2AA0313-20EC-4F3D-B0CE-C2A671E93E47 (syncValue: CSZwy6gFZGiEnZrKUZ2Ly72S2G34cvQ7)'
2017-07-13 09:32:30 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99
[ThaliCore] Advertiser: session connected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99
[ThaliCore] Session.startOutputStream(with:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [13, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", genera,tion: 0)
2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CSZwy6gFZGiEnZrKUZ2Ly72S2G34cvQ7","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'CSZwy6gFZGiEnZrKUZ2Ly72S2G34cvQ7', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:B2AA0313-20EC-4F3D-B0CE-C2,A671E93E47
2017-07-13 09:32:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7 (syncVa,lue: bG2VCDldmJFxoZOLHI2gdI48um6WBhqb)'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation:, 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
[ThaliCore] Advertiser: session connected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49789
2017-07-13 09:32:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bG2VCDldmJFxoZOLHI2gdI48um6WBhqb",,"error":null,"portNumber":49789}'
2017-07-13 09:32:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bG2VCDldmJFxoZOLHI2gdI48um6WBhqb', error: 'null', listeningPort: '49789''
,2017-07-13 09:32:38 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [13, 16, 17, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
2017-07-13 09:32:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
2017-07-13 09:32:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:38 - DEBUG testUtils: 'Got response data'
2017-07-13 09:32:38 - DEBUG testUtils: 'Got end'
ok 318 response body should match testData
ok 319 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
[ThaliCore] Session.startOutputStream(with:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [13, 16, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:3,9 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-13 09:32:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 320 must be stopped
[ThaliCore] BrowserManager.disconnect peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliC,ore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49789
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect,(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,c,lient disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer,})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] Session.disconnect() peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] VirtualSocket.deinit vsID:18 [13, 16, 17, 19]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0 state: connected -> notConnected
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] Browser: session notConnected Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C82,36E4123D7", generation: 0)
# setup
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliC,ore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [13, 16, 19]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSock,et.deinit vsID:19 [13, 16]
,[ThaliCore] Session.session(_:peer:didChange:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-13 09:32:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 321 must be stopped
,# setup
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 322 must be stopped
,# setup
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'listening 49792'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:41 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,9F10A0D7-8856-4298-AD0B-593BA1AE204A
2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:41 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}]'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C084CE57-C7F3-4479-BF0F-ED3250D8F6A8 (syncValue: NjiqosJJaaSMO9ONQbJUMqqXVMA1nwUI)'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}]'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
2017-07-13 09:32:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}]'
2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", genera,tion: 0)
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NjiqosJJaaSMO9ONQbJUMqqXVMA1nwUI","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NjiqosJJaaSMO9ONQbJUMqqXVMA1nwUI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:46 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:32:46 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:32:46 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B2AA0313-20EC-4F3D-B0CE-C2A671E93E47 (syncValue: 5KfZa9q3eqoOjnFPDq2MLp9inLu6AVFM)'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:completion:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generati,on: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:s,t,oppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
[ThaliCore] Advertiser: session connected Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-13 09:32:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,[ThaliCore] Session.startOutputStream(with:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [13, 16, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", genera,tion: 0)
2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5KfZa9q3eqoOjnFPDq2MLp9inLu6AVFM","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:52 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '5KfZa9q3eqoOjnFPDq2MLp9inLu6AVFM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671,E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:52 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47
2017-07-13 09:32:52 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-13 09:32:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 946EA4DB-6614-40DB-B5B5-705E7310BB5E (syncValue: s5Wnj4HqA95QRyEJrgLejDoHKGMsKSlc)'
2017-07-13 09:32:52 - DEBUG thaliMo,b,ileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:session,NotConnected:) Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtu,alSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49804
2017-07-13 09:32:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"s5Wnj4HqA95QRyEJrgLejDoHKGMsKSlc","error":null,"portNumber":49804}'
2017-07-13 09:32:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 's5Wnj4HqA95QRyEJrgLejDoHKGMsKSlc', error: 'null', listeningPort: '49804''
,2017-07-13 09:32:55 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [13, 16, 20, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:55 - DEBUG testUtils: 'Got response data'
2017-07-13 09:32:55 - DEBUG testUtils: 'Got end'
ok 323 response body should match testData
ok 324 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [13, 16, 21]
,ok 325 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49804
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [13, 16]
,[ThaliCore] Session.disconnect() peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,# setup
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,ok 326 FIX ME, PLEASE!!!
,# teardown
,ok 327 must be stopped
,# setup
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-13 09:32:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 328 must be stopped
,# setup
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-13 09:32:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 329 must be stopped
,# setup
,ok 330 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 331 specific error should be returned
,# teardown
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13, 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:33:00 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:33:00 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 332 error should be null
ok 333 error should be null
,# setup
,ok 334 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 335 specific error should be returned
,# teardown
,ok 336 error should be null
ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 49806'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 339 error should be null
ok 340 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 341 error should be null
ok 342 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 343 error should be null
,ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 49807'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BD4179C3-99C4-4D4E-AA94-85D1022448AA
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 348 error should be null
,ok 349 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 49808'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "38BF00CF-37C3-4A08-A8B1-E47B289313E1", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:38BF00CF-37C3-4A08-A8B1-E47B289313E1
2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 353 error should be null
ok 354 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "38BF00CF-37C3-4A08-A8B1-E47B289313E1", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:38BF00CF-37C3-4A08-A8B1-E47B289313E1
20,17-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 355 error should be null
ok 356 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adv,ertisingActive":false}'
2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'dis,coveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'c,loseAll called on server'
,ok 357 error should be null
ok 358 error should be null
,# setup
,ok 359 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 49811'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 360 error should be null
,ok 361 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 362 error should be null
,ok 363 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-13 09:33:01 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 367 This should not cause wifi to fail
ok 368 native router should be bad
,# teardown
,ok 369 error should be null
ok 370 error should be null
,# setup
,ok 371 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'listening 49812'
,ok 372 first call should succeed
,ok 373 first call should succeed
,ok 374 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 375 error should be null
ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-13 09:33:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-13 09:33:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bb48968-b6a0-4076-992e-9d6f716317be","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 384 should be called once
ok 385 should not have been called more than once
,# teardown
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3bb48968-b6a0-4076-992e-9d6f716317be","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 386 error should be null
ok 387 error should be null
,# setup
,ok 388 ThaliMobile should be stopped
,# can get the network status
,ok 389 network status should have certain non-empty properties
,# teardown
,ok 390 error should be null
ok 391 error should be null
,# setup
,ok 392 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 393 we have not added peer to the cache yet
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26bdf339-c85e-47d8-9c59-90cb6e07803f","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 394 peer should be available
ok 395 cache contains native peer
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26bdf339-c85e-47d8-9c59-90cb6e07803f","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 396 peer should be unavailable
ok 397 peer has been removed from cache
,# teardown
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 401 we have not added peer to the cache yet
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49f8103b-d1dd-4956-ade7-4d87cf4fbd74","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,ok 403 cache contains wifi peer
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49f8103b-d1dd-4956-ade7-4d87cf4fbd74","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 404 peer should be unavailable
,ok 405 peer has been removed from cache
,# teardown
,ok 406 error should be null
ok 407 error should be null
,# setup
,ok 408 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"94a8b701-f669-4e23-a7d3-86f07f4658de","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 first peer is available
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35b727ca-a07f-4374-807e-f05e11d94fb8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 410 second peer is available
,ok 411 first and second peers are different
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"94a8b701-f669-4e23-a7d3-86f07f4658de","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"35b727ca-a07f-4374-807e-f05e11d94fb8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 error should be null
,ok 413 error should be null
,# setup
,ok 414 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 415 should not be in cache at start
2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b0236cb2-7213-4c66-9b46-fae8f20b55be","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 416 peer is available
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b0236cb2-7213-4c66-9b46-fae8f20b55be","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 417 error should be null
ok 418 error should be null
,# setup
,ok 419 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-13 09:33:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 420 error should be null
ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-13 09:33:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 423 error should be null
,ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"18e922f7-62e4-485c-beaf-2139e4cc9178","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 426 peer should be available
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"18e922f7-62e4-485c-beaf-2139e4cc9178","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 427 peer should be available
,ok 428 should store correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"18e922f7-62e4-485c-beaf-2139e4cc9178","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 49813'
2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0d4c4489-4e7a-4411-972c-062ccd99b9cc","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 432 discovered correct peer
ok 433 got correct generation
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0d4c4489-4e7a-4411-972c-062ccd99b9cc","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 434 discovered corr,ect peer
ok 435 got correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0d4c4489-4e7a-4411-972c-062ccd99b9cc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 436 error should be null
ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 49814'
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8dac63fd-4c32-42ec-bae7-8e42941fa4ef","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 439 discovered avai,lable peer
ok 440 peer is available
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8dac63fd-4c32-42ec-bae7-8e42941fa4ef","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 441 error should be null
,ok 442 error should be null
,# setup
,ok 443 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6babb2a9-7b76-42c7-ace6-71ca93a1e974","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 444 peer should be ,available
2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6babb2a9-7b76-42c7-ace6-71ca93a1e974","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 445 peer, should be unavailable
ok 446 should be removed from cache
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 49815'
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67d19785-4f4e-4fb0-bd85-491d89accfb0","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 450 first peer is expected to be available
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b536998-43d6-4119-90de-716a1c6933be","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 451 second peer is expected to be available
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9b536998-43d6-,4119-90de-716a1c6933be","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 452 peer became unavailable
,ok 453 it was wifi peer
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9b536998-43d6-4119-90de-716a1c6933be","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}',
ok 454 we found peer again
ok 455 it was wifi peer
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9b536998-43d6-4119-90de-716a1c6933be","connectionType":"tcp","peerAvailable":false,,"generation":null,"newAddressPort":null}'
ok 456 peer became unavailable
ok 457 it was wifi peer
,# teardown
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"67d19785-4f4e-4fb0-bd85-491d89accfb0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:08 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 458 error should be null
,ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-13 09:33:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 461 error should be null
ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 49816'
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da83a51b-02d0-4b5f-988a-6333e0374ec1","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 464 first peer is expected to be available
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05399eca-3c67-4151-a89e-7993db045a0f","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 465 second peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da83a51b-02d0-4b5f-988a-6333e0374ec1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 466 pee,r became unavailable
2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"05399eca-3c67-4151-a89e-7993db045a0f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 467 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 468 error should be null
ok 469 error should be null
,# setup
,ok 470 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-13 09:33:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-13 09:33:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 474 error should be null
ok 475 error should be null
,# setup
,ok 476 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936a0c42-f728-4114-9d51-779a17941c62","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 477 peer discovered first time does not have new address
2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936a0c42-f728-4114-9d51-779a17941c62","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 478 address has not been changed
2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936a0c42-f728-4114-9d51-779a17941c62","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 479 new port handled correctly
2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936a0c42-f728-4114-9d51-779a17941c62","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 480 new host handled correctly
2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"936a0c42-f728-4114-9d51-779a17941c62","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 481 newAddressPort is null for unavailable peers
,# teardown
,ok 482 error should be null
ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-13 09:33:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 485 error should be null
ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 488 NOT IMPLEMENTED # SKIP
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-13 09:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 495 should be equal
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-13 09:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 502 contains expected properties
ok 503 the same ho,stAddress
ok 504 the same portNumber
,# teardown
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 505 error should be null
,ok 506 error should be null
,# setup
,ok 507 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 508 contains expected properties
ok 509 the same hostAddress
ok 510 the same portNumber
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 511 error should be null
ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 49817'
2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ec450ff-91d1-4659-b358-4a7fde7e94ae","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 514 Got specific error message
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0ec450ff-91d1-4659-b358-4a7fde7e94ae","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdverti,singStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 49818'
2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0c802183-c52c-49e1-94ed-610d2c643a2c","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:0c802183-c52c-49e1-94ed-610d2c643a2c
,ok 518 native wrapper `disconnect` called once
ok 519 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0c802183-c52c-49e1-94ed-610d2c643a2c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 520 error should be null
ok 521 error should be null
,# setup
,ok 522 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-13 09:33:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 523 error should be null
ok 524 error should be null
,# setup
,ok 525 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-13 09:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 526 error should be null
ok 527 error should be null
,# setup
,ok 528 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-13 09:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 529 error should be null
ok 530 error should be null
,# setup
,ok 531 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,ok 534 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 535 error should be null
ok 536 error should be null
,# setup
,ok 537 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 538 error should be null
ok 539 error should be null
,# setup
,ok 540 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-13 09:33:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 541 error should be null
,ok 542 error should be null
,# setup
,ok 543 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'listening 49819'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB68703A-82C4-4F5D-B702-F06BA199011E
[ThaliCore] Browser.startListening
2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"20cced7e-1872-434f-b456-5f3549b99072","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 544 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d465da31-9ca7-4da7-a91f-282b7e3b6cf8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 545 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"20cced7e-1872-434f-b456-5f3549b99072","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d465da31-9ca7-4da7-a91f-282b7e3b6cf8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 546 No peers
,ok 547 No peers
,ok 548 No peers
,# teardown
,ok 549 error should be null
ok 550 error should be null
,# setup
,ok 551 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'listening 49820'
2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba248a84-983f-4706-884e-c4648ab184ee","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 552 1
ok 553 2
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e229ee2a-19a9-4f22-be4a-ec203627b049","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ba248a84-983f-4706-884e-c4648ab184ee","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13, 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e229ee2a-19a9-4f22-be4a-ec203627b049","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:17 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-13 09:33:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 554 error should be null
ok 555 error should be null
,# setup
,ok 556 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-13 09:33:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 557 error should be null
ok 558 error should be null
,# setup
,ok 559 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'listening 49821'
,ok 560 error should be null
,ok 561 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:39984708-4DDD-48C8-82A8-BD25A56C4040
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 562 error should be null
,ok 563 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 564 error should be null
,ok 565 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","generation":0}]'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5FCCD746-4D8D-40F2-BC08-F7A42F066745 (syncValue: 0)'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","generation":0}]'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49824
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
[ThaliCore] A,dvertiser: session connected Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9C5D4377,-7D93-4F72-844F-2719CD011FFB state: notConnected -> connecting
2017-07-13 09:33:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":49824}'
2017-07-13 09:33:23 - DEBUG thaliMobileNativeWrapper: 'Issuing ,multiConnect for 8F99E40C-F002-41B4-82DB-5743D21B8724 (syncValue: 1)'
2017-07-13 09:33:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) pe,er:8F99E40C-F002-41B4-82DB-5743D21B8724:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [13, 16, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:23 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:23 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
[ThaliCore] Session.startOutputStream(with:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [13, 16, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49829
2017-07-13 09:33:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":49829,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [13, 16, 22, 23, 24]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:26 - DEBUG testUtils: 'Got response data'
2017-07-13 09:33:26 - DEBUG testUtils: 'Got end'
ok 566 received all uuids
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] Advertiser: session connected Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
2017-07-13 09:33:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}]'
,2017-07-13 09:33:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}'
2017-07-13 09:33:30 - DEBUG thaliMobileNativeWrapper: 'hand,lePeerAvailabilityChanged - Emitting {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:33:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] Session.startOutputStream(with:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,5 [13, 16, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13, 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:33:31 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.,stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:33:31 - INFO thaliMobile: 'Receiv,e,d state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-13 09:33:31 - INFO thaliMobile: 'Filtered out discoveryAdver,tisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":f,alse,"advertisingActive":false}'
2017-07-13 09:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
ok 567 error should be null
,ok 568 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
# setup
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [13, 16, 22, 24, 25]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [13, 16, 22, 24]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:22 [13, 16, 24]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [13, 16]
,ok 569 ThaliMobile should be stopped
,# test for data corruption
,2017-07-13 09:33:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 570 error should be null
ok 571 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 572 getPeerIdentifier
,ok 573 getConnectionType
,ok 574 getActionType
,ok 575 getActionState
,ok 576 getPskIdentity
,ok 577 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 578 initial state
ok 579 after start
2017-07-13 09:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 580 after kill
# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-13 09:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 582 clean kill
,ok 583 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 584 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 585 forever agent should have it's own destroy method
ok 586 agent's destroy should be called
ok 587 agent's destroy should not be called again
ok 588 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 589 Entry counter must be 1
,ok 590 Entry exists
,ok 591 Size must be 1
,ok 592 Entry counter must be 2
,ok 593 Entry exists
,ok 594 Size must be 2
,ok 595 Entry counter must be 1
,ok 596 Entry exists
,ok 597 Size must be 3
,ok 598 Entry counter must be 2
,ok 599 Entry exists
,ok 600 Size must be 4
,ok 601 Entry 1_1 should not be found
,ok 602 Entry 1_1 does not exist
,ok 603 Size must be 3
,ok 604 Entry 1_2 should not be found
,ok 605 Entry 1_2 does not exist
,ok 606 Size must be 2
,ok 607 should be equal
,ok 608 Entry 2_1 should not be found
,ok 609 Entry 2_2 should not be found
,ok 610 Entry 2_1 does not exist
,ok 611 Entry 2_2 does not exist
,ok 612 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 613 Size must be100
,ok 614 Entries between 20 and MAXSIZE + 20 should exist
,ok 615 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 616 Entries between 6 and MAXSIZE + 4 should exist
,ok 617 Size should be MAXSIZE
ok 618 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 619 WAITING state entry should not be removed
,ok 620 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 621 Size should be MAXSIZE
,ok 622 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 623 Kill should be called once
,ok 624 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 625 is an agent
ok 626 enqueue is fine
ok 627 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 628 is an agent
ok 629 first enqueue is fine
,ok 630 is an agent
ok 631 second enqueue is fine
ok 632 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 633 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 634 is an agent
,ok 635 good enqueue
,ok 636 Identity should match
,2017-07-13 09:33:40 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:40 - DEBUG testUtils: 'Got end'
,ok 637 Got expected response
,ok 638 Got psk call back
,# teardown
,2017-07-13 09:33:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 639 is an agent
,ok 640 enqueue worked
,ok 641 is an agent
,ok 642 enqueue 2 worked
,ok 643 enqueue is not available when stopped
,ok 644 start action is killed
,ok 645 killed action is still killed
,ok 646 enqueued action when stopped is killed
,ok 647 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 648 good start
,ok 649 good enqueue
,ok 650 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 651 null arg
ok 652 wrong arg type
ok 653 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 654 good enqueue
ok 655 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 656 good enqueue
ok 657 2nd good enqueue
ok 658 we are in the pool
ok 659 We are out of the pool
ok 660 Action was killed
ok 661 The original kill was called too
ok 662 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 663 good enqueue
ok 664 first kill
ok 665 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 666 1st good enqueue
ok 667 2nd good enqueue
,ok 668 1st action is in the pool
,ok 669 2nd action is in the pool
,ok 670 1st action is out of the pool
,ok 671 2st action is out of the pool
,ok 672 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-13 09:33:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 673 Got right error
,ok 674 Start should not be called
,ok 675 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-13 09:33:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:43 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 676 Got right error
,ok 677 Start should not be called
,ok 678 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 679 Got null
2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 680 is an agent
2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 681 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 682 Got Null
,ok 683 Got another null
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 684 is an agent
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 685 is an agent
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 686 Action 1 killed at least once
,ok 687 Action 1 went first
,ok 688 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 689 should have gotten null
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 690 Should have stopped nicely
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 691 Still looking for null
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 692 Yup, another null
,ok 693 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 694 Null 1
,ok 695 (unnamed assert)
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 696 is an agent
,ok 697 Null 3
,ok 698 Replication not yet called
,ok 699 Notification 2 not yet called
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 700 is an agent
,ok 701 Notification went first
,ok 702 Notification 2 not called yet
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 703 is an agent
,ok 704 Notification finished
,ok 705 Replication finished
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 706 is an agent
,ok 707 First does not throw
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 708 is an agent
,ok 709 Second does not throw
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 first ok
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 712 is an agent
,ok 713 second ok
,ok 714 third ok
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-13 09:33:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-13 09:33:46 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 715 peerIdentifier should match
,ok 716 generation should match
,ok 717 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 718 good beacon
,ok 719 good preAmble
,ok 720 public keys match!
,ok 721 must return null after successful call
,ok 722 Once start returns the action should be in KILLED state
,# teardown
,2017-07-13 09:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 723 Response should be HTTP_BAD_RESPONSE
,ok 724 must return null after successful call
,# teardown
,2017-07-13 09:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 725 Response should be NETWORK_PROBLEM
ok 726 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-13 09:33:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 727 Resolution should be BAD_PEER
,ok 728 correct error message
,# teardown
,2017-07-13 09:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 729 Call start once
,ok 730 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 731 must return null after successful call.
,# teardown
,2017-07-13 09:33:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 732 Should be Killed
,ok 733 Start after killed
,# teardown
,2017-07-13 09:33:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 734 Should be KILLED
,ok 735 must return null after successful kill
,# teardown
,2017-07-13 09:33:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 736 Should be KILLED
ok 737 must return null after successful kill
,# teardown
,2017-07-13 09:33:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 738 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 739 must return null after successful call
,# teardown
,2017-07-13 09:33:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-13 09:33:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 740 Should be NETWORK_PROBLEM caused closing server socket
ok 741 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 742 Should be NETWORK_PROBLEM caused closing client socket
ok 743 Should be Could not establish TCP connection
,# teardown
,2017-07-13 09:33:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 744 publicKeysToNotify cannot be null
ok 745 ecdh for local device cannot be null
ok 746 milliseconds cannot be less than 0
ok 747 milliseconds cannot be 0
ok 748 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 749 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 750 should be equal
ok 751 should be equal
,ok 752 (unnamed assert)
,ok 753 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 754 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 755 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 756 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 757 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 759 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 763 should be equal
ok 764 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 765 right number of calls to address book
,ok 766 good preAmble
ok 767 good unencryptedKeyId
,ok 768 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 769 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 770 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 771 Matching numbers
,ok 772 We have an entry!
,ok 773 keys match
,ok 774 secrets match
,ok 775 We have an entry!
,ok 776 keys match
,ok 777 secrets match
,ok 778 We have an entry!
,ok 779 keys match
ok 780 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 781 Streams have same length
,ok 782 matching size
,ok 783 keys match
,ok 784 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 785 should be equal
,ok 786 peerDictionalty contains 2 peers
,ok 787 bluetooth peer's notification has correct connection type
,ok 788 tcp peer's notification has correct connection type
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-13 09:34:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 789 notification peer dictionary contains exactly 1 peer
,2017-07-13 09:34:06 - WARN thaliNotificationClient: 'peer is not available'
,ok 790 notification peer dictionary does not contain any peers
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-13 09:34:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 791 entry exists
,ok 792 entry is resolved
,# teardown
,2017-07-13 09:34:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 793 Action should be KILLED
ok 794 Peer state should be RESOLVED
,# teardown
,2017-07-13 09:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 795 hostAddress must match
,ok 796 portNumber must match
,ok 797 suggestedTCPTimeout must match
,ok 798 connectionType must match
,ok 799 peerIDs must match
,# teardown
,2017-07-13 09:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 800 Correct error
,# teardown
,2017-07-13 09:34:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 801 hostAddress must match
,ok 802 portNumber must match
,ok 803 suggestedTCPTimeout must match
,ok 804 connectionType must match
,ok 805 peerIds must match
,# teardown
,2017-07-13 09:34:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 807 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 808 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:11 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 809 action should be resolved with NETWORK_PROBLEM error
,ok 810 correct number of requests
,ok 811 correct number of failures
,ok 812 correct final peer state
,# teardown
,2017-07-13 09:34:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-13 09:34:13 - WARN thaliNotificationClient: 'peer is not available'
2017-07-13 09:34:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 813 peerDictionary should become empty
,# teardown
,2017-07-13 09:34:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-13 09:34:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 failed with expected error
,ok 815 peer state should be RESOLVED
,# teardown
,2017-07-13 09:34:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-13 09:34:14 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 816 First action failed
,ok 817 second action killed
# teardown
,2017-07-13 09:34:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 818 secrets are equal
,ok 819 Public key matches with the server key
,ok 820 hostAddress must match
,ok 821 portNumber must match
,ok 822 suggestedTCPTimeout must match
,ok 823 connectionType must match
,# teardown
,2017-07-13 09:34:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 824 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 825 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-13 09:34:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 827 All keys need to be available in the cache
,ok 828 All entries should be expired after 1 second
,# teardown
,2017-07-13 09:34:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 829 Size of the cache should be 2
,ok 830 Cache doesn't contain dictionary1
,ok 831 Size of the cache should be 1
ok 832 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-13 09:34:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 833 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 834 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 835 StartUpdateAdvertisingAndListening should not be called
,ok 836 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 837 no error
,ok 838 should be 204
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 839 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 840 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 841 no error
,ok 842 should be 200
,ok 843 should be equal
,ok 844 should be equal
,ok 845 (unnamed assert)
,ok 846 no error
,ok 847 should be 204
,# teardown
,2017-07-13 09:34:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 848 error should be null
ok 849 should be 204
# teardown
,2017-07-13 09:34:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 850 should be 404
# teardown
,2017-07-13 09:34:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 851 equal keys
,ok 852 not equal connection type
,ok 853 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-13 09:34:24 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 854 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 855 second cleared dictionary
2017-07-13 09:34:24 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 856 First start and on called correctly
,ok 857 First stop and removeListener called correctly
ok 858 first action kill called
ok 859 second action kill called
ok 860 first cleared dictionary
ok 861 first cleared pool
ok 862 second cleared dictionary
ok 863 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 864 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-13 09:34:25 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 865 listener has been set
ok 866 peer dictionary has expected number of entries
ok 867 Dictionary and pool have same action
ok 868 ads match
ok 869 ,PouchDB matches
ok 870 DB Names match
,ok 871 public keys match
,ok 872 peer dictionary has expected number of entries
,ok 873 Dictionary and pool have same action
,ok 874 ads match
,ok 875 PouchDB matches
,ok 876 DB Names match
,ok 877 public keys match
,2017-07-13 09:34:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 878 start called once
,ok 879 One entry left
,ok 880 Dictionary and pool have same action
,ok 881 Start never called
,ok 882 Kill called once
,ok 883 no entries left
,ok 884 Third action is dead
,ok 885 peer dictionary has expected number of entries
,ok 886 Dictionary and pool have same action
,ok 887 ads match
,ok 888 PouchDB matches
,ok 889 DB Names match
,ok 890 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-13 09:34:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-13 09:34:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 891 right error
,# teardown
,2017-07-13 09:34:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 892 right error
,# teardown
,2017-07-13 09:34:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 893 Got, error as expected
,# teardown
,2017-07-13 09:34:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 894 Got error as expected
,# teardown
,2017-07-13 09:34:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-13 09:34:28 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-13 09:34:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 895 Got error as expected
,# teardown
,2017-07-13 09:34:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-13 09:34:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 896 should be equal
,ok 897 All tests passed!
,# teardown
,2017-07-13 09:34:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-13 09:34:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:36 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 898 should be equal
ok 899 All tests passed!
,# teardown
,2017-07-13 09:34:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-13 09:34:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-13 09:34:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 900 action should be killed
ok 901 Error should be timed out
,ok 902 No doc found
,# teardown
,2017-07-13 09:34:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-13 09:34:43 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:44 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 903 should be equal
,2017-07-13 09:34:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-13 09:34:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 904 action should be killed
ok 905 Error should be timed out
,# teardown
,2017-07-13 09:34:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 906 socket hung up
,# teardown
,2017-07-13 09:34:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 907 same getPeerAdvertisesDataForUs
ok 908 Same pouchdB
ok 909 same localDbName
ok 910 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'listening 49958'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Browser.startListening
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E48E184A-0302-4946-8B90-52C396560D15
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
2017-07-13 09:34:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","generation":0}]'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","generation":0}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 2)'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE31,6BB98A8", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E,1,D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Advertiser: session connected Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E85005C5-0D84-44ED-B96D-D756C4327934 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0 state: notConnected -> connecting
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0BC5F6,D9-8F29-4D0E-A0D2-D2915AEAC427","generation":0}]'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","generation":0}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Advertiser: session connected Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Session.session(_:peer:didChange:) peer:E85005C5-0D84-44ED-B96D-D756C4327934 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49961
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":49961}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 3)'
2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":49961}'
2017-07-13 09:,34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 4)'
2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:,completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":49961}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 5)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":49961}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 6)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [13, 16, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [13, 16, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [13, 16, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [13, 16, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [13, 16, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [13, 16, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [13, 16, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [13, 16, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [13, 16, 26, 27, 28, 29, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [13, 16, 27, 28, 29, 30, 31, 32, 33, 34]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [13, 16, 27, 28, 29, 31, 32, 33, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [13, 16, 27, 28, 29, 32, 33, 34]
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [13, 16, 28, 29, 32, 33, 34]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [13, 16, 28, 29, 33, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [13, 16, 28, 29, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [13, 16, 28, 29, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4,A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [13, 16, 28, 29, 33, 34, 35, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [,13, 16, 28, 29, 34, 35, 36, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [13, 16, 28, 29, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [13, 16, 28, 34, 35, 36, 37, 38]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [13, 16, 28, 34, 35, 36, 37, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [13, 16, 28, 35, 36, 37, 38, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:34:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [13, 16, 28, 36, 37, 38, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler d,isconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [13, 16, 28, 37, 38, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,0 [13, 16, 28, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,37
[ThaliCore] VirtualSocket.deinit vsID:37 [13, 16, 28, 38, 39, 40]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [13, 16, 28, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [13, 16, 28, 38, 39, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [13, 16, 28, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,4 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 48, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 48, 49, 50, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:34:55 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 48, 49, 51]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:48 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51]
[ThaliCore] T,CPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 52]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53]
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49993
2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":49993,}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 7)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":49993}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 8)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":49993}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 9)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":49993}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 56]
[ThaliCore] Se,ssion.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 56, 57]
[ThaliCore] Session.sess,ion(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 56, 57, 58]
[ThaliCore] BrowserRelay.didOp,enVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 57, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 55, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 59]
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [13, 16, 28, 38, 39, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [13, 16, 28, 38, 40, 41, 42, 43, 44, 45, 47, 49, 51, 53, 59, 60]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [13, 16, 28, 38, 40, 41, 43, 44, 45, 47, 49, 51, 53, 59, 60]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [13, 16, 28, 38, 40, 41, 44, 45, 47, 49, 51, 53, 59, 60]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [13, 16, 28, 38, 40, 41, 44, 45, 49, 51, 53, 59, 60]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [13, 16, 28, 40, 41, 44, 45, 49, 51, 53, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [13, 16, 28, 40, 44, 45, 49, 51, 53, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.soc,ketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] VirtualSocket.deinit vsID:45 [13, 16, 28, 40, 44, 49, 51, 53, 59, 60],
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [13, 16, 28, 40, 44, 51, 53, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [13, 16, 28, 40, 44, 51, 53, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [13, 16, 28, 44, 51, 53, 59, 60, 61]
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [13, 16, 28, 51, 53, 59, 60, 61]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [13, 16, 28, 53, 59, 60, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect,(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOu,tputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [13, 16, 28, 53, 59, 60, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [13, 16, 28, 59, 60, 61, 62]
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [13, 16, 28, 59, 60, 61, 62, 63]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [13, 16, 28, 59, 60, 61, 62, 63, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:63
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [13, 16, 28, 59, 60, 61, 62, 64]
,2017-07-13 09:34:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:35:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-13 09:35:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [13, 16, 28, 60, 61, 62, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [13, 16, 28, 61, 62, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
[ThaliCore] VirtualSocket.deinit vsID:61 [13, 16, 28, 62, 64]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [13, 16, 28, 62]
,2017-07-13 09:37:50 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-13 09:37:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:37:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:37:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:37:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result:, skipped - Call of onCheckpointReached handler on a single db change'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-13 09:44:49 - INFO Coordina,tedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER, result: passed - test defaultDirectory'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-07,-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-13 09:44:49 - INFO CoordinatedCli,ent: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TE,S,T_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017,-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed -, test sinon sansbox spy'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-07-13 ,09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-13 09:44:49 - INFO Coordinated,C,lient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get same port when trying to connect multiple times on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has the same local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appli,cation/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxco,re/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-13 09:44:50 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 911 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-13 09:44:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43D,B-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:49:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:49:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-4,3DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/243B6EBA-2B48-43DB-9ED5-F529E79665FD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
