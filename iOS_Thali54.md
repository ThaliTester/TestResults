#### Test 113351851fe156cf_iOS_Thali54 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone SE 'Thali54' (5f598c405d20d04b836dd4c89356e94737c1c2d2) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone SE 'Thali56' (8effff55cdeae82604a08043752b940f94063299).
,Skipping N69uAP 'Thali55' (d7a40d176e510e468af45ed03d4ca45fd18dbe43).
,(lldb) command source -s 0 '/tmp/981D7671-4B6F-42B8-9665-80A2F1EB1998/fruitstrap-lldb-prep-cmds-5f598c405d20d04b836dd4c89356e94737c1c2d2'
,Executing commands in '/tmp/981D7671-4B6F-42B8-9665-80A2F1EB1998/fruitstrap-lldb-prep-cmds-5f598c405d20d04b836dd4c89356e94737c1c2d2'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58467"
,(lldb)     command script import "/tmp/981D7671-4B6F-42B8-9665-80A2F1EB1998/fruitstrap_5f598c405d20d04b836dd4c89356e94737c1c2d2.py"
,(lldb)     command script add -f fruitstrap_5f598c405d20d04b836dd4c89356e94737c1c2d2.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_5f598c405d20d04b836dd4c89356e94737c1c2d2.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_5f598c405d20d04b836dd4c89356e94737c1c2d2.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_5f598c405d20d04b836dd4c89356e94737c1c2d2.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A83B27B7-68C2-458F-AC,E2-0F2D682F655E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A83B27B7-68C2-458F-ACE2-0F2D682F655E
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:182B15AC-D951-46A2-9804-8B5334566E8A
[ThaliCore] Browser,ng with peerID:5B877852-CEB6-4477-885E-8FCBABBD01A5
,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F1F626D-239B-4F77-9FFE-F1D43E5662D0
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B877852-CEB6-4477-885E-8FCBABBD01A5", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5B877852-CEB6-4477-885E-8FCBABBD01A5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5B877852-CEB6-4477-885E-8FCBABBD01A5", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-12 13:15:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.543276071548462
,2017-07-12 13:15:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-Thali54''
,2017-07-12 13:15:33 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5B877852-CEB6-4477-885E-8FCBABBD01A5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5B877852-CEB6-4477-885E-8FCBABBD01A5", generation: 0)
,2017-07-12 13:15:34 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-12 13:15:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-12 13:15:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-12 13:15:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-12 13:15:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-12 13:15:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:19:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D,0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:19:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:19:10 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-12 13:19:10 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-12 13:19:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-12 13:19:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-12 13:19:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-12 13:19:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-12 13:19:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-12 13:19:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-12 13:19:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-12 13:19:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-12 13:19:19 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-12 13:19:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-12 13:19:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F0BD8837-D361-409E-B271-D42895C086F8
[ThaliCore] Browser.startListening
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F72D571C-EC0F-449A-9DF0-9A1DC45ED503
,[ThaliCore] Browser.startListening
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "58D74E02-5324-42A3-A4B4-9377406C7F80", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:58D74E02-5324-42A3-A4B4-9377406C7F80
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discovery,AdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A3658BC5-A201-4EE2-8D46-136624FAA090", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A3658BC5-A201-4EE2-8D46-136624FAA090
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A3658BC5-A201-4EE2-8D46-136624FAA090", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:A3658BC5-A201-4EE2-8D46-136624FAA090
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "28D672EA-BDC0-451D-AE1A-310791B29438", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:28D672EA-BDC0-451D-AE1A-310791B29438
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DF6B1910-3650-4BE9-80B0-25E4634E7550
[ThaliCore] Browser.startListening
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D34F925-0999-4B0C-A7C1-80153F143540:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D34F925-0999-4B0C-A7C1-80153F143540", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28D672EA-BDC0-451D-AE1A-310791B29438:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28D672EA-BDC0-451D-AE1A-310791B29438", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 ,13:19:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-12 13:19:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:672362F3-126A-49FF-B6E6-EC96571CC220
2017-07-12 1,3:19:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD
[Thal,i,Core] Browser.startListening
2017-07-12 13:19:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:28 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
2017-07-12 13:19:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","generation":0}'
2017-07-12 13:19:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E59712F0-72F6-4566-A8D4-829A16C30569, (syncValue: 8qmvPbyXLgpfma5MDSMhUaY5fBXKXGn0)'
2017-07-12 13:19:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD
[ThaliCore] Advertiser: session connected Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
2017-07-12 13:19:30 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D07ED69B-057D-4B8B-B6E1-38CC4EB251F4","generation":0}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57095
2017-07-12 13:19:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8qmvPbyXLgpfma5MDSMhUaY5fBXKXGn0","error":null,"portN,umber":57095}'
2017-07-12 13:19:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8qmvPbyXLgpfma5MDSMhUaY5fBXKXGn0', error: 'null', listeningPort: '57095''
,2017-07-12 13:19:32 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
[ThaliCore] Session.session(_:peer:didChange:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD state: connecting -> connected
,# teardown
,2017-07-12 13:19:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:E59712F0-72F6-4566-A8D4-829A16C30569
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57095
[ThaliCore] Session.disconnect() peer:E59712F0,-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD82B37D-D503-467F-9AA6-26A0F563A03B
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:39, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
[ThaliCore] Browser.startListening
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
2017-07-12 13:19:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","generation":0}'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E59712F0-72F6-4566-A8D4-829A16C30569, (syncValue: NVODcWNzBwEBlZ9QRYz0Qp8KAk2BvuAt)'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E59712F0-72F6-,4,566-A8D4-829A16C30569:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
2017-07-12 13:19:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
2017-07-12 13:19:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", genera,tion: 0)
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NVODcWNzBwEBlZ9QRYz0Qp8KAk2BvuAt","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NVODcWNzBwEBlZ9QRYz0Qp8KAk2BvuAt', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"E59712F0-72F6-4566-A8D4-829A16C30569","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:19:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1 (syncValue: DdO3preCv8tyJIL4lUbXJTrErhTRFTEA)'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB,1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82
[ThaliCore] Advertiser: session connected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82
[ThaliCore] Session.session(_:peer:didChange:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0 state: connecting -> connected
[ThaliCo,re] Browser: session connected to Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57100
,2017-07-12 13:19:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DdO3preCv8tyJIL4lUbXJTrErhTRFTEA","error":null,"portNumber":57100}'
2017-07-12 13:19:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DdO3preCv8tyJIL4lUbXJTrErhTRFTEA', error: 'null', listeningPort: '57100''
,Connecting to the localhost:57100
,Connected to the localhost:57100
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82
[ThaliCore] Session.startOutputStream(with:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo,={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-12, 13:19:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 104 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
[ThaliCore] Advertiser: session connected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
,[ThaliCore] Session.session(_:peer:didChange:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
[ThaliCore] Session.startOutputStream(with:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [1, 2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:19:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57100
[ThaliCore] Session.disconnect() peer:48C5A4A8,-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] Session.session(_:peer:didChange:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", gene,r,ation: 0)
# setup
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0 state: connected -> notConnected
[ThaliCore] AdvertiserRelay.closeRelay()
[Th,aliCore] Browser: session notConnected Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A00410,B6-5ED5-41E7-AB5A-EEDCF0B491F8
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
[ThaliCore] Session.session(_:peer:didChange:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82 state: connected -> notConnec,ted
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C089239F-FC8D-476E-944D-1E38E0C79965
2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[Tha,l,iCore] Browser.startListening
2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
2017-07-12 13:19:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","generation":0}'
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1, (syncValue: aVQrG0kuUUSonr8dutGoAqqxni3FO3Va)'
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:48C5A4A8-57FA-,46F2-94D3-ADC762D5DCB1:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
2017-07-12 13:19:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C089239F-FC8D-476E-944D-1E38E0C79965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", genera,tion: 0)
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aVQrG0kuUUSonr8dutGoAqqxni3FO3Va","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'aVQrG0kuUUSonr8dutGoAqqxni3FO3Va', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 188FFAC5-6F17-4776-8380-760277222EAD (syncValue: knylvBa,zYBXk7oJpz1SWx3Cl1gIYu8x3)'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:188FFAC5-6F17-4776-8380-760277222EA,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57108
2017-07-12 13:20:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"knylvBazYBXk7oJpz1SWx3Cl1gIYu8x3",,"error":null,"portNumber":57108}'
2017-07-12 13:20:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'knylvBazYBXk7oJpz1SWx3Cl1gIYu8x3', error: 'null', listeningPort: '57108''
,Connecting to the localhost:57108
Connecting to the localhost:57108
Connecting to the localhost:57108
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
Connected to the localhost:57108
Connected to the localhost:57108
C,onnected to the localhost:57108
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 2, 4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 112 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStream,s() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [1, 2, 5, 6]
,ok 113 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 114 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# teardown
,2017-07-12 13:20:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:188FFAC5-6F17-,4776-8380-760277222EAD
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57108
[ThaliCore] Session.disconnect() peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: ",188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
,# setup
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:25A9319C-4651-4DA1-97A8-134FE895A283
[ThaliCore] Browser.startListening
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
2017-07-12 13:20:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","generation":0}'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 188FFAC5-6F17-4776-8380-760277222EAD, (syncValue: BmqcRW61po9xg4p1pgvo5B74zRwzm1fV)'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:188FFAC5-6F17-,4776-8380-760277222EAD:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
2017-07-12 13:20:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
2017-07-12 13:20:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", genera,tion: 0)
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BmqcRW61po9xg4p1pgvo5B74zRwzm1fV","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'BmqcRW61po9xg4p1pgvo5B74zRwzm1fV', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F813D69B-C593-4754-A03D-1675EBF9957D (syncValue: 9IQnGwa,557igR1b4aHmSnfLi74CfK3aD)'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F813D69B-C593-4754-A03D-1675EBF9957,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C
[ThaliCore] Advertiser: session connected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
[ThaliCore] Advertiser: session connected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57118
2017-07-12 13:20:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9IQnGwa557igR1b4aHmSnfLi74CfK3aD",,"error":null,"portNumber":57118}'
2017-07-12 13:20:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9IQnGwa557igR1b4aHmSnfLi74CfK3aD', error: 'null', listeningPort: '57118''
,Connecting to the localhost:57118
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C
[ThaliCore] Session.startOutputStream(with:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [1, 2, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 2, 5, 6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,Connected to the localhost:57118
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-12 13:20:20 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeSt,reams() vsID:7
,ok 119 got the same data back
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
[ThaliCore] Session.startOutputStream(with:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 2, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting,:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCo,re] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,e,amsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 2, 5, 6, 7, 8]
,2017-07-12 13:20:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingA,ctive":false}'
,2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A state: connected -> notConnected
,[ThaliCore] BrowserManager.disconnect peer:F813D69B-C593-4754-A03D-1675EBF9957D
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] Session.session(_:peer:didChange:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C state: connected -> notConnected
[ThaliCore] TCPListener.stopList,eningForConnectionsAndDisconnectClients() port:57118
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Session.disconnect() peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] TCPClient.deinit
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
[ThaliCore] Session.session(_:peer:didChange:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for P,eer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9281573B-540C-4F9A-8AE1-6069B66045B0
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B646DE46-5115-43A5-B62B-416AA42,BB8DC
[ThaliCore] Browser.startListening
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discove,ryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
2017-07-12 13:20:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","generation":0}'
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F813D69B-C593-4754-A03D-1675EBF9957D, (syncValue: VNZyDlyx7E0hNma4pGLTo6rHXz5cNgQ3)'
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F813D69B-C593-,4754-A03D-1675EBF9957D:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
2017-07-12 13:20:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E835EFD-E820-42F6-9814-E20DFCA52E02","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
,2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:747F7346-E94E-4725-9519-7DD504D607E9
[ThaliCore] Advertiser: session connected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:747F7346-E94E-4725-9519-7DD504D607E9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VNZyDlyx7E0hNma4pGLTo6rHXz5cNgQ3","error":"Connection could not be established","portNumber":null}'
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VNZyDlyx7E0hNma4pGLTo6rHXz5cNgQ3', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier,":"F813D69B-C593-4754-A03D-1675EBF9957D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B94AF845-82FA-4968-A8E5-D060BBAE3A27 (syncValue: J58rg4SYZgQQptb8nzBYmatebbJkFy8i)'
,2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
[ThaliCore] Session.disconnect() peer:B94AF845-82F,A-4968-A8E5-D060BBAE3A27:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:747F7346-E94E-4725-9519-7DD504D607E9
,[ThaliCore] Session.session(_:peer:didChange:) peer:747F7346-E94E-4725-9519-7DD504D607E9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:747F7346-E94E-4725-9519-7DD504D607E9
[ThaliCore] Session.startOutputStream(with:) peer:747F7346-E94E-4725-9519-7DD504D607E9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 2, 5, 6, 7, 8, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (16425 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received (5311 bytes):'
,2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", genera,tion: 0)
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J58rg4SYZgQQptb8nzBYmatebbJkFy8i","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'J58rg4SYZgQQptb8nzBYmatebbJkFy8i', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5E835EFD-E820-42F6-9814-E20DFCA52E02 (syncValue: T5MaoUN,6Qj4Flp014TWQAkUTSR4WAiWF)'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E0,2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
[ThaliCore] Advertiser: session connected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57130
2017-07-12 13:20:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"T5MaoUN6Qj4Flp014TWQAkUTSR4WAiWF",,"error":null,"portNumber":57130}'
2017-07-12 13:20:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'T5MaoUN6Qj4Flp014TWQAkUTSR4WAiWF', error: 'null', listeningPort: '57130''
,Connecting to the localhost:57130
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
Connected to the localhost:57130
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:,11 [1, 2, 5, 6, 7, 8, 10, 11]
2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [1, 2, 5, 6, 7, 8, 10]
,ok 124 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
[ThaliCore] Session.startOutputStream(with:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 2, 5, 6, 7, 8, 10, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (12045 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (5333 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (4522 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (7594 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server received all data: jVDm6x8ql6X81WmI8D99GAEIvCwPhlhR8OlwQxLvDPnknCozjSYAsKmCl68fPQzPVZQADPFbk8izSSYarxV09PoCwfDzCwQxiTpxtV7jaMXXBiw6q66ercWyhX7sSAqmLOiCJYG3zcEzMRwKAGAdSBU0AeJen1IOu9CfTWAwqtxRpqFEGjb8QU9wyBZxsQPjRFOaiL5NHqYYbrhwGC4jOBlgc7yupvOgGA7gfUsa60BPIZMjxvel4BYwniCfJTqk4JnwyFgpsBag8cmpC2aDDAIbCuow8JjLeOY2ucVhyIfu9J6uJ2YpYpubFVfgGrKofRMTsZnSsYpQlgrtkcCkcfaYXcbDMEQ0wPNAnpiAF06nrslXqVvk9DlcUaJZgMVDTGFNnJf2lqV6h1ggIzXAo3jg8L8aqrNE5vEIK7Nw1sdElSI33L,oKAVTv172puu8YZcz8YeSeuAuoSivbfiXaaoqsVWXooMZwuTpZA3yhKK6jTR6LW6m0k8Jgt06Fb2WJsTaNli7v2UzeWb6Yhh9cGSuSB96DKRRaJrhIMhjXEIPVzzyDmyrMd4PBSiuCmGXhRViPs7nhqRNFeX6dh6VEW7fj6C51Z101b8yyCQP88LYpStoEbs7XWC43K8wKhyZR4HxhnBXh9eByfNfNqqSiWW5alTRN15O61D8KfQtVF7Z01DQH5n,kmge9HY8w62lWTvONBENRFj3XY8sGPfmIN7AYKwq0MeezqeYXRr7k8WiXlxy0yuXjhrD42wLpdx2aQVulxUjKBwkb61WPUlgJNCGvnwbNaXigmsHq1v30hVa6OjCOSqxfXKglE7lv0TAVoodEa3rZ0EAuBiAcFlFOpoDpRrgFVCcXpQEJq5zMJeS4x9jm8dlX4aTvA7dlNqwDeAxZKGclQyGXZfMCHGgEZ3c8HVNphVNoVzUHvgq5XOnLrTEs93M,xq7BEcF8H8Fekm9oXOapN6GEJKk24mlvLx8eKZgs9gBvICYtRNomGp4oBp5B1Pb9AV5Wmio6GFTK97I8wnR1uUqou68SlIIeEaYI0ICEf52JmH6wPbTd5wP68BLR5WtXM6t1eub9b0ZBkK7ZzrGUxNQMH2UzvUSkH1JvKnaGBhGG0khOTPfAK6bqNudu3cqkWd6OnFq0XnrHcRyAZx4Irk4ON8tTDrpOskBe7TniuqXdmh5DxLIwGrG8v0mMuOgu,xBNLXMXmMK8u9bQHalfw5z3KoxzDuMiCaoebWXDIS5pPZz5T7WgmbhCTXjunWgn6LtEk23wxD2qgY0xABivhzJW3J6SYO0tgRYe4O4cyXUxaeqsySpGhfCNhgDcS7kt4ubify3zSklMbSBmK0QHjyARi75bBjrWfhFzFQrCcUxVTsdtSY7NjjJ4QCziXT8Wj5y342WslQmAiY31AFych4Gx2oQqb6sQhebn6qHT6cyqEyYubhlNtzQLoGZwPNCoA,HSAPXIHZ7XRgozjbQHVr0eMTyo6Dgm1yFTdNRMZ05ttJ2mBxDVk24T65F07ogvbEU7wjkMaWhuQZVsoKK54cc6jhq0L9FMIq4onyPuvQczVuR5h42wD3oaon0hM1rBadlzNA70pxos8PVzoXDc6hJLy7XxuqGGLvaznodswN7SBXD5eXZZVgaVGJRAZAPFX2tOBliCEdGFjXamkNS1t0M7JjxQ53laaANXh2Z8WlcByGTMORSin6xizL4AkJMymK,0875meLEzuHzOw1alqzDFH2PmXucNxnhap9XhJY5iqRpzv6HFnj2GCTff6SlStvo9HtoG1PvZUWVvi4LGItk8ZEAOa7aWeJNXqnHGZ6qXMY2Uy33PuXryBuRshVPORkROq7uZtmv8FubgYXZDhULkgxgkG4JcRkIOVe1iTlTzz84Zr9Oo0tcwPo5Ieitd5XcquS1IrrvIDEqAyvT2bHX2QpTRxplOmllQjIiF6ofUEu1q6jYMjs6nGGeus3KpzU8,iORsm2h76iI6QwEwrTiyEQw6cb6J8fMMhpQiEp37gdZhyt8nP8IjvFoRm3iv3nviCczlxzrgjDumkX6y1ISsbZRSFHIP5ddwAw1l7Fw8V3X1bvjyDhvpkPMwUwfemQD69MfsaliEx90V1igBFhubakvJI3ZV5Wks5o8gzgHGg7fZycwi3HjPu5S5IX5mkpO6p9WP6O15hjg3gN4dvugNImg4VOBD5G5X1xsAPcjz4yGExd4RZL3uGobcPUSFXCah,RscuxW9LYfpSnLzp9x8Gsam0iPkJuKeMbUpXCUWzpvFPqxJhYZ0jFUx5DiJh4j66c0Mp5hbOSAQZlGPNXWSVg13NwcNUm9d0FyiZB6QOoPHIIHoNzcz94xlio63J1VTh0O9g43ggC0mUdXfO3GEu4YUlbe4aH0AZC0Cca7EFbqQ8L4fn0etJmsG7zIvwTf0V9mf3KdukQjzgfGnW1NcYkpMp2zACBMXTcpndZlD5uljY04ngrAiU9I9Bep6MOZkI,pl2V2iMLoFuGq1FOrxYQP6JazDp6KaQf2qsgcGz6q50xMhWwsZmEs3BhwSX6M0fOho2VpbOuS2uydmoNS4MeSAEGzFF5IIQgf1OYY48H8haJZSBLCupaJLNf0TE9R7RoUEizNH2sZT8Xzx8u7OZDqioMA1XvEKL5U0gE0pq3jBkjyyJSUJq2IYzdLHsdO2vGiNhZ2LKzZzNN46OQ5ZuB5kwezdHVa5yg0H84O98RTztyabIjF8Nay2EK9ZfzGrTL,rKlAjdBuAzdfryKXB8wK5IrQ1Hd7gFRot1Xjldqfr6sZUM0GvEM56PNTXBWg4zJaVzQSIIdvwmdZ7LtdM3GRM7eE5DBX67tIl8GV10tOwGMBrj4U3RYL2eRyaEKIRbr9ds7XrgVPiHfSn1IyKvwl1wCH1BjT7xyaZB0e1VYC76MF8Jo5UxhDkF2ngwNmxllKRGPlxmYONFEWcdO01aDjAP8m7C3EI83TYl4VlVFCW1GOKo8fP6SljUWVOM0Hb12p,8s6cRLPHS9g1HF6mejG1yVyJMbjXSenriqVXD8Gt3yTRqn3fX85xTfTz2odTK8nUmqsw0FC7rfH5SEW9IKbKEEmLY5u3xJHAXAVFEtl4C7rv7sPdCWXonx3fKWaGRjmMRHOdFndeipBONVxJni1zzwjzLAObQE2n5WrQpH89YI5ovufFPw8Bv9N3Qh6lucqJQqTzbUsZJcaYidC1CSkijsWvZXqVIwrawajeINZyrcYVLYacreJE6vDthg4GF69Q,cysEUXaqqYr3ynpppwx8p29DEmV5hdxcORxl43DV3lTSs3U2r5Rsbo09P0jEwueGLK8zRD2qNdXEdHiYtwgbMVmmGIEdPEjpnIiMmeLmrihF3aOZDfLBIcriwDCEf01SWSSRPAnG8829CR70SXtaX3vAaB6TQcZ2ZtG7Bg715wgwkDS7Wx5kuosQiLdVaPbEYtToy1qTaIXeaPMFPslxwTbvtRSyi8QNG4EEKt65to92pFZ868WswZHHpUDrXwfn,AyV4a7jrvEHuLz41oXoqLPiC3SY9XWX28WjKhsYcjfbPVB9G43LdVlkLMSncBBQECpnPYEcHNjKy6TJO9uZGCP2HWIzVDPCimtKsm8jlFDWzz0DhTFUIO2jTIPDaSz3d1QxaNviJwkBPmnNqBPdDmpvitTC6WDuZSznvbmJrWC8dQEpaKfAN7hYxkJ3W2CTlpNjj7ZxUstQj2vjE24mAam8XXNQiBkHTU9c7xSg01xM8hLn1ZPeqBmDwpC7tjnWD,K54vaUvZbFjS7iFRePE6wumtF1ulSQPSkISKmknrUZWMKN2tR1LtODBsDt4Nt0zdIJFZh0NuR3edSXZawWw99heKnE6TjRyVjopPf7GOAYJXQekJJoVHNO3sKW0PKa2z3LCebGmTDYJ5AYSdsBJsMcRxzvYRUgjavnAmJhUAMcGWkoeUotJ9ATrs0nsFAIbeLMhs4oGMIOklfpUxdpzBsCuKjxogswUvT0w1RxkuJ9cIXZ1qSHzXErEaDbZE0VN6,6qBgEfISAxJdaBIr2XRXG6AcbOWwwVZxPrFCvAz8mCqkoSpvBYB42AtXa9LbNuChGVpc5dROVZIBcFXgcBpjvIKZNjzAYEDs3XeHlPAz4E1TigIN4AbsMmSWzPRPTyalafLeW8yQ2B4C4knnM94byffrm9h2Yg0R4KtGTyfst9Fqe7PWUEiwhxyUdwQ5VxhPucvV8Ops4rudSyehU5GJ2dbhPmWIvGE0fj7ROfj6gG6tZIqqNyW5pdVsLXgFrJ18,7QFhtlMhftvYi9oi0uJXg5B03KARiRSXryQoEfrMRXCyu20OlIUJAhYkSLjF6UqBO1m4FNEXk7oZdW8zzrUKTEQHQiCDdCWalJHFgehen2WDxOFgXcOd1Q8VzD3tUQTo9nxVS1IBiqqN1v3VYVt4Pmfp9JdoWE3xXJnxW5bfTWQbm5WJkKTgVIhaFHnVLGUkezbWkLGw6bI9jpRgeUEIIirdiJCeoejB5mZWU6xsWUmLUGPY85zf2NKB3QMxlloj,z6v8KFFnDg596K5UBXRP0ctmGBKtOrHvelvBPksPkEzPL84OxUwb8x27GMixiwNjYX9zZSRuFHQMVEki57zN5Pv4InOyUGxudlGFic9LCg1ITlCxoRW9jrXwWFmwifgiW2uBzlG29SErAbfw9K4Y0MLy2ItTGfai8sxcSwdsIzEFRSiFn9VSDXZ5Gydg5wUxveQA82og5OBzxGyE3GaOUCQMxRFiEve1uHU1OyE1pYAP3rKdUHfCFTdKiBcSK1Gv,8FghGOLkmFPa0E2NzayUyPRzET026Ci5BUJ6K6YNRDS5Eb4yvCEjXj2lb8bF1onwLZYfEga7Ja79bZ0RF9CerhaEKpp4Eic2gJiEjW4qwrQltDiyJv0oKpsFZia4kbpNJzasmTN2JhpcPbu7ibQbCuQEYGeNB5dzLs0tYAUzByMhgHTyW7KRFcIALjfKUDTN0GYJiy6euldCpH7JQzzJJy4xKiRU5fJ7dyin7zxIPbJYWfsUJnSXXF2j5BZlztKW,F3K3YVoyHUSn8aDP74MB5AZkycF25l6Fc3E7lHKzZieWqELszrecjRj9sCF38QiWxFkQ6mXgW9p0TGegiF4KeSPAafM2N8gAOn25fOEa9AZsarRmiuXRX9zGuSNr7o7Q2vQ1BxRThSvmTyrlb166OyB7nwM74UT1SF0QZHePyzUv2xOt8895Z6D0qNlHgGN0zHLPNu5QoGAH0CV5Am2FqZKi4jgVOZxJ9fMc1murEwNjaZwq51QgbgxPiLJiZMam,LbdpcjsiWYC3D4GMnoUOaLuLDwedkp0YvAcvtLDLvVD63C4UVHWIl28nHMCIqpBomUit1inu97elWhHhbDtHkghMHwoCi12ZJAXAPay6WvJYR94uXaT6ezXDOP5iQfP7EY48Og5y7nc4pbvZsZD1N3z8IRUlPVhHwGYVtTqj8mx8i8OZQhX6PXsxyFx6DTnFHWGHw9AKWOd3jaC9v2Jo8TqjJlE2IJFZe6K3hlVnthj8cMwipTV6ddkycGxmtL5f,VgLcUXmKEHoTbbYcvzJmmF3s4OA5T1ubgxTiq54pctXRN4fsVehEtPcopRv9Qe3gYFSUqat0jC3R3fibLHbHt41X41H3zpMrq7syuHZSN2jqZlvqndkqoe8F6u9as34LQYIbqqoUFmrMFnWBAjFgiTUtY6KFU2uQFVZ7P4OeFgIBFoFE4mYIoA4br1iaUUWy2Ap5aheBX2wFjHVjrrqTJQ6uT98DPxZvtKYffM9Bn69Be6kB8Y8MbEbpvpe6twwV,B72Rum5tawxeHcjhToH4K16DehlCx77SLRDnb9gJCISNXswDcM5WxNxbtoxMkfD3N1ZkTU8Ci8CECPvJe280bntBlweS2Bpv2ePx39Uk4qIZHr3iGJqqLMCDwzclvkIEpzg1g7EAyDnJSyDjHKf8o9jeG2xkWkaaUoB1iBVifbOmZIdB1A7xWoUSP3jI5qVoF789zpCvr4LVuuHXE1f1pZy1QNXoFYCi0TRzdequgLDgnxpnQdypKygkIYgVjX6Z,IjgSmAXy6coyRjKlv4cTTNdCIeMqXnApt7rGSc12GmawqQBvzAuGktjicS1d4kY02FAaOTMxMyCkzBERe8PEFi9OT189hFNrMn0LYphFqeQYwk0RlFjezSvljT0DwKD9llKYfZUXC67duOBa5ReD7QPwEPwHPVgJ6vhHtULz0gCabzIdL0xQziS9P9AJSXtIGGoJLxyxlbTiji7fQsd29UaWlwNzdGAXi4PGU1A65217I8uKabkfhN8dEJBK6O1w,TgghDlT8Q9HERG1MXM568dFuNEtCZg8hS8t30jRkpeICBG7UucOfnwqitnTL7weAlhevFvMlco2V9bKdeCxCde4Gzgiw0o4HjE4daAwiVaCBpHPJfRqq1ssEMpZ8K0L1jwo1j1bXMCl5gBFK9kM5UKUCMyj0VvhX3Ko6l6ah51As8Rgt7IZmmgi4TGe5fSAfATApwjjjJGsDzLBUVfedU6Q1QGXEReIaLfeUmLfnc85w5zqCjfriEvcO3xtEbuS7,x3NCkJIZPYO0FJWnnpU82UObRHSGtAPQwtgKdTOp5oKtGm6U1cBa1ocXHm0KmGI3Oa7jAGQg2sKa1iMCw47n9oF9nZRJzr4QWC5AhwJWmjV1zkNNXdopwjL0h6JNja6RPAgZ8x0LPrU5TB0puyH6w3ZeJfInhWqolHslCVZFwFsSkqVbIyS7A3DLUh9hBeLwYw8sA98igXPqGz34vml4fke86ryAepEVHHPvHra5E2TxRSvTUDbP9kWDP5715xz9,xOTOJl3fVQYDSVNLiWXsjRZT0dx9jAH4NHPQS0kOGjzK7jLfGDnZ3H6YJqYvOTU0u6egWyWEVxQCQsHFYr6sQ5vNCeyJVcGg7kJg4HVGHul5UH1QAKrnD8bEY3leXPTdU6iTAXeD21ZARb1WEHVweXsxxeK0pXkZJ99fjz0JKVwRTTlPKS3jELYUuoaNqSMcqqBy16eCO5c8YvnBUU4sNnPdl1HCUNTFFMbIeCipFwWWQ4vCyA5DIF812tnw7cSw,YIMyzvx0O9qhw1dXUO2FJsHTdVbsWmseHQPywtXDV7WA5lzBhISddP4i2GZ5JUD5n7Ttbd8xoqBmWGFVeicInoFQChVMFtN2mdYfW3EDIJsyL48koWYDLsl8s7O9QI6HuxZ8rrnxzA85lKP2ABIa53tQ17CwCorRWFr77wpRxvysVNCoLn4qzUwa4wQqzq3qvsIqER1Mx1F0ZVcSHsCe9K62zNX42mNat5m1h7eKo6UqEt9vt3fYafMqWmWf4Xe0,xBC5nHvcWD5ZH94IrrEIBqQO3TybpFlzkIZ975cbtS5HLIdUgu3SXqDoMEG2F0RyYkru9XoFYf1vCbqwHR8WUlgQxqGQeGBVQbCDY1lsu1moFbuqPVkXadnxxbmCQDdafvV9m7p2gSl64m4FVWP9nbqei0ofkrC1adDpoiD2KOTNNidwvdsANSyHbdqsIQHCZ3Q6QhUIhnYHYWqDYB9RXQcEownXwPjL6wfUxXlUynog17ULPCt6y0AuuUFEbqJt,2zZrvp89p61mvdXkvhK83WBmLSKHnRIYOroMbMvQEJkfDxq00gIANDqjT21SwLaEQ3JysQWxfjjkeJmTtVYUx2Y1UeV6Fdr86Zll1mjuAT464fqtgXL9iAAubvVetJt60ZfF79N1V6ZwVJO06BX0bSuybd0D4b1Ca35m5Jd6QxQSvhPZw6P4KdgQi8qAHfLPc8rHs8Mcmuw3jqROBK0sYqt0nqAf9xK5mKwC9Uh4ztxmdj7pmrRZQpxbT2NHzPMM,MsqJ7Y0uvAqaU7IXPtXRl4ujaghxlIzGR78syYmtlU8q53B40AH6RvBAU6ZwxWXkWJCp7TlkgZwoYwOd5a6lvLXVn8HvipG1k1ssO3GtwCUgdWtT20jWZmZ6insCCAw3WSdUwYaP6VPBMGxTuuTxGw0OWH8sGZYSUnfUaZEB0NbbqIc5RaArqUS33xMYBVgXOZHqYy0Jb2hiDTP6EYQZ4WqDabc85VI0C1lkBWa7R93V6rwL2364sftnJduTJ8Rz,YJYZZO4PY6vIhNAKFzwp2wGddmTv6wtRRbgmWD25UD3lkkbKGzL8VOkRwgjq6G3P7LpcWvRqzXmohgksBL5XqW0atwUXajAQKKfHF9IeFXFigjdaFvuldYic4ddujZFSz4a6TUPr6uP9Y5LSXN7myjJI91ywOxnq6ItDIQbkdzwF10fCR8oRH9NpoLVoxzvyPNGOIcHUd3gbVV8CWAhU9HaGmizgJXhPqxgewOXsJKSAuWQUSEdKIZgWZaDWHUz0,5OZ3UUlEojrKd77y8f5QfBniNfT1AvSdQxS3zsffXXQ5mOUzqkI8ZFOHVM2rHGCH7Ivb6BtoXfqdjWMqmp0viUrcTLjn4czvwuv9c4lk8HFwgK8TTDhDgEx5fT0s3XD8RKo1jNVx5Z24w51pn6YckNr2vNaGfAUm25g26spbHqFSX2QJ8kCcipiTp3LGRMTmZN9UBiwFrUyPkn2njyvZg4RWlJqUleVMg6Zd7MCQgdnPlLSuDbapJo1PpFnNri8L,8FrK3cu6Ix1zOglAWG4BTUHIvFhesXtKXjP3K0ABlp2kda5pdVJJDzDbB8PCFpq7ncs4NRLHZJVWDCbMHIxFmFCjAnAo0z1oAZQPQUrUSY9jWoDq4R89MWJDqBec67EChtpHcerP2fRjZuFbyzjl25qL3QdX7BLgAoXogHepf9X6Ed3iGalXKzu53nlVhPtqsupVNscZqehlaMqttYNdLEPIYdweyxtVPGrvQUBdPrx1y39mgBL3rS9KI6L7ljeb,Wz1vfpAgtexhoVy4M7cHHByyIFobfn5uKtwCBKmHcAztfrcWuHt9SyBlsssPITXbHoCnl53GQChJ8hbE0VD84cy6W0HMnTlJYLeGoC0n53VtYODNQePIdf1xAQXtZ44yrTcTfgZbxmP2wuCpprDtD27uJKmuSoHCX05rfrYhpKp9GriAK8b5g8IN5SNFPEv65pueXgwhiQOKOqfHg1VA2RWUD3xP0lqpdhieJoOaOpqvad8Uhus0A1CCo7eNyPFq,tFmYVj6SG0c5c9hBYcl6OQej1PsM4TXQa02DuPTccCQobhf7OioVYNrQFTX7wOifRuGSB0KiQZ07lozPB8cDtdd4iXovFLMVLmbapOaRpEXTFgabY6uVCM4ockFnEx2urc2BIJKbbBq1gH8xHHN0uIUrYHhr0t9IP89OtOixKswMOugBUk3tcqrknriWH7TniQPOH9PNCQIc6BaJV7ZlgD3C9bti2ntxvPntt55f1e3go7ERuMWVzFJp6Von5N6m,JGXcqFoedMiCnnOQ3HKvQfvl02rdHJixS39CgsDm53meuGLRIIsD448kN1yZvDVgkvFJ0kZDdjhd0HshTpCE2K30ewfoYhf79bIPWsxowywQuS09dvuBvGrlHS0e34QYtJdbUYAGNZdYCZDlqeabQjdjE7lR4ch6FXSnv6qltjOOmKdGsLDGLKK5w9ITKhPxlBy4hiHBGR1A1x4NHpPnLN74dDG7CszL6Mif1xvZa89Hu8toJuIXLHG2DzPcoR86,rEUWKP5XzlIhWPwfVRQ4HXWe3UXXFMj23DSOhYMRQ56haf7uiRJW1E8tds2KhLmycqHs6wLLEFZl9Us1cBmctAvzCAAhujIcyQgwye4MkKBu1DoT77HloLRJ44jjKxdBEcNdhliPt4jJ9X6pxXHEvyD3wo3kPmwr1kJ3g7XangDGrzDVUDqiEGuxLwHXS9CRX1TMa2Yexc2wcaOyr8vwfgDSg7qWr8qXZ4r6bXn5qscI0VmP4DhDhx0RISJHwFBk,q2mW5sdlXrgINocHaih1qNykjeEKILLOtg3iG6IFPYED6e70AfTdfANcdQ8XrUJlb8atvoxFadycPLZ2Gk0hyva8amFqUvZ9kJ2tPc5GkTeqXIDqb30CGNyMFAcZipuUDN6m8MpYbQ6HADIF2K2hUrnked5sooECDZ9BdOgmNkCubqgpzaI1CfzLeql7KSeHHXEF10eRuh2iBDlUEnF8PetTXTU5E1t0RTdtu70UuzFfbh00OeaHUeO0I5bjplMT,U6ixfuRf3tsFfHYyAASRybD2bs05lqGvrZWYzdfg8zq0CAV7SHqsyNR1OqidTAWcbJoM7vWCZq8H0hoiwZTPeggpdS2yF3kU9XhUDSTqGTa36lK0ndr1HFRfDFJis2uEaJrbjMJD1dMmIDYwfyGWcs3sL3Epg9aK2rra2c6kYB3riEAc6WILeU0OtsB0VX54uoSqa23ZG01Y8slqSTCU4WuimCpSZFTGuITsPilk1CzJ5iUKvneXJolSw1S1aC2D,5bgPaZX28PbNw6N9B8VEgjYtxVqpxmWMpKDzEyZEBK7PYmDjNOCZjNd0WBPQREolTzl6vAhJ9loJZEjAmQ1H5G7g7rfABsvqA1QsMEqK7Tl2fREfd6hhXMXqWLAyRyrBMRw6Q6lS27GXt3eAhbHMyRgzm51N4rstysCKlHiaFNcl7O8mttGbOZzqpiuqRNJLQT5vDhiRbksQpyfHcEAH6jNnBu9NJm3IftLhlmGm41fMnzvrd1Ucdv9s5tMVsvj4,2GHmGr4TLtLjkkZG9tVHUOSmoR5WjfCdU49yFk2hBn7dGRkkzHHxWFQgg4Uu4Z6FfkZL87X7No1VAOMcBaUVM6KF4LOVlGnYeohi0FGVZsA2y8BqB23VCxNVhcWxoNZN3gaT1qTSA24a3lJNu3qHzivjUi3ORXnmTebKEYCdP8bohekfOCKG8Rx5B3v2s8EeCn8ti3AVzDciSo7RXhvyOWCRpBOjQfZen9BUViC83ACYuIaaRq44DU9ret3AcrS8,OMWOgHlDbEWCmXYGU8dKDTj5tZlml6A7i3EJ73Q98Qc6AbkqWoPaPJAgobZIYbjYgIIEZPCsmuKvQzl6hOkzAcL3PxlFvr4QqJhe3VtLd7GKC0ChNmvRg3JynmV5mxtZq6BzVbrSyH19vi6uapq8ccvO84u9A6roMkHl98kZCRdc7VZ3FxJkKzE6FpZtg6eDh8I8Cjh7CVCr1z6lRddupp9cu45XhQkSUfJt0K5Lx6A5VPYTav60DYDnL9PnYTBu,rCOI83djZvnUJp829XcijnTqUIRslT5UV2yHI9Vq0gFuXMQLGBAEsJQWXd2vqLwZVuDzEKzfjGuo1719vpcPclQEYRYiE2nERTZ0LQ0r4iPqZQtABSSRoD14FSmaQWtQo23WtW20l6wEXOH3w0YRR66OnDs3gDzDXridOEMdHIAGqScvljewqfcmIKxgktFmKN9fXMK0MojW3UK4mFgOxi4iV0mEOVin3GX4rQAutnNVY6LwWTywcFdRRZx93SdG,LIa10pDDJZ7Ih3T8B3AflabshgDzbxKu2R2qgs0jfENVIk9zhWhqfGxbxeyCJ2w7zGMoNtyPGIyqJNgQ2P0utSxSuMdo9aYFtdLP239tiYa27X67bmjIeDadGSxwnu7pyeQUlmzizBq0SEuiA3K2n5Bzy7qHZbbqDSyJzknEgpvzVeaZxW4Pvm8VEf87X5z42HyaGHufYs2dhZdaU9cN3MRiEnTXIReR4A125DZBGdTQ5uC1fZg3riI3WCC3vkmG,PmETL3x2uvr0NP8NRDYKgGmMoH2w5Fr8B7peyflVgDKDDoTmYcQn81dEjUP4Lf0IAGb6QMd6BsL2m42ZjpkumRi7qirzLMQReY85EZXnnrTm8wC4xH1ssFNuLNwySfNiIjtnEcRQ765yuVbNEzsV7O9S5lUfKlsXPyhkSSms2xwAgaIjh1Oy3ZyAimGlXkPDlhD0FvDVsfc10oAXSs7dXcTIlR82GcoTpEoPl5jrjvIG2h044D01QFVXOoPj6QJE,KSRJfXlYmhMZ1VZToNYac9D2yLQA2H0AAALWfNtIC131h84Zm0tOWrofbtXWnhprWvySTpxXtjGrXIOK12urAVYLCoWLosW59021pchqf3i7pJAak3PQCAbx0GnwionSndkKhZC5oWwJERhUZmBk1H0aKZ60qZ3JkMwpTbkOajAfs2JEMina2jN1X0O5A89Bpwjj0s8jTyV5XBtDSYmRjRusMsbxFxvDsoXeo4aaci1LF9cHoMUt6QjdHmT9UI4h,c0w802KKsbzhY0HOwCqkSVawNLkQvZJgP15Y2WImN4fPTd19vbfLWOL2Lzxv08XEpMmTfO8d3g7C1wLlQaXZLpeNnGVpVNyncJBpJ5EkQBZc1UxKydkhD52YlawD0I7DsjtxAcbAIXr0vDOA7CsWPwMzS2aBUWxLJwwTBqJXieruozHazpHDBCMSVpgVw2nVcjByoTFzmU32U3tKP1mj79afjrJGxOt5m722CIt9G7XUFRuge3rS9njshOhrEP7D,Pr6J4aq2sAKUgngGXGLBGXV2hjxIRAhIRkQEEUJ1yp0a0jVgGrE8Vz3GBrJqMaMqYoLE8BbsXLHRKe6m4M4JuHpSfQS6dJnDCiTiH4muExlZrLAfXrOtU6y7oF8MPkGyAliLIVCCcOhz5ygzuXjThflfCoyVSKZstzSUndtT6fk4YLzGplj8c5gB9OUZPHPToTedDo5oNb9vGy6oVf7HF79HSEMIIZUzUMFdUVYSyYcI7Z5b57vl1RvQt11dcbH6,kaIiURXjjMCDJBkVqBwD6jVKdgs1qP0h2LbcrTNOejYx6JGpUazcjIZFE9YnsV6tIubGBOSl6W8YiOmyUZ4Cgd0xt0bxBdgtTqVFjPNsSEk32WhHjFk2m3LNraG2UHvUstppbMqB0AhbUTUSAoe2z84z4BiKF6uVzC1qpiq8sWtbhiLgpclwKeHbpTYsY9vvfkaFzJ27F5FSDRotBH71uZtXZApBHTloUkMwJBXMuK3dw85cgNH5GDKN8Yg4Lwbt,FwHMb8OnPaDbMMwsRmmAPJeVgnPE8Sy62tF8PKYgEVxBN6Iu9sJCCL1R0AedKxQsorBA8uDtDctLFy7nV1wCfWvG3wiDOLSMVzCPcaed62YHGVIBtanBgkvpu7G14Wif1inoVOWjh6UV9m5c3jyAaxw3fLJ2faI4kGOKFygk2aSy9yi2WkPfjy09Pz9Fp2LGC6Kv7Hz1XRul4uoed4ZbbbMDMUOKMn6O35CkxAV7CQWPuc0qTjA3lNGnRisdfQnW,TFU91tWKKXw7270e76uV03bFehLEp6Q8kYvyYBUVWQdd9CZDeeEOaoxdrz0TnAi8IY6ubbm4YSFGvaDJHp9RGKqQPIi8hgXUxNAELemkwWcjfc5wZk14YkDaHBaX8Icbg9eFrUeMKar7UQQLJeqE153EsjHxiggRJZHe6KtRToriRZITuRdWZC1G423tPkiKf5mAXHmwIWinkJ6KyGGZwoWC9tMKLO455lq4BXJElSPcZR0cIzqANMgMgeTlndHo,CP9Ihz4V4Ez6b1PwhLGD0ArU0goVemmc1gbSaUrOkLBO4Qm3WaDdCFB5vT1XAAoS0DbwdRECjqYx6uuvM9OgC44yRw64OsBNt2Flf4o6CUCxKKqbIDyRRrzfknsV0bKkDJYyKDv865eIn4m1tJt32VWPcajoc8Ai0dFFYck6GqsnZ3orqkERVpiSPypDpSZDj6U3kImWvt8feW8w3w17jrEzkh30HIkfd1WNEVVO7sjmxWdh1eSfRwk8eGs5T3ey,geIdXyHTK5VHrcD2UarxYngRPjlHiEPvq2xU1hF0qX9PrsiPHXyKka4GN3w9Af3dtEfMkSmVDVnc4pyQNwSJsTyF9e8UaxhAWB6m1y9CdhzHZ8mp3S6d7xeKT6Dtp6XseVNiDyDmtQAUwjofb2d68ouHLrFSBQimMfed4u2vI6Mw4JVuqwcTHTXSjtPRHvexvYzCCIwn8AviofrKNMLz0OD441kAe5TiNJhREVkbiJmQLA7D30iiwqJZoNlYkBg7,emy2rGOGlx3AlKEH2TJE2e9Tj2Qy4ri5R02BkLZte6RuI5LqGiSVS9Zdms2W3slPqeRnlJGXnQEpAZ1kwSmXyA0hvDFIWQn9CiLVmZXUL3aE5jE4ylWdkJMyHUOZet7JY1bKlXbp1w8SU4R2zrEenQMHygxkFgAg2wXMpOSJS1GDPuD5uDe1VgLJaVXDyzThjGWHsf9oxpueS0sUK1X7FwckgFSrUZj4HjhMnyUZMeHjUWCGJG5YuFahD45BV4at,r4PVpp3D2tNXA1LG7TqqOPpm9yQq7MEHMovvWMQwLO4HCt86ffmnCCPENtXKNxONocZo83KoStntUHof4byBZvZfdXyemCcxoRjSmv8AareekQtNTNL6IOa68zt4krpRRGKqSbCr2q4VHu6Emddz4Gs4p7Z5lKbDQDg1Ha6v47dxkARDmTvbJhvAawILx8k7qc82unpUIhK782C7dKvXvyce2QxdB1hpCj4lxkATDIPJqEszYNutXIICgBdnNNVO,ysa1RkqYuSd5X1OTWGBfNglREQCP6dCYTOKn00SvKponRiQszwgsPmyTT0keVTtdwqLsHrHEFW3AUSrAJgnwgp0Mru0FbLL5tBIyILefUHzv9mke3r2uUR5LIdLzVNU5mf6dtl1QWu0CM0TKgGAtnsoGv76MVFanpZBSdOBAFsgU9HowWZt6dU8jpZc1vUkcjB7XooSRwVrmwxbJMwZDmuk6eRkNL5T8dedBkUBoeBfC7VVzJ9v6FvRn318zuEER,lLbZFoUqZUNUtc4C04YiwdBjmahtgsWOuok9xRhdS3BLqWZc0AX0ttytseiAhxsudye8drFhuqcdIDFgwQgxxhDug2rc9kDagpzupEtyqdQBuAVO8saoNs82PN4Utf04djG1RdrZxCXU8X59lI9TPTq9H9Ng4hvSRRgFWfHYp8tIsChaeWgZ9AwCAiqkJaCzt3fXsgCIqsepkyC1cpezWxAr3maYJbs7DnvN20Zo4x2HxAdERsceZczzCB0V7u3F,kWbAGuWls5uJjr36vERTJ7tixGl59AFFKUY7beliT18TrASdaLjCoTMRiTw4A9Q1ivUwjRgd92J8At2d3k4sspCgAwAH3sqiZDCkJO6GCTqnbqM1E1fKaI2xCEKxHCXbTV7s0UFcVocKdXcRg1k3j4fLBI3Glu6PKpz8Sl6CPrKVDnPuMLFoWGtxObopRG7s6ieE6IO3bRLglQQRPgSzyqfyCTcdIWlhG13CGi02mWtLhXDBOQ73T3X3frSxpnmu,YCEerUYngT7d90ZQ7XNkDJlwzbMAoOj0ucgg9x7QgTiuOb6FfbFozZe25SzwPOtzpoTP7F9OpkTXZid1kJB7f2HD5iVb3r1oHL0wDBGlGItfkHkoxThdxHUrmQg2UiqKA1wVVEqLjNB6erKNXwHnyGQ9fOc2A5FPimwdeXZ85x9eqdNWxhSKkONhiS1aqkQV8uMIYiZ0fRQV9KgjpZ0dTMU0y9qEAQbaV9mIr40UYLUpnrwZUUETP4Ifzd1B6ft1,s5UNHg9CYlhGkq8ZANc9AlFJfj51lMOifE9eCoLK132VVNgrzwpAwhD1dd6kbQ0Xe71o0hgEuuZhJtqIpTB5FmI8lVAiN3o3MtRpUZVOIg5VQhzW7VGVfc6u1WpUCApAyDYLbEO13vk8TqPFd9o7VDIqK1cufPA8MycvZ5jzrHXm2d61qpN2Q7ITzAmYUw4HCg5kPhgTplyvVMw0t5YpZeKj5tgEZJkjEloU95n5IwYqjFWN8EcAu2r5NOVcxTvu,fVVWYacHzNv4OLK1OEACWJiL06oKaEAxYCTLR2Xbj1B23qheIACUAS5Tb2Sfm3mDyk8ZTCNswT3FpnhiUXxeg9Hso6hKxCtvDkZcvufZiMlbI1FmDyqERluR7Kn9NS3ftJRTbEzmBHBwBZ0NSWuOFukRZP02dEiH8PYaWa4W46j4GodqtiyXgpj5sK18qaDhA55e8FqPoCkjcsynQELEnjIuw3SiLrPEv6EMLitJgjFHXcgqysTX0Zwux3sQZKvj,2Q0TZhmdEWKbj5XhYG1YWJ4WMXMSrthfF3GlREdKO1dkXUqXlmynuo2dls9WCmhnU8t7RRF5KhY6AkxfPdhKgVRBraIjq6xdC2o41zd0nJs3ycsbEjD7376cjklizn4ooG7BagULfHyXAYkZub7wP6PlLu61i30t7d9XkelEuvQs9DZNMi7qJBypLzBnzbW1QdqrbVzYzhPz0QptPd6b0yz7VqVcS1PRclftsDiyEqxquScM8KTlv67Iv6KOAEGD,VmQx27Yp9vT0Xn3q8yJwKkh5GQP6hvggkdQkelFT6rsUVOVN9VRGfpFUYCbllJq6rXfAHqLMvMYAE9i0jySiQfawSUKOODInqxjbPfNavnsShCpOR92PhlIaqDjBwrFalqS5rNYPZHA1iyS0RHo4O3Cn7omMf7aNOihNdu9wYJZiQVzsKFJdcAFXbKdybA0sSsDohL6Mu65elDPhYdLk2UXxBvq552mYLwxSTWjaPm5eiqclgzqGRMhbN45nKKvu,2LdmJ2XZRy4MHtMqmdWytY6Y8vpCEhEFpBDNfTM1pBil6YEuDIONLCuiuwOTpgM5tJ7ibvgGWLEnWtETgyJhRArNM4IcHVDL8ZeZMNmNoILRBBNAw08uajwXRQJ5gMpoeL8Xzj87Vle3RiH7YfsuCyooPGKcR2l9zPGzzWkscViNT4jhHbK1l3w7j7WcrBACzeAXCMJkezVHABH3CgxZ8tamQJ6lCNv4uN1ABcS4sShgqhWdonAdWIJC8mEnO6og,O1ZPNYdfL8Y9eJ1c7hXGzrYP1p2Sbtb5FjLw0Y1dBfj5u3omtdCbY9dn0uiHDTSFRDE7Yu7u2FqmoIzHdBY0n8OpPe4HYEWEM8z6DZwzQgXT5orC4e0NRY1bT7pnB9GmULwbXMAWOQcU8aTUhtaUaLh2SLRVdSs2n0oRxns8ZvZPq1eaHewluVOth7hwOtO1uEviaqouude0dAvX94JAvs8j1Sbgt1wyAPqxtfiCOEq0UtQzO9gK6IaUXWZ4edRl,8IEGh34AbsjQXZnwlNacXbx1YkSooxNg08JgkaId74SyAhEkCqesyNdDTwTIC53TZs4QaHuXEGYGc74Hjc1xQzFIE3hgKEveB35CLBjKfKYUcqHAtmArfE1YdEYI8bSzwufhzrafehdRyxeP3cHhuV3ESf2fKyzowEOFPqpPv0xrbCDy9HrqQnYsLaSxzAWhyXjSIeLHOPZ3gRwCcqBZ5R9yDWmK8JFXY1BOhX681fKEdsbmtntaZwvKQuICuwKd,2BwZHSShujZ3BniCI07wYjKxd2zo3zN5f8D4c0eqzNmjvVuFCYrohPHdWAjDia8Wi6Tgb5NwKTYUsiQn3OVtVQLhaA9CbAkZqRqtT0euORDeuDzhPfbulr78NPOuTdS3cgnQGxvGb9CrNMbfgBpDjCsmiodnAOvr5pny4AohdEWcTxRvVD7l78np5D26ZLm0Apr51EmjnsqnavHztwoIpsa7jnLbol11a3a0XjJadfrgs7jErfFbODdqBHra7OYn,Q0Sc5CCGKA2Mc8SHxCOvyvU18zMK1oAxksJzPteDWG9AmvJeKXfx8JBgmWj0E3iFEVfipE2ZZtbmEg1HkzN72YfKmDQ4zVPKRAzvBnoyTAJWLNUXd90yRhlgexQlDqByUuDvawm0WVIf1QLBuNw8V7iQhRkagrm9CSotVAHQKm3C6CaDkRUk8WEvAO0zeD0twyLHJUgdhHepmb5NJFciBh99YMztrvXWYh6p248uTN8doHi4oeZYcpExWYIyBTGI,R7G38ULJ6xCAWfDgyHFAZtyPY1MqImKwpiqIVl8LeNsvkFdjJ6llSSvXgC7MUvYJcAUqQsWZsWKK54vk2Rpeb0l9uCBpym28H6HGGRbaoxxuoVfAYIQBRkCGY627fZ1LWWn40rplpsnsTGDfnCZmM6s8Z9ecmxS8rQTDI9IKUO0u11BUISaWpNZvohcmtVeJsFHBESUhzOftUovYXoWMiQMkB7YM9CKUrBjyzWrmo9DGqsmjMStQrVbw7ypyRU2Y,HbwHFrLWBKq5AaLQPpjJ4TRasrRQOqOdFXEOzkCGaUyXM3wbssNcJh61wzMUPZwWnFyE3UVGrFB43bNQGjz5aL0VQExbkKmEke9X9Lyuo85ddRaxgN3Cn04aQmt5X7ktr9JnlAEFPgpVhnBUBK4hrITpihNGmnlwERaqsh4mFlWf9lA3IzFIApbP5IIhjpml0BtJ5jXy8hVHwJ86VITt4UAnKM5wi7m9MYrMFrpmc8YA3qkG60E0jPN3xXghYZ0b,SOjbbXt7YZTHD423FVGiaeGQOeJYua7ystTT6VPO7Y37n1MEq2lzQlyjMxDeMkuDBpmYrglEg87oORnvx1gHjkXERF4mst6v1hLr2kp9kYkQeiWDWpkXRgYZ7NdTXBt3QJ7n5MRIYxPNOK4qSWLtnm8K1Fr4jQ2835kNi8kzB4JAHpleM0yG7uT9QZ0l0604ZGYIDPHUED0lja6VqQbN9eiIAikFnUneKtlQpc7j7pJHCJTdYJN4jGqHFgmLf7W4,6fkJFIx6y4wDpdH4hb9zGcnYYv6DqRMcToK2atnX7XTvOloHPc6LqCKUIkLk1aYXt06urBDR4Qw47R63lQs2lHVrONJgLqMXpE2k9KwICJG4oSB7zfep4EO2T9JNvjzuOHwrfE5viOO2umbFxiItp0mw0uaFlVUS9qhqmEgm90FYwI2Catjkg3EZ45GTKmXoLYSh9CC1uZIoRSEXvJZ7YeSn3Ri7KGDzb0FaGFOXdbNhcnu4iFByeibixKSrrah6,HAEYX3I8P9g9T4SP7DB8EwSVEQr6euwnyx7s3uuftmJjLyYNKtOqmfghhPzwbGZtIH0jBFlVMZ420lymNlWtLB4GNtiDPwh9HsDw3HOUVIH2x2Ebg40UEPtShk9peYqO2u65q9ePPHymVqChoaO076qhpefeD9m3VjLB8jAgbyTpgpwMswzYuHM9724a7MVyn4Jftq0iQyByJk70IZDGazZGq5xNgncEngLbZCHsINix8i1YPnh9q5qmEsgiRGVn,3UrMxYJoLvg8WPfGZo3z6JOLvEopFNXaMFmTmDniBsvimMXF6EiKDWDGV50SHvLpnbaMscrn5E4fT2T35BaGPF3uiyBfZw1vweRpg5Jx1DJmUAA3IOkNWh1owVIhu93p3YSwuBG2D9b6c8ReOpy3BNbi1qNoEr297fo805FToPfYPUb44ccQRfBpI5X4X11YhI9zmJ3QJoZrnwF4udakt07sGb2NpvEShS3z29S3HFPiBwSKLt0NNaTjfeKZMvf3,hxTFwS0CQtW0GI6MZaXcNmN3Ahy5opVrMk5tG15FPZ0zaIPva9boqr8pkSQGAvpuMm6W4QUJYWOCGTHH6lF8fPFej4UaVm0hKqWbJ5Ydl7FxlSeWpBt67rHO6GSYJkwig1MfjjaMGQGWouZT8Ca9rz29d3WgwrSZTEkPBhtIAPxmiWzSDtdk1j3vlXemobjIidBOWbLxvdqyV1IG26wqWaYpdIJaCk7MPYy48Wlu9fNxN8dqgCqbfnoJTJYeFukp,VK30p7BWwPc6YnpMD4cNdJgGtIU5c58vLPInoTjQp9WUdbqOgrac3afT5epUNxbIkT70yYiP0GGRS18FlKp8oISbTIcX8Jxm7ZGl0k7PivHi9VzHsu2s0IAWjy7w0Ke8FSpu6tJxIvQBdevI3ZujsNY80xuUp1S4poeEvQZZhP0CHiBLD7NKB93k9L9JKtR0BoJbZIBz8UxRhYIDhnSaQaN662v9QEpiBZRdMNPzdcRYNeHOAiYNmhD0teI4xRzp,Xlg4mHH0q6KNfZEhJ0faNyrSkZs0xeWNmByXPbJWA0EvjwEbflQu0531xVrJNGi8WJJdrr7mQqpk3YaizFkbsPRDGooBVkpozkMI61zjIzyog1jmJINP2QLypwhqSn1KxbJm4fJqEPpTuKXqDXAJV8AzHWF6YMI5A7lPzo8oF97fH85BTP5RZgFUscI8BaC4tihmIkeTC14udvpytOvb1HmDfKIiCeNN1cs2DGeERuTbglfrrHunj0kA8zcXQ5W3,DZYuR2hggBuW5Bf0mw6SiH6l7iM6kgcWtaO4TTj3N7TkOMvTCaeevWZi01FGatejjcyKuGP1umfW6c2lseCx5dIH7GipWnn4rGlezZPwg79kmpY0u1o5BMWeRqEd9LXeQgBWTqp6IcSYgxa21ZqsILhVgsldqaSPC287KUJjkYT0gAGiUk0QQgiXg0OtBwPfcRpfzSudQLNrxHkIvGDPpusyB1Mg3RLKs1M0Q4CSdEpIxU6mEUp3rAJ7jqG2AFxv,m62XwjLHlUAeWNXitsAvSsVuzlayGSJEMuigIaLpeuIF4SRPOMgOgU4VTuXaEctBUc4ZNVstrTDgUC8iiVyyhohg17D3zWHS7ip32HR5A1LJIj5wFO2MUz8yZZBoIisKcfbm7uQd2oYGiRukgyFgR1g9XOsLzPIIT5FNVVLxPq7H7Z9qH65ohtKTdU393Us0MlrhyclRogRt1oXfUwQeZQLag0bDrzOC6A8stplwE0nYo4soR7FuTdJvYF4HyCD9,GUJaFTjf7R2l5DiuPVdOgmbDXEhvdXI9fj08qv0an9Vx2IlhUmAmpvmI3po7VkuNDNuwu4YveNZS1zO1sHmGvTxfbDvMQT4Wam3tRStjzDmIu71g5wYz65p6I2nrg7A7OqSCunX1MW7SixvhfPEtL8mZezH3tyB1Vp615aImyWsW6V6aeQsky8Tk0jjLqCCMvIyDNCed5qt19XX8ke8zjMISYQHYqDDCAKgg79X6UAqYjbx2u1sRPwBA7k9SuSfk,AeZXARjaflwVfCs7CAl8pDXZsk5V0pOrN48gpNQ06ztLad6HhvMcvzDN0MEqLjsJJUquyLWpC9LaRLIWINuSwv5w6xxy5ExiOM628n3q2O7rFUkLDCIHPnNhExpwEUWq67aCcU7587Fo8qqEluMqMAE7gwkzvoZm6tSn44cPgB4oESnGHWhXJtellpDsRw10QdsRHR9iESp4FmIc1pW6ZH4OCMfL0mTTyImFcqgjNr4l9KchMTf246D5ntGgdeFZ,AKtBc8zzgbmmtQ7MKNfnK68pgpaJofbNyfeq4yWNofd71Bn7cgz74w5GbvKc00E4sZY9oPSTnVTkf1Km3UiybKDEJepFfE8F1XB1C4HKVTbPEBe0ypraWoKmVX8Lk8zTwK2ZnaojLEViHjaobNDo6g5XagqGx3rjxN7LM5N2qhtUpA3fKkR7qUGTCp2Q1x8YiVdaMQsdFYz6hUNJZ3lpNXmw81Adn8D2VSi2uO7MfBTu7RRAW5E9QxIxVvehR4Hu,eAiMoW6PmeX7lE9IYDblS0qTbocOXJDAKyQyjeBCe3d4CJz2zb6VL8O6jkb1YYAWkxF72sfVSMvyf5sHWtJjMCJ2pM76gEYnvkgLvPJar7pvoKlB4jOb9hkjviGDTCulXZxoP72od5rRMNlMrsKUK7rbrOYIjR09FA4xiQJuOVWUya05j6NwaLZUAJ7v45XQXN9VKpUxQDMnDwr1T3GKVzHh4E0uGiMw3ADpVwelKokxSbO4ciZeHuqMtWXekFbv,VOFZ6TTRNlF86ZrRGO4PvphJ8SW8L3t7xgdnjFVnXkiwT1pxAqTgODaRklm3ORGH6SNoIbeIhHAPP2fEg3ildqAXPMJGoPTOqnae4NDH8HUhk4KUXzToAaR1uIivsV837DBP28H34McsPjp8KvbkDd1fdo1qTNX5NYRbIpBsOL48Zs5QlbT48R3O8PZ8QTR72wbQywGPwf84vY0eyunFXmvRuRf94oxHrSxGmVaP3Mw8x4XmvFvNiUjDdztVcrEb,roBNxPGJ9ltAXA3YKGb1HP5OOSaH38OL3zrX2CBvTeEZ64c7k1A8A4TEKznIXKTulDliExqFj7ustaWxae2gSPc3yaboM3PCNjnu9xqNK9uXmYSpGc4UBRQsfcM3HX8fAD8mc8neP8aJfUYuPZvb3ZCXR7OsZlWvOWJrNKrH5ZArfl6RxaBBI107SHtUDVlPVY1yHAOu5ELX7ygeapORdW2feqqNqaQSvbTlGnWbglpnCh6qkaQ9Og5D0MJ5N6tE,0IAM4Af7UfDeyx0sjm6IIO0ETD7FVog7UeUsWjiYrZdPpOWBOrP8vCWS1SssVn890vANbRoklVygY9HOPHp6utK3UdC1NstmNx9IEpKHQnJPWWJ8NngVMLXAsXpnpg4tJs08vcRx2Z5YMPqfYRbiohXxJhqhB5ebbJGVFKoQgmLxEjB73cVkDmtCOmqcTAqeit5uqdf0NKGSbLGsTBEiOXF7kigwll2tROtbUDNQsoFUZ6g8G4kw1ZJO4F5ayaU1,CLyafTr8nAw1XsNf7Sdza9qv4jKIIIwbqks27z3vPa1pPu3MX5UCOlpTxGYFJYw4iY6VuPCcVHRyBoRuDSWSCJDXKA8x82sVxymdtstCMYJeEW7bzPMOoAmwFj9eeNHNKjlaAfBGBWBbNLmRQvShbUWh6fa2lKwl1UhJLoi7sCPr4nRhVafBuR6KDS6fe2QdocphGS8FIUwbYp4b9droLgywv1tEWv1RzVI5NbhfopDLIWnJdyX1D5eJB9wzdJVo,qXue1oRjWIN8XYWuZOOXUXCDJlbU27bCX0eCexHmL0heMKS9duAEPpHnFr7AqLSgVr8o4UV0E4JaMP0VkDPrBiR4SlyeG2zplFClj4nCwI1W6lsLZyxSxXJuVR1JufTqgvmRR2OtqEbFip1G2CONL90M8Lio8pPnYSCXATgGDLMxZDUhgLV9ZFCV3LUbM69ualGwZXzYTctUmexrX2UhQefDhN9sssYsnIPrHGy9NL9Kg9V7gp1TlHNXhdwvx3Ek,vI3WuvXyQd8uJWExqZuwhruwhacuzJkT1bNjLU8qFbmGaUGOHQ7aGpyAH2MpVuPQip6lXg7GFOQL8FFMtLV9y6GFxhtCv4fQLijaCpSuQVdh24KLcGEcPatIIw2aGcyYtNvmDJbzGiRYEwoBB3KE075pnZKil40pk0aMqn5aJzOFqbdYchwQF5OBAfyOUFfxXDnxgFqyFmeWE5TdNVtcJEjQNqYXIEV2J57zDsvH5vf43MjwPjGgcmbuUnslcMTM,z2b8M86xwrSfX8JEt4colpDGwdyT7jMXRZOl5fFiwWkPpZlwSCV9CPKs46MAPv1dGqKCTVb1msGR0nwuyKCSFg18nczF6mLaGxHLmrCVAmPzLbGfZvva4I2XPBB4StczWjIT4eF7WsbiF0DqJKzfEkh23jB2qz7WLQAqUPNH2Ae4lcZMPKACFSirDxu1rfBR2lCuQKDeco7ONHkJRISNdORBQfJFZQvGikhHjCryYNZ4JhqKjAKDTL58dCOKGIxU,FrN4aXD4TDYMDFYWAYwS0CMRZlxyW7O4KwT8n8b7AMcSJGp314zIl5rdUxIc4Lni5YWqvicbol77marWhyjU1893bLvXRKu3c5gaNY60yDsrXMedwM8Tv6kPSiHIZVwYNtWCqAqNHDt76YgQsHxlHIOMFbKwFIXz5QKQztlqyEivWcesSUHVkqVWrmkq10p3A8TxxfQeCOquSe2LKH55LMk9aqmxdLWW7I4cCEIp8gOfyRGOIrZUdktgquKmEcQj,4A2wzHfps6nDPQD6Er6OnCmAQnuV40s2TZ5CJhIThzRWgUXwnXAYDviDtVKFeE3wyJFTWASHycMsLfG3JOVBtbOQNalaxe78013608M88DI9QLlnm6wIg4kXYhq48ywxaA2GjLIXInMff72IAIOJjeqZYvc2x6f1DaRlaK12rvO1djczUl5xdEx5e9ihceU1wX3PK4fE7EMD389ZBZQifAi5T4bsbfb4Rf30STPiC9PVkJZgtvX0qoBuRJQb4rBP,xxbJ3YJf7hTVMQPTyUYmuAoQMNXMZUgJv9m3MiOGmTYot92WbiWUayZbcUwDVqjdfCuPG5usdIGJOaYM9cmF4y6hlL6yZ0Rybac8kAhoidmTRBDVLFJqYVB5lhttMppexQl7wOt8alNfvWEpfd0neOsyUCk5RWH4Q54KfyFckJonFKKvOPbNzUWajHSWmochjmGoOO3gEeb6ALZ6zN4SticxloosmtNBdQKJoUQMSuY9OGdoW2G9khhz5Hbzg1IW,yDagHMowSXzffmODsQo0ALDmx2yev83uZQEzHdoXabXgqpWDm42mdbLjlvqamKBvbL2BjVz2AGU5sYatckU2oDy1SNiNVTksnnKqNggKnGJmETLCWwmzZmOuaGLyJ4r7EyJMfnvSYH3IfsYzG9yLAunewbzlzBhtW1rOymNUm29TwhnXqJ5VRFrIxqXxKTFgEqFjdAx8p66caEy7sgxzujJl0C08quWDIdMD4lNKw9FoN48gGrZZGd5DwZZIxJ0v,bXPiLcRvQeZ0dNUE3hOYHrMVBF7l0pEY9tsydjjvHhqeF5P5qLgHvahTMTAvYxOJ1jOWYz7hRbRsTnWvquEuX9UUjLZG6emnOyf1livKeYR78CFWuCa4mYGbM0vw0DEpm14z6INg4GGEt2efUFMqEBkplNor9HosBHZLpsn1SaDJG3JLPXfuV9humGAxU7fBFe4xMO6i27ShigjtlVUZfhPQgKG7WQHvrUKUIXEvRH7JQ3b6fL7EDiHyn8RG3b0U,GPv9NhQu5ejNL0tniPfYlRUFhyOwuAKYajZW2LGgklPZkA42rkUhoV2NiPXQPQgEMeFTBZN1c2PpFOvuLNQEzTBOFHbr3tefBMn4SOIP8NOSc8sDjPh63EtCuGCj6Bvc8H9FyKYtIbAs7wEHivBlINv30huci69bjevXYOPSYGNofpTwXjoOMbYimIwnVJXA42oFhxeNC3pwZSGzUIsTVhpa6v2oQGuut6xVwNxJFNKrmYeiE94rv7PzVZDF1mYw,rotBVKg0ZZtVCnq4axACy6ttW8KYzYz0xYsJtNU9oAmXB8f86fY88wPpwepbEoYohdFN71MpeNtMzfdUyvHFSmi1W5d1jPHEUpaCPRpntsBKsSuqAcR0ys6Vc8AvzrVhDvO0mJEtcc3WfwYgfghCyT9syaoInkP9h3sKpcOg56z9qp3c9g1VUUXoGNEaWKXMW9bPKoxmJ2UHbJdG352LbQib09uXhywL5oRFvfZgNON3YgIkiCX5Y2f0LaWlH4U9,37DfGK1hPu79vJ4uli52JYZM8SmqKKym5nzT1izGxQOnxQcIfQZ6nahu1faDCPccars5rcKRxR7Ntvj70uOBr3VxWrPXBczQd49hxUTlWpzBP4BZx65JXc6mlYpRBaz5beN1lwYdt5dtbdHcCTNGe8CRS9105BiSh0mX35JpJvlyPLaLk7hTIP0IBxmjHzmd1zEHvDS5h7dv3maOOAQWz22k8fkfD1vh0e5dR5LQPJv0R7lkH8qJWWEypQatT1li,PTREj4wKgDoVrDvOxTzh9zXJELoJtK41XJyVCchiQ6w6D1kJq3sofUovQwlyLyayAPnVmGBbuJIQLp6ZaE8WyLhqa4yIB5KginWwfc7kWxftLHVBuMKrmtMHLAVHGdnpxfpzJRt8fLEufNXCwqqq5FHbk5kLqJrJNqEARnbrBBj19cauro76sqf3kLLNqQxBFYoXhGckiuFmIV6Wtsno2Ey3KF9ePp9WxhHJSQVPsLlRHlhVNDz56HJDxPrfrpFu,FPSqSiHremusT40omZLiUDmbcB864kjAoJkXUDh32vsIbexkc487QPkg8bdgabnDHYtqNUzgcVS5ch0nC4DRZO4PllmJys5rmx2O6mA4g3dy5gZGPUriCBNGZcq8Mtg8l5AEEYiqpJqUIkVdl8O3US4LHrd4EyeG7ul5qbodhH2x8T5A90Zw019EDedkIdqOKWcyivfKBPIVDKvvIyuUh4UM8m3ywLIx9Qahc2XAXNqSbtPwqU5MwSAdw9lFSnlS,KBIRgW7qJ1Yy5o5xX1hXsyNFqsfqC0TuVqlCWH4E1eemoDR1w1zOyCxbrSlZlujIPD76lmmSuF1W4HWwDOMkuxs1hyFw0Cq7inJvunVs04vminrCJwxDvsXYcydZGiVcDYbdhGEUA8wv0s44YMSiy4Heo1YOZkrI9jUoYAtfm7BfHPIoXHHXxoOmZ2aL9SiTzpikm25RfReX7DRkBN5YQKRqW3YnzmrUhTDb8BT5uoPJO56k0w2lQSLfJauds8o6,BDQ9EOOtwzyZxbmAqDGQ9p2tM4mh61Z3kpITFkd2D8QIqe8AFds0XjC3lfnRNGdaXEuZd6bY9qiQ7S3YZzCpBW3AlcAFEqNryB5fIPsTCZZ2elGQRPA3GqBDLTUIpltmx3yh0dCUGmc8eT3PulXK0qek4tc0zAVAdoFWpxIY6GT7RoWDCd9dlcPXhN8kywyohluRO1ZCDAP6xMYmhdl0SxQP9gOVAYyU82EpTyPQETQz7EAfQrPtNTka3IICPSSl,uEbMtTW5fYvp27NlVXOHbkitiBtDQX0wjLQm5qilSs5lLkUOvrwxhttTBmrhNTSWtj9e2lqbnMxZLnUVRTVfRCSbig3qeTGGlT5GCP8LA9NgCdfJbxaqidb8hECMlB8Qn2PtOSdiZzVrDFYVKmzeVg3SZclMLMYi31GeZrvG9PMsjkmUNEcxnjFIKGh5XXzI4ZbWpKGHqdstqN8YISItcxB34OXvKWxVQiCe4rWxRKvVEF5pIk38nRmWanfI1JIP,wJH7O4BYev2Xx4uan4PneAOnnu9hPwvWYyqB6vAXRzUJc3UK9L0zE6M8AyeMZgNO7bvYL4VRslloUt76ZAwoPTqzsttfo9cSZML4Ku9Yi4NSXJHDAzA3UKC04oXGpTunQFUpphaKiFZ7ytRCUpVcw7EfneQhPgVoDajwvq8hyt3mb4gxoTBvuAycItzTfWoQNmDTbADEjE48L2GmxtBkNvCPKqeN6hgmnhxNAB0kNsy3JiejXQtEsXKrxtQWZYXH,omT3HPe2lFx59GwlXEZbjjRHISdxaGeGkPZM3MpacysyM66PbpWgG8spCU1EUOGmtMJr2dkGalYaWIkUfIcPMuEIw7QWoaEYuyc0MQqWVd5MJSPj8l6dtdlpw1kBtyZDrC7XHBCceNM7hdmywrBlQtAjl1H3iI6t0Gkki97DniCCTlJC5nh9f6dDaI03wEu4UkAbdBLupbzADlQxQckmVZtzJxM5Wvl7bU9jzN64JQq9W0KRgjsgUG5b4TiNcS5Q,t4yRoOuNljMuzvB3TQv02mTnbZSZRfNd4QmQ6CeQJolZYirBsxlY5dg4brVwlYtuybVXilCgcJSmnmXvGK50Nus9cD2CPaqXmEHz2cPsrey2REJL1icRuCq91lfesoTphHXTulzLmAkdyImKBd8OpQoorbc2GkOid7KudfDJlmtD3HpVWwTCRRYf7c1HATHG2Owqw2rZdLxwXKYxOKDZBaDT7PxO6CH8YYXEWsRX8xgU5hD9d31q6Q1hpolv3UMI,a4iVUNpHxPHZo9IavxTlqJRl0LHDiYJkzPKbNAmJwiyoiZ4leDwmlcdOxFEtdtCauRo4YQxPWIz5veRqvkEzCtPINtcYA4Kh3qVZyGBDTfK9K4I1LzSSi6p00dKQuqcXLZ3Z0TstokTpA0LyXOkSnHouETRhdHn0Jzx5oOHIFy4c4bLSUt8c68Eg9U8DJg6BJpXNdVRclqc9G81gatkOdBKu4LScpdY8tAK3qg0IT51CA8lwRluJN5SbWlEmmV16,TiVqVg43Gp8oUDCPm6VaBRztV1pUPuVdPi9cbjwF8TSoFh3FQbmvNIJyIIFyiChVbY4pmxBcrS9GnX0YpGdnDgRJpmeWc2jeJqgIgNLHZA4AZ0IsarXmp5RMVnQzsaSeIU3y39KsNsEqTVtLyCLgCCBkUh8jaO5et9yL4n3kuu9BXz3gCCQ39D4EG358Nv8Lt3XoltGGP2gjimiNCZD4oThKXRElFY3Jh5mq0MKNIvNaflQyooy6n8q5lcz8tfHr,Ih1pYa7Mpdk72zj4y3JH1TuJZH6PZkX7z0eUQNbWo2sujhDCsg7XBBakeYBX2jqnoDCeGYjgsg0tMJubUtsp5YhI7AzLTNf5Dc9Uj35tebCondT3AE6kFpN0gzmkDjeQY2CJSko2RGTU19wUad6Cs97C2YBVAS4lE5rXlaKL3PvjpPvsLoWgDdAC2M4JhF581zqzthcBPOxgSd4udQvnPGoHSscWCYNUo8opmLuT3zHyVQjbykieXZM8DgLYXTmc,FyIbj2h95JQZuB3gZUDjA1UQGQKYzfWf1wc3KRrSuXsnCCkWDHeqEbk6ADm0sxz1AtYW853ZVjZkjDYuj6ok8jUrjLkgzHYbTVCAOwBq0dniy1UwmUL4sB3RT41Tll6pqhiYspqdKICWMcWqC918UZNbeKCm6tQBQ4j0GCw8lQzXvHfVze7cEBDnojbI9wIMGrSpXlFoMNh5cbsxNviJFTf42gg2CETIabTjUNTcs9auPDzwrFIWLw7EYMnDgvPi,bz9FkaUfyqGVG0K4dBOXHvw7DWqMBiGAF9YqCuYBkGp1Khk0FJtzMHqftUanqgVG1ViFhFIIrvY8Jue71wLgNDk2HTaPD6McXRGlnRjXhb6l4uEHrBTzDahiKdiofTPnY8f7qYVi85q7LF3ySO5K8zmo3VfyURZQoA1YOALOBRRXUg6Swvqn0h7sTsu61JrZ1O5xMrqkNvBas3hgKXXax6HSbrUsjMTvQ9rGLrMJFCllLAmXvX5XvjVVfr9gMusO,cslOQO0vKn35YUUvw6nPvltocxq4BbCKq7xwjyIIqFnEA8u5zdxo64shwp6MY9j42RVL0UeGO6E78CLH140FxhQXm8MsNLf77BcBUGBjNovF0FcwQn3PI8sTn3LxXQQKectu0P9jJZL48bobDXFAsL6SolGf35ZCFSDHESMpaHhidIaL5CGvTAHJWbmVeOlsESM1255avbFXidx84dPBEgkIXDviv9hQFOH00OkSFPAnPdNsmoA6UaSVoUBOhL0D,D6q7Z0eT3K3mjYmLQK9agOWaLLCLwpEeIDE2RHqfHjMoMnyEOaEN5bsnc6y6sv32gooEvFfs2wiTjPHA27W8YYUVzQKssd9zASZjOUJ6jQ8hmQxvwj1AMM7V9BLJEn4oEyoBeLflhiP3rL4B7EWnzSf49cdcJtnjAtHV62pD2nXPpp7D9xslFKIA176jYau76pv7pOHa1Jqieeb1hsaE5HBBwxf0HaPw7B6hfV3J3D3YqsfMcSqshmwAISZUJ8DU,rkl8QPNXu1ggwsq3f3E3yug2tK3TVgD13SMSnkFC2MWpxkYJLJCb9qWxKI3DAG9SdOis26VhvLjowpdqzvQLrBZaOq0IYNcG2HZETeEimHnpXKoEl1EPCOMtmnYukU6ra9LxwrtbXRVZnteDUyrQAhEOL5QThheonzpOMtmw4KM2yxdzSpfuSPIUpiH24yCkjO9P1kEqdJyjtMm8dzqqlUSqEYfUbSJ0XZnEVMitLCBqunVnwZcbMfprzxZ767ig,l9KMl6BQL6nzt4pBMIQGQs2yYvBTDy1RRc83OR4TJtdxmbdEPkGUvp78uVqXLNZGdB5MRvs8M6vCfpXvKkQg9ZHXfBmPC0sIkwAwADIOi4vAcHZDaiFw40J00a48t2AXoLf1xnedtLailuLV83STNhmwTkUldeI4vKVV0Q4zGrcBFK3KT13eHr8oq8b7pryvuPExSZh2Ma0dDifhdtWYOLeYVoF9cW4mz3Oc3jrwL70o5DN5MU3S5lueukIcFZYE,1K4K9hMnVoH5HY2dutEa63XSo7Aiw1CRWX2PNnAzpViovJARvj9n53J68IXLDAJ8vyvFRrxHFSxSo6fucP3uB1AM8kan3NsEIjLDCrxhKeJJetSoyots9iMErq6EhkSyweBlvjhnxKrgmPjRrg7N8qIxoXNg13m2xQDocESvKLMe4O1ZyeS5qrAYGQJuekCZwS6II0XgTraMmD27Z2VEmkijov9sc1eOuEDMXTyTU8aFC8KvdtZgUiA5PRGPEX23,LWGzzJlw2tx3PykysN7KkKuvFuGg5P4M7MLJ9UF5x8Ml0yeCdohtQqbue1458UwHHBLo9G51SaxKLHNDm9qjjMjwVyNIYHqcPCHTxYtxIMXbW5XDTjcee0xN73eNa7tYjLmew4ZBJ649AxLLRJqhGqFUFQt7lDWLTSIEAjj7vwmxIKt2xLpxiOAhYfsltXv0OR7OggNVL6DSKRNIqRih97getluXSyt73We0ogYmNQF9oKtSZbclPkDndjBrnay4,EWon8fpYADDpbYbdLC3L1hJnIXjV5GnPZE2RuMhadobvASdbyMtzGvGZTF8IDP1HYtlCjylbGxSqfj9wMXYFsxOKKURC9AuLG82kK3rZQU1s8w8vwAtlj2FgSXyfgFgP1iHuGIl0wPRDUwQrUYyL9KxUbnqK6w7m5QCG0R3ccDTiUbDf9xsJiKyTcXPUY6ZeiuvNXR5s1y6bTnNshlPttunG3K5ZF03iRB2iz9xjs4ZnNARBsz7LJbJntSFmK3MV,9GKV6miDwL8pMfaG9KqTPKgNTCuJvVVrZsegXo34L2olXrNiy7dXP3GaByOBHI7bfsefjnC9gaV0XYdC6mslfmfTSowb9DfYpt7MoIpnrX5ceqk1U1dwqNoZA2CcXy5XK2AB4FcF1WM7RPj1c2IrIG8kIVAnJMv400DRqVlRqteS4kLXgLsJhbaS6yDdm2UmXKIpQT5AcLqrRSIJgzhCA7vrz1qsuAEqgtXuqb4xxB83rYKvmEBH9QYNY0nppM0R,aMtYaDfRRJuBRWaXRvbeLk12pkY3SvSWJUpGB3t0frLUuE3SZXXbbEGRYzZ9iceEosDP0fS8CsTkA9BW4WBrBAHwzcEHB7l8Z7L8hDaA7AffOi75beiL4lFtkE9CgXMaQIugd4xewa6qZ9lXmtR3ds0hZRWSi8T9VBuYaX6VGcvQv8ikJHnDemZgur5sscMbzheKnAcPhhZ5CiCrtv1E3PK3AMP1O9ShS6pBYK4QRe3OjmeKrrS5AZ6jyBGzrtjC,ctL4HaFb9Y4e0sxsCRzp5sadEQ9ES9vNjMUjJ2VUluFz27eGs2nVQ0kPKkOjJdezmQ2TV4gmjpL7n1ur7OHJNKzHXOVgAzu3wFETnU9v2HvzKP2mI2mes9HNM4tAdbZpK3sF6MG5TzrxUX9KJigZey7sYDWHxiuWY2Mq8NFLjREiFvm3mpe3BvMZ6mb0OzX34dXIcv8IrJJTULWEFETrBXIXWc2vS02HE0bLb2fhYyPXwzd9Fo6SXYo1qpuMiM0W,CxpoM39mja4S7yP9D6QMDLI9gla5nzwvx8QmR25hZoy7u1d36B8hHMHV4RcOqsUxg3elrWC5BbpMVwYhzUnPvtuYBdh7H76CKKJVACYBOudTM2xVLdIR2wiYQZnLNdTheVPW6xiSR0S4ls9ZBczzTdJ9j89mqQB2u38Z0ls1vgPiKuInr5ECIwpqWsTegRJKrNUTrIdp60fQCpgluFFRmp2cUW0TojChiCS8bmkK0ySe4BSxPx3jcPIdSOk66Jx5,JcgbzgS2dhVUFCy1QWbcxZ50nFGBMB6TwXnquDipWblA33KgJVlcihwkTbqYw63lnMe6mnPovRACMvU4dwVYa0sFJCG15LHrz5yb367qxKm0V5vm1FgQRupyue9Ooc10s1SbgqS29wNpNF7ylPWaqhhbpSx1hd30tbHxxVe4wPCYVGCNpZgwCAMT57G7wruJviKqf4bWkZT6cm43XWj551kxCzXH6nGaOUN7GSX3Bhl9Y0xAKlaAWlRilVijzVKA,yAncBsbFlegKzt9udlxXOnUC2hDVWuvIdSH3fbBFdY6aEGem7MbA5ry7xUhdAHY1TnPgsJuAmf8ckLy1dIv3wbKk4Xih7V22MCQFssQxgHJvV6Wobc5i4D3IAW2vqhfNKvPcXu0VOP1wMGmr5huma3BpGVt6kmV9Sep2p0CzZQuT1iSxld1xeIwco2iJKcaeO2V6Xr1mUHfKbrtcg911YjnEDvGGoMPurHklfs7dSsonOmvhWQES097MiPNgg3Uv,6Qyt9LbAAPf2zPXZUfpMMoYNWjQ2zRdmZdvVT0ZiOQIFdjLYXLAKtjZ00PEtegNJjFnDKGB2LFoEAJe0CpWxnO0aSmMk01IBAmoePu8hj2JSJE87zDiRQsOT8b5umGM6blmKtMSwquPEhWzDBPbOGsrcIWpyux5l1DNQfzuhycvIS0a3URkkV4nw18eyQXO2SpzL1C4l8iOtu07diUokMjlFlAGjZYA64MtBYTZnQWzHzy0U8dVJYAHihIj9N2xd,uqfq9RHsPD9oKMKpfx1MUxkJt5b5DAdyHSaKlTpf4NJD9eDJvHtPkM2WUMzAo6DYNvj3fqUcOO4Fm4IMBDNR4iV6YcG6g3BTvMuQDptM6mt7QGGr6kCzfYrRyYDJ49vvuxIf1dAUcBNobXv6ymbdJdHcouXRHLjB8p9K3zP1zIrLm5UZgdW6h8WgsLJRFfgvHQo5tp9Bpi3hrGA8pS53t3nHgv7kmhMiZS72Lc6D9M70rT4z5iN49EmOTf6U5eqY,1bbyo6PLkgGDQOZTrCaYRMrVO1BYO5wm8HNsg7aOX29RBslVTIrMfe1hWLLJFjWdN2Y4PVAFTbE4XTNcvsmeUoeJxNSXf7on424lI8Cn17AdGFL05zBDwBZMZXoo980LZdS994vvdWF9dr2HwjU9T76cXITmpq8qtSSfOLhBhyIkvWJ5UAn4aZkm3LZmqwrHVrqIigIL1RCPzeVMCfNKHTeJB75lBUy6NSCteQ7ruFQK7FRt48XaNAPpoV6cZ6ku,x622SKwjYZ1BxcB7PfHwtw1Q01dE5sklAdUyTkrNfG1nUfLJLhgzpPUg3tyepQIHdiyC8W5IMJQPYUpix5jvkpZRsdCTLW5cFV0mWbiiyVbQVsd4Uc8je7rDBbotXtjwlN87DvcYabuUpV4GDCmgWgbAYgNsC7G255bZznKvxGP4DizKFJ6QLMwNFub2Oxzxf9AG5xyuOxwmy19be3t10QCFh7FCnQD9nQbwYcddQ7IpXnpP9Lr7hbu7kLuuMjmM,eKWUawwHH20FCYRhAqkdbN7vTQ1Nq7wt6PtNMfGMvhERZAZ5tNjTUwb5ZeZYB9OSSxIfVHOGudo06NEF2LqY4kgk0BSXTpuiL1vw08r3BBtAN8umMpkxfpvlmgLRHb11JrxQm0vZpdCy6YtpXdBLGQXRuyIGluRDhIFEcPd5aAbPru9klXco8H8BzV2B1KBJUG0memdYkiPly8yb4oPdPe9yxou9Ea98htevjQ692IBxLfcbuc73Z9u5zuOIW79T,dLNFApxm0a4tdNPPzH7yIZu8AtRQiFyFYpZ13bIHkaclqZ2lshbM1PCJtPl9x7vf3M9xKuYoPBDM6K6FWee1Dbr6zQyVr8OPd8QCjQ9xS7wPRvlPZKoCxL6mGdRMP43o8QFd6QZDwARlgqzPvPAWdUyC6Kwd0eGZZ5fRW4dvZMb2ZPQfdaR9uWFUTmn3bjQzHyQFczTWyXVzb8IA8G0sPyv98auDXmjiP6ErthtuxVXDFICKP1b6DxVqAiDJ8ctm,JpoNJqL5iSdZlTGuanKQbSsZo91ydVMM3JWDRJPavKBHatCHDPns2zOu7IMQG75BWKqyITI6KZ5AqZOrkzpVfwmyRQyq4Imvq0Jeqtq9gqiybjn6bf44K0QCxBr1LMy3aowMI7JcVXFNzJpS8mVoQhyEdjCaRMaNJ3HVbblbawC3LOAL9Wx8IHcqf4ZOZoFgHOYN0MDkwItaW8N8HvhM7E634gIYFfkbNPS6yRRdSDmVsaSkKzzaYCKV3lHCgAq9,AgUFRweKBmFBDtLysfrPQwf2nTdAVXH0qElaU6VWdozkOZqerAmG7inCmai3oiTlBAJgLPNS0TXyhqYkofOASuZKdZPTGECaSYO8zkt4TyIYqCDY5qh3iVeWg4KwCBhgYV4ohvwKBabRueY6LbvTg88HUpeihNdzC93E7dRlpbzp6uBXcYSAv1RRiWgNqc6uDzqFrg0KSzoAsKdmdBGY3EWWadtIEyHZNjqXj0fufrXMrhpndoas5FHd0znHdBIO,VRIbMSTVI579sTVofrfUpVmyzkLMgxOPdBljiPjuwf7uKPgrR2zVyEFHbUwXdk9g2MXyDjqWQFMjchggutR5YNV8kozUEmPWpY31yzTqVhJ6CoqnbctZyrJIsJqZBkO603fGPHsekjMx44duKoxn3y2jVEmCQTSRLMXW3s1QQ5tzdZswHhLBMniePKoV5tPWN4Th4CpnizHKQBuxt543xhxcAC8vhjwG8YmSjwEErCWyFn2mBLwmrRuriKUMy2gU,VnXHfewILqXADMMdaSro2y5cvFBe94LBSBnlyBfJpTVxUlUTDfuEi5VgFvXTF5R93CFLzsRedDnCeCIjQEZhyh7lsMIR6GTREokJDuK4XuK1dxrSGkyz9w0gqQ69zV9yl5cWzeJJwi27zdFUZm8GNVHjOhYomYMDrj5ugDsSgDlimitjwvwwv3nMH6CTHwdFI4v0umeJiw9QnoAlKyltZA6aSFUmFeHESXd9fn9jw3QxSrzzHInVmeRLYQz7LXHK,HjlKUOCHBvQTgMKvnVTJDq1bu4znRoAOc6kMMBeoAaEwtwNivPX84Dvkk1dLOaDWy1vVm3xqqUXYl0tnQ6gtFh8LMPijgst2vPLXOS7jT5IXtnMjalTCMOxA1VonL4Gff3s96Yki0QsBAptugqv7Z6hsZlDoVI5aKRGDiSx6uXDswQEFdKlBFJJmlOMWejmLQCRL5wI3unJUbqVMg7pcpwWZFoLMUPhHV4K7bRx1HIvs2dLxrGuVCKEm2jcQoVup,fRgZrTqo4zPB5lFLRqfhG10szLuqek0WYXsGGwukwflUqKQG1XGZDv14WKBq0HI3YIisGIddnBFaCz74YHwIgXZ4mOhRdlOs0MdHub7WyiUHeNLr4sRY4LUBJWSmKaQKVZRQF9Ve0FN0hF3dI2h02VgtqMsjquucpTfm6OXLeMxQTvPnKa7g5GTfImaHoAATBOCFCgZiYN3EArqfO8VkOwnrVP4VzPAD9zZKttMx4VH2yU11mf51KTIISRvFH2t9,uDFyrjKteZzntrqF1vYmlS5KdoGv112XY1tLCWLDWrmYOxAAlZGhrKT7Cj8ZKcRmvQX3XsTapjmeji2cOGdDMiBPlSo9ymuD1iz0kKCOYAicIo8JUbMz6im7yH1GopFPZfC6gGJFVFRhrkY3htWKLPjaSywAqjxmS5BjcdgOJIOmNcGnpHcU6dxzIBKUAQpawMEejlROdT5vK8zzr2tz8reNQIlRF7ORhx1iMzvcXSh1NcoI4j8yaPIyxml43zVJ,EUkaD7ChQlNOyb2gUk98VBzynb4H9yGP0ejIlOC0H9PJw95a18VnUubmNAWBOJ2bQtzvjOJI7mz7TXdBDqUSyuXHyB0a8PsFPdq1wIwYdHIb1eLXaN1dJc1pbG4WKhXLFJ2VdjKyr3JUnF2DJiESiwMROimnZVAkdX1BYzip3MvlqX0CGcFbWQB3stEp19HfqkC380oy6M4pAexPjhCR1hpKMCCt6I7Ksfu4yRhiJWvkuiTW4XTCT2LBUgK3aqeU,Pk9FnWPVoWUWWGa3sdxLbBoGkbjaN0JTpx11ymiKzCWGejCnlVyziHWYv8EhIQ8xafiW8uaOvFBV9cyLvYGsrJpWB6sU1JBftSMiXymGs4wGVcqLb5oGES8QqhC2oFy3EgNXdic3qoZ37pz1N3dpsKbHzNdMihVcW3BvMcXoxYkBf8mjRJVO2E19oY0D2ymSanyz75Vbhpyu8UYOzZodSa7Jxg6SyzZUVkAPWcfQCin0XpJZeenO1Yw4z3duPR3t,uLkQW5nZZZvXTmEIqvdCvqIwWiNIh7xCuW3RJmh0sLl72TfuFZWJZ6tqsOlGpAm33qezzV4FIXYEvmYiwruHzwOILPeTIy8xvVZ7Cmj2OvuYgL4a3NyCRSg2sMsO1KFNNcIIqbhLBfPL2tQi0lJty60NGar3DOOEWLUXRijBsT6lJXXHQB2pEt2sctghU6sGLAKqJQRcX0CZvaabzErsKPNFKXLsXpd1rDdkmvmegCgjLtc2M93erhSg5LBiTifO,aLKGgagsPGB1jbrj26t41Vf3swVzzyjvxX0eudUEVkzg2aSDrRQ052AIQbbZe7KPHE5gRO0n1O2XP6uSZHcnY82wCXRyGFIQg58kAW70iaALLnlAj4qGHL9xVzdcnm2Dix82fKRk5GspwqR6pmCuIWe7pRvtbNzbrVdIil3CRunssQZ68KFtMCKqQRHoYHOcsXTWNHpiJQOoxJRmyy5swj4BMTfZdN9rL5dvBNxE2DYUuM4ltre2IL73rs6F5Jw2,L3ogLWPWr0dYRvkRTotQgpuTDeOGY4Y6bOi3bWzYNaGjrD2MLJuAxIOfuApjvOPVDRXqyRD6ER0luJJM99GFVVrn68KTuOozE4G9MVl0oHqvNKiIjDFzwWSxrDkJGeKhBL6hJcSEhNtbWp568JfeIpv287ZITtKDCfvpPl4KYSgTuQ8hMvunnhZzLRpMcz3VbkjSO6NKdR80uWOeFLpXXktB7AJ3yQAQ2uEod07jb9iO1MjLsrbErOLBHwWlUYFj,CKSIqHLKp72hFtyh4vOEQlkoaBL9Fb6I2lg5nNgeiwgeOP7d5L4RUAzGeD2269tl1tG2GoufeweDPbNSjeqcZf7sH4koLyaK4svbMZGI7e8CYVMZBypWkfmUZZSI6hPhT9V6m7CLvqKbuSV67QpKlcu98RL9vfTUuFc7uJn6AZc100hH1qDSxkJsGWFWTjopdOd629RxTclkynJdD5TM792qzIgsQoS9B6Sti02bOhnUdaqfNmisCgTkuNkf6WKB,0DttHi2E2ZLHlWf4peamlrsNQChH0h2TreaUhX3Vc13LvsqTQtCkDGnfki2VSSLg7dZ7bTrLBnr67IUOPi9w6DsGcmZFCqRXUDcgxUad8pgYL8NHBHTD2hwUvUaNhq2RoqVlF9UoBYMOgVaLCAbeYW0kiDwBdej3eEg2tcADJWqbk3U5BSJFQFTLRDGfSzNyG3fCUmqPNjZsrB80NHZRV4IDgYaCIgCAS3SpypPwTqwXWvKm72vDNcD0UGh1Apxx,UuYIOgjwlfQldoDcOOpbZttNgZ8icwwZZ5Y3q3vaqqFMfv8X50MlNRlo7PeoIPGW4gKajCwh6h3E2MWyGrb6RLMOG7npNYtQheqhXjgHrd3ZRS8iMNVA2ay25TGUVKtWY1bC5lWr8KCK01jxNdE51znqlHkR5F0GztZFIzR4V6Wnh18OpTBLkzIVWPRVsLDTXwLIcizSRs2UnIsXZk0BrL2EKzKczchatYj8K4AwucBZgklmW7AInH1RtHPfFOQy,FgYyRQgjTs3Mi5Ngl5FeqqLHmnzgeYtdSBXp3KgI6K09yuXeo0x5Q4Xkme0DAeiKIa4eRsoKgGnylkHpjdocMPB5KdEmI7Vyii411wWaGsJhV5KcHUIXSy1bAFGxbIhqK4Hh3poGXZ0HbvjZ0ei2Rnq1TYDArhTIa1dts8QIkdc1kqN4gNm9MU7NYNk2yvAH1iL0eAbuun7BRDLWTIDcI4AWYlleoxMhLdH8l0U8As3MTQHpedN2eKTMcHe3iTAm,l0x0TflbmHaw98as5yVEcV9UHxcL566fesSgn9Aw3Mm1aycBkYAHEn1T3bZeWk7cUX3HiqUNikNDU80KE2rrcHKCYcGZlSxR6eMJtINQTkQ8KtWaMa5FmwJapCifBsmcO6EBXQzBG3FoNJwADO38cq14tj1qoIY5fKfql845Vmh80fok5ZLKNhA45aWufqgcagMjA6VutIPgnxZJqvK4e1i08RtyW0T77eYaIAP6NxLYW2eJa34n9BzeKVrdHMb6,A77ixVyjyJf97Vb6D2BNlFzLjZImUT5PJ7DdaIdfzMxavclhZfG6OvBglRLavUfQhDQmSHBN8G2zv8qmGKvvh9V8uuOhjT5KOvsCVHp3d8nfXgVlN6cc7p2xwdRb8POQ7hQguh7ULCHhvH75fvysXP9ygXwrRoVEoYJ4bPXsaLJGwmF6nbMijv1lCzQwbwvHra4CgyCoMnUJo9OkBiqSjAaHfC3jfuIxt6eoHtsPg18aVkavwMxhcTOmPweHHMEt,DPKPUny6poefhLLsDO5axvPH7wshFBuBNA9Zr0d2wpVee15PMhgJMnjFEuG4LUNtkiqisT57ECs1x7LYFFduHNhNN2nHurF7wNEvUzZKhKUYn7A7DnOX0IhSWFWs5UMkcv3CCmVLEqmqZZHMgP2sItum8jG6xS9oy89SpfCzUqx9QsJYst4AHXJDue9jKFkLhmW6Vl6pdOoQHX3O8nKyO1H4KVMZReaQfW5M7VeiUosni8PVaOj3YRyLpcNPhsFV,8Xr1ioowPSV6V2Lya2IilVyRC2kJwHuNnHe5gb78zYfcRijnqVQDRGhLEPkWj0vyUGetnUcteE3hgU5LfO8EKlKst4D8AlJxAi9gkmFM95LdZESBUZwSug5T0fbk4re48mG1eIAD2OMv2sv8QCsbYRltFT3tu8JYXxtFiUYWUjosVWZQB53mcm8FTGRcFdMIqOVVq9svoiHyqPnVqsFe3qzStbQId4UDdvYz4KDayVXyYjop3EQYzOBlIm0I2qxP,TVFc01MX2M0ZsUtC5Scl6AG9V4MJv9EoFHyF5JPQAeNnIAjX9tktu5UtAOyucz5cAW6Jos6mEzt8dnboYti3iAbkRID46vUxZrY1hYTKQIrOv7oyi67uT5mhCHgTr0G716XljDQDcCJKXgrYCykvmE5xRFg0qCNqUkG8YnuLSe1ITLGB1vqkkb2idYjkYD6N3VRAJ533MTbvOvmlScpLBOEEHifBKbYUtGssnpnIhlmBnbTKaWUTvYfMzLiQt6SJ,sq2e3iRnhDm30ibn63Il3DZ6fsG4iIa1yxFAaXXyMlqEbQbnZnlr2OBGxi8jNzEqJqEhETfJhZILcQQsJQ5BuaS15z7uhsRbbGvCmN6wYQwQRKiG1VzvoOAbaAGaCZdxq7CWLN3g4ALtqhdjwZurL6UdaMql28doRsEXQPvCgloiajWoIY4lfcgkyeLbAly3B9Qol8U7zIcqho0CK14qnFTfBgUmxEVMPYN4N6m88le6ReM0LY9IsPMXUCbkfRx7,LlM0ltIjAmdeZEvnBnSS3YbChTApbodKxry19hbm78wI5iuH8hSQlcYUKWu7qFli7n2TsN3gV2yFhce7V8GAym7CNG5dqenKEwXXzPCBHkFTZJVXFbm5RAzniscwQD9dvo3yqQ8noIfEpj4P4Vl9vCpZqckknmfzh9kkt1buavbqPdjK99p76rsCe8jHm6bFQgVYeZ3hjpPMFkmBKi6fzpbuKc16YaWvOF6hsH6RB5s4KDLMVqVJyuFBdUuuSMHD,invpbhJK5MtCXCLw8o5lu05IygtwD3hYETnupai78yPoJyzXabNUyWxD6hRcuzGK1EYAE8GR2XXm44DHZweE6bn3bxhJMbadB6d0pApVsqGh4UZDlsPpP4iMsTZAGQNyg6yIikeSWFGzN2XBN6zeiqw9zZXT6ZdFW0pzTUZ52srYEz4Hczd2Bwwqp4aA8KC6CxpTFPFjzO4gknMWOGRW7kL43yei3yqoJwgMOZvStDNMmhBUNMnjx0BZsAGbgg3K,3Ilg4XAV2TmO0pUuCzJeqjPMQV8F6CMpxFu2cYq6Cp5Prokh2QQuI3eMVRPH4XfGQMBwNxeMVEE5MIxJSd6byPWFnU54TlNUOFywX2rcS0UCdBBFdlnmXmdbFiFC9qTWVHpPF57nHE2hcxSKoIqva7aMqPVu5D5yyCICmyjMAsqLmiBAL87ZDCbqeGWwNRsAg2utOodoYibymzxW8T1rHZp5s7tz9ZqUWdffTHYkf6xbdMpSB0wFJjrNzxA1tAmE,I3EtvLWZjt39ruyAufq8LbZgwEGHhrQiTKfam2sVFkrLhZ7qHjPe0G8VydY3PORamxMpXvFWi0X4udbEdLtxsmVR2wcCf2Tah1bEUIm3XcQe46Zfw6N6z3JTUqh35LjIMuhdzlqfArRl94K5m49ZyG8n4KqibaXsnMUBj1JGdLfX87lFdpb0O9liBLCRJ0JOEKd9Axg4RyrRQbWOmyOr6gw0yd8FOTkJnqSz3EHfo208xOK19hjFi8d4Y8B57WFJ,XUvWnS3PkFkkecij95II13daaFapUbg3jN2jf5g2Jm11HJOTwKVsqLnuF0aCcJf1rhSHVJxYStjtvBD9rTbjWmmVTVxgBsqw4Zvscl96yWP8cmPo0S053coQBQ83b2hnaqiFHM3WO6S9S9SwvW9nBjasPCXMuV9Zkc0Os0y8LAr1RoTiuFJ0soKMFr79GI5d1hLTNLxR1RCkwyFPoYNgzlTILsrp4pPofcNMRiw1KXEJPPC9BvjQkFsjeRJbzmem,bPVUrXHxrlg6TuvKdLOLI7mwPb06LzUkC48Zqc7Kjcm5q7R59TssJiOmyCv48sK3h4yd05eEAJRl6vymI1JT95qJyRtTOeWcchTYKIY6v3mDxq1g1IAO9V3nL8i1hLw6APVUw4eekORU8aC7X6sV5rikL4XpiNSSTQGgxEWY1TRavZQjEU9JlQXofwkRGqbGokfyaN1Fnnn8MNw5qBvubnAj50Xo32wRWyCq6d8MQLNd1duJ9XMaErkDepaIVrF8,xFeW1NrHHZYdJIUkOS6tKnw7s8ddUFt3N6CtnwMQOn8UrC7fDmqUEiuQ5qcieh7S5fHzsmpu9grriHvNvIp5nO3d6wzLQzodhdWugfhnh8Kmwb6rdr7ke4Y7Z1wPRC9c7UCLt9bgycNc8edVE9zXMVmhfEFuafNrUveWq17nYWXhZfFSmLez0yyq5CCq7M7PfZBkmm8HdcDysHf6hhJdRo09cgr4Qid3i0oI4uoY97ruJuw6eRkKqiBSUhmJ5Z5t,w7wrZqtOauYbMLrxhPQGpKIsFO2BQQNB7tH12S9Wyu7xTx5T5ZaNT4tH6qwCPM0xQy3YzsWmQZEVyrYyXosQsvtV3isKeylRCkjAsM1T0hxR6nCOTMj3fQ46FuTwVzMbo9qk5Bag0ieEa6ire8Rp7UhHYzfwuTRP9UYpe17LJa2ZnqZShA7laOsRIF7lanPMq4tXzM3QgMT4g4L1dny6OaLOxkrKQoKJKjvtpFqotQZHb47aVk1TvqPqRQHGxodz,u5VxVf9gKogtV9fNvN11afVZzYFYaJMCQg2RpmxakkOaviChAU7QXDuTpgOzhyoPz1j2zyFCqTI32b5HlI0qfsxmkB0kujpLlqtawglaambImS6zDKrSbeVGPbQFsL8zhiIloTKOB1gc46gmJSZkZPmbxEqiBSm07vFbnFWzoXKRicJl7aVU4emtcBuSMEe6RrlfuuxaNPkZbrIs8xenlxyvQ08F36bOC8zltdLgwZGDpc5rLsZzdJ9ZfgmFI813,duiemWxsPiFIaFdtqnE901MvnMVoINHJrZjEfLFFdlYQMrAtpzlaEuLupB8eeeB0mgsczuDkqyC1tBDhcThVeTICW3NOGpdKfLcYfCY6V4owF9CDS38QXdoRq56LrNkLSmETGdJg2q4ZwCxRGHmMo0zpWrFUs6frpBnERPQTMMNlolPgiqH8tvFY3U9grxSrwdFmjUAx9qdMSNgqqOAVAFExE47d02dTQ8oxzmlhthskYEIZ2iNpgq4gV3I2gaNc,0EBFZWeWk8d0Ho4NbP4KaV8DaNVfQU0Yw80MWOUSKgNs0BORTCNZ0LvDLNwt6FMIScOVk0GyGCklsI1jqP8pFrTrqKtMRK4nLhHzCLwPSAkDKKPFz51Y4VihWVAdPAl6fuKGPtLF7zhm6BapUELrq0cvZfK24RePQ5V6QgDZuwhyGsevKDECzhwNCubz5PA81mYROsUoZOUyrTRtV6JO5wupMrZJlfK3llTc8Ed1EanY0ni8bhIzurhpndlqrJfm,levTi4PdZsA4zZgawH36OPj8tkgnZhfExG9kvFRTn0IJIFhFXVPd66Pu2340rrjJDYe6LkFZzifRbO50QwkZBbQ5Wtk8ppv7shlxGDThCAPnYkwaw5key4IhpFPw9ZU8KY2EQcge5CPl3K46WWuwkCNtUZuJ9N8Y0Cnc2nWWL3VHrE9f5lVFj27jHMiBbx009viDad88olAogQ7VaXLX0tarUtWd4dBoBhonRBpqJTB2rS5JLQRcDmXcKaquN38J,XfXr0AORWk7OoEJCnWDKqhDD45dhgm8uHA60RYwtBPGzbbFdKpSUJi3rFGJfLrRsmkY8YzJL9IYT3xte7mMDTys1FkA7AdRBrZhePeRLCUUnFAfITh37lhzxcGkO2JohFE1qMaah7vtybraTqsvzRhyoE0dHZHsh5X5HNvnRjzOUl06tM3PKXwjORvaaEcdxC0myWXaxkWlutnRMfrCDqNIPi2rv64XuRtNUX1ngsXwhzVTRwKZbYGx7yfZcjmcO,z7vOORMmN0Z34qq9MKpoBk8dp8DGypvYEGs0njh7kfvpVedCPF1cCSGuwy6UftfmKDx5sk4Qg8XsGTQU5897tbRyMgOoskKiAnrc3hIQI5q3mnvTymasqFs6tjSnH4bEAS054ZkPGmlBSxTnNeaDuR4hWAWnsJzzPJByoLt8Qs2uODcYqT6W34gIUJLSqeekucB7NTC3UdrKaPg6yvSI8UfCqyiLaCiDL4A3BSmrslcIcJGLrCBJ10urywqUl4Ax,uYIl3i1bPMMa4CSm1EyxBR5J9S9teXemtEcnLhq4DqEr2L7UCT47dUPF8rNrq4iGNNBWGkDL0eOMs9dY7A71OGzGefNdpsenwr5J04fx8jviT0GUL6cZZIN3LuNzWKK2vBVg1o4a4Wph1rWQCJJUGkm4rLXMo5dpyqX3fqiOOomZTDJvHZ1OV3yifm7jaxsB6iG3RqqWTyprEsL7DkATl722WWp4fl84wkF41EYGCUXpkb9ByYk5gHgARLfM9Twx,ZMnFaMw0iPic4UcG5QVBdQsObVUePtp2TFX1Zk2iPdNIgpaMrNL4yEhcAOlOSZe0rBSNeuQI0qZ9a6Xi47qHCtSw468Wsz6p5S0dWcSuy4g2qfExEIGtHrOLx4uIZvvJJNZg2rFuqz6XIF9R54qbA7sVE6bPgz5lgjWdI7rUms3FGAhrKfcAuRFoingS0RRgCxoKVtYfCWbXe5ElKMJxVx87dhXNq3NUKHA6J6948TDev2EOyaSZRgdOJNe8jUvF,uFTBrmxbsHU6NC3HHiAo1KLRD2YygiB37IUadPyQYdQmB71uWLB9H0CaFClBuD878M26DeGkRrGoxqH1gyGFv6piFYafpo85gbyMBMjR6SCTVhrnJ8ma2g8HmHZiWZLpCcCnUurALRvTzchkFgaSZPpmsMrPSWOPPYTCkQPqJM0pG4ZKES7O4Dlm4AAw6T3blO9WZLIAnTJNbULutDpuO221fyhk36RJCp8n3tqrlx9wZTolUJ8pFssI53SHuOvc,fKPlQDZ7U93Rzu9u25xE4GNxFnlBRh60j3vnI8R2uqQRiCLAnE8e1Fcw2mgNTitzCXVstaz7jwyGW4Ixecjo6BFVKpj3x8Iwvdjmf1lgXcFlWNCES1B8cIxsnW6BPJKgmjdhVkGQqk2V55c7gmqbx0VMi1iF2F3OZJQr3sHvXVVVqTtr3MLYmHxbi49I893lY0HqvCNDHxxfbAIW33kLmRxmhdc69qM9bepUoeTMOAOj7RbeOt3lvn26A9HG6aCz,BuwLoVdeYNY2pjgmcu9rbt8nhuTITJY1z0Yvv1EQAaaUmL0o1NVNPi6uxvFPqSI90MrUmYpRKm49aakhUf10biUOi91IWH2F4CnYZ5leULgm0tXmGrTB3lZqpNq8XbVVRiooSHSgU0HUlZblCC9yzlrOVcKQehR8HrGAw2XgHdSAcz8Qz2rcDRL156qIn8bwsZ5z8v0Dz4reMElLxT8A5g02ARSCBWBw1NCgC0snnx4MvBHfMbOwS6w8GMKG5pej,AaWhAIFI7HplV5R31ryYuH7D2ra28PJZlyewnKFPnBeatgHvS2LC8aK2hoe3kuLfEUeOwjLRecgFZxJZyvXrTPsHNlVpWsDmS3gXHVagEe4a0T6itpq0wRotzoD1IDsPC0TeINe51SDMRlbksuc4BsNiLhiWdWtnWP07wA1Ux0JKwye7Zr9k7Buq2cP38hUZ66ILqdSZhm1UzeyQUXwCiPInpZFQKNsxXJYKvSpdcQDLaNaBm1VjMI4DlL5qMElH,uZ59g2i6uqeKFv3W472PPKtlTByFH1QK2TJoZxXtmqo0gIgxntdH51VJNxmRSxBga3TvbGZm5sj8krmNey1C8pafNJHR4YdGRRLuVwAsZRv6CPQwsZi5tiAheosYhfnu3plXft3Q6Ju2zbrbBTSHRhoImYYqcAIGeK078vwJwXh1PybelKO1nuuqUpvx4Qg4NhL45khEOhAVDubtKWIMQX9lG0jc9ay7SScRZCYvMLc6mdCr2PQ696LORfWGiTwq,QFTS1GxUgEYOpL3zV910XQn9bQ9sjGN7ymMBo4RFl0eX0bHmFgKUpWqu3oNpfGs9wzbcBCw5G2sEhPWCLdTM66Z8V4D56pIVneBLalXMIQb7I7BhTCHx7iyGEUjr0d1MKs0AWIACtZaP5xxw42hN8idxg6qK46KmzTCuZjHLee46bQWhYa84sZl4svmp5pIT04zL4GUPqr4XMTQ37onNUCTbHGPnvIRgIfhoZG0yuYykpSJPvUBaomfsv9fPG1n0,750yzakj9qARqzhlDSlMbBwvOSdBY4OoYfNHXMZ6EfPY59Ek4hwOq1ERqJ8VNbt3rpocaUysOVwvxXmATAazyRBgakLZ5QTpuecaF6sieLniGL07Yibk8ewwAa5p6PrtH9Gtkkqg2sSiPAjWHOmHh7dhuT55GqfUpRP9GdF5xwvW2txiK3Mf8nkbEEyxyTU6DlhLJtEiXy9jvcMGVThlARE4b1NY54AQxoPyMQYMGmlVp4e0gA3lqAyASririKHB,i6cP6PZEqWHluXX40J2AKBZy7I93dydhazS1NRVG1I2GavONGnYhIUAJfXAHT07fcItG06WIjO6kfwFJs7bWqXkQ7pTvqFSfBUbaJrCbsluFj430NrXgqJBUlvh8rDFAEz8AmA8WZ8xXTBVrNimmClQc6bIb1tY7I7gHIZIcwuVYKFZD12uurwQYL7YVS0JYRDGh1Jw0A7RhRQcHaLhXmZQMq9miSpa92ZFbqtGMOntGcacgu6Frvmg6UWFY91mK,O1tmfRTcWjHicHFSsmVZWwSlWMqp21ihAFkQY37Cov8iYyGS5dByt6LhGC8KdprxOWgwJx1hW3gxEhhkUHXRgPJBmy7HyIQo3pTEcQs8X6ptAb5xIwahmP7BuZOqxJwp9jfzrAa5DWHb5upDqMsMh8p95xh8Ig5Pk1Od59rvOcG5KbhsQteNylNry84ZrT0rXCVPdvDSytIiIsfQoamI05psFYONNOjG8vMexUDoqeDCh9UWu4l9Eqdjl2T7woAN,iNb2G3nsf2wrTY4WocF1APL2tUUoZUIdt7NfNNTMroewk08Z9jGwPlJbK7seW8dRb8i2KD71pggBQAZQ52uNbCZgQxPsndQ9zHrmO2lcNqeutAD7sc2WNkLA36tpbK9B2ot6WkOsuuf2uFuiMCqCILC2vRGR3g92ZqxbOPUo4D8SoLLbbMf2sQ7liQAWvHL49LTPE7kiRQw798Vl7D2tWAvtMluTrAqKwhPvLYsFKA2fHGrYub4fKix3pVESBdQB,6Q4mpZfMuF5YRTXpRVta6rWQM3gxa21XgOdAVl0ZTKoplxhvwhJUas6BcB6I6spVwVGjzk0OPaPwtql9ySOc39sM3sre7xEpyNX5jkjTtTwqmTGcLX3kEZyS4gHOeXRKMm6Xt44BcUp4vSLnmdKZ6R1SuHJ9k2plJ4hmErqq1XinVPSVNGUs34qjB8HaTt0n7mEmg2dhLGc2qwQiNMtlxXIqhqEztwgXTl1aTXDtDkHEJRjM60qQiUiqlD9BrDHt,UXl5nJ3Hg02vjpy2moOQrJtn7DH3gG9vGifSh2MEpH7TNKkDPABoVMpNsPAtRyFK4Bjb4I52rhHQTW9QNGl1rUvlX5JysSXgREjLJ5qDUCRmceSiNecvTyzfklA8OuH94zG2CRTwo5M9qhRgLyt4RC9hj2YOtPJmnXMnggxIklUbqUBr3URC9fuG61bNjVkoq7W0OkRaCbolIwpRzCUry4zHGhiBhRRWcvS4nJ17bRjdCUnKSJ6AbmTT7G3VvhvA,J3lAVDWGQHLDn3zWH55ls1VUDYIoKj2byW8OAQ5pv7RMyn2tCYIs4wyO1HCMTPOeOXYE3ChWW3l70meBnbq96kNyeMt3zNPgWLwEow6uBgBPViEa9hXLuBzTOvxDKQj4OChdG0tQOyqmYwiaNGQrpCDDfYC1mn1aV0sEqlUjFfxndh6z6DedcFJzuqMQGhZ45lnbcgQkNUiiNdRDLpVurib2N8DOIo4blAIQRNPn5qzcIoba1mQUaEJaOEunZtG1,oUtoL2X8wBMgTw3w4M4WVelYIAVGfsYRDcE6AOE2gEl0kzorXqyeZRtudMow2BsS5JsJXhjhEeZoGjRHmJfVY4g7oPfNz4SYtiHTnpbFk8svABmYgy8gvuWiSlWdtfxjVbAAYkNr0g5lUTxiVrRROVfPDbqQWvNGTKwJjcMaDhceRqDj0u91vqyvvcTU9p2sZESIn9TqLgYGmm5DGjJAHAogb5UmfGKTjmXjyQNZxhoZzv0CuNXZGS0ASkAXw2Qc,4OYTAqlVXKZP2aIRQzCnq6KNmmOF2C2eiAX2001zD18gc8YEnMmn8SdwbFjxLD4TnHlt9IBsIPkCKFJheyWDuYNdSuyvt6zUWvcedATkIWyLzTN7j1aFVsIzOM2xrcTmG3UYN4FvgmWk3fSOOmxapmGODlAduz3lxx3lm9i1bxDTC79Y2azyprJLws2v4fofPAz7tQpArZOL9PCCqw2JuXqhsqcVSqHXjLfQ5CvCPkMnleuAA60G4bPhtc9fYl2F,hnTZVgwVNQrSdjfSHYKSRiUvpdQU3BiEqG0gbHe1gldnYsOPSMIs7HV4Ww29x8sand35hZmtzoKbBV7YBAVFCgpVfpnGBi7DiGYPHhglL1lipEtcnSXtIMuwMLpnTrbk6uHoPd3MKUSXUi8sUlXDjPAFyOx5HyNNVmyC98Qkd28VgGqZYJz1lOdRH9YfPoFjKgibIfi8NCPUNkWYGBCq1l4CWlZZpBbWv4Y7adH2Nz9zCCcBpZCytzUbQYg0Kol9,kTYD5ONSl98S9b2dIkRtQikvD6v1ZqEszsZlThvIpkhi1ZW3rHiAhFoytAjWOC6J25U7ueWDf2WDzFtvR65P0JEOwF47zvfTqnS3WXhsTTsrElXqanx6DEhGx3e0xqt3esh6HpRfmc30kHR4HvYvbyQs067z5UlXTOVVkozYPi7seZvqwScKVjzRCj8ZXIbbCglDFt3OEqHTXwqNdYrJVSPs8QqZyyXUzBd7d97rpUQ6HAH0F1qxL9LcnNwE3NuB,uS1cWrkyXuuteGtYcMyKNmlFOrLJopclgawVulkQnIhswkBUfOpOfamwiVNlZ4As7qyJOwBlzJ5WfKdOjVF8epxpbtvIlbCtGJAJKYJSRwmIQe5ROAg2DhDI6ArdsHWDsLDrNirTcLcHEvVQo9g6ylntAEEgraeBIBsrDfct73pZwd7tjOMdAbRwZlQlwlCYWG2CzCBjSdWGG0XNUlimx9vBpyydLbCMbXJgO5iqajECLcvvQjACkAM8QnB371Mw,SD3cxEUrPugB2hMBSuShBFBrD9ERSbCNg5qZ62WZm440bCJCUxa7vI0qt9qK0kiPMlJwfEPmBsg4K07ynTDpmkewOozKjvc2V5gyPGitrnbJR7RU5YGYLisjyw79cgj3EfY5v1A85lto2ssDZCcDd8aBQwuV5EHgnt96xXZnRcun77tm7SMLF7pGr9gD9EyEDtjEd0diWzpy3HxyukzTNkJ02e9xiBkaZHmtMDVectRTD6oZMwMp5ayzhs0pLZsH,2lJkjA0zl49JIEjKpd9Xxm6oktu1zARXk8XC4Js76nExe45kbTstp3KrrygpKD8eamJTFfdz2c5aeaU8eQqrhdB2xfvJqnmq7CXufZVZNcLRMjAehRnQgBsJSuLqJJXNERTxec5WYhlcnuRH6LfrJkKiMJyT9XKfk595jIiD6xdBqNQ9hNNQyhcFtzw9CzUbi1K4Qveb5yYlyjWDUf4EC7amsIQUZFcYHYyzi5E7PrWzaxycbtN0c22rAFdj77C2,oG6OnEoxfUhZZG2D7VzcPp9d9WmBd4UXX9V6ki1hzBixdziGXeVbU0lCF2D1CKLTXk68QiSTSxk3Mga3Yjt8AALbU0B06Mvgq0lC3Fxjt2g9MPe00YsHSQ3aqTpfJr2rihYuYR2bnVeQfVsmZi5znRfHY6CMlMca6zaPcRefkAGdtwrqThzsvCs1aZegb1TsJXnGqSd4YDliGyzw9WVAAFYiUS4vxoi3IxHmfwIgLZ2as3L381uFGRV7rfV9kSDO,nATpZ3jeqmbus8mZ1SVfykHU0pIvpKvzvtrrvvufu7c5tgCZYxodya6gAim3IUpbFoNGwZieFbg9f06q1zKX6IAprmdv9mWzK83JYUQux6AB4BVK6R78bklnCRDtHUsPRzdkHaeIV6HUydqRXIxdnZ2FZriKXHDifCanSEol1NuvRyMCz3R1Plp8ksXBxiaS5IVEFf059HlQ7O6P9Lg7cf2IMLE9pNePJPggaUmwzxK0ANxWRD8ErzrGL8q2Klks,0yNEZQvCCS3lxWMf3JwjnFU8zbYymRiI6DsJBl1FLc19uR061tQnfR9UJHcIJkLTI1Ey4fQrEJENm0XfEpX6uQ3OadBnS5TxS6VExzmiZUN2p6q1IKcE3CcFC6TKdFWmm3SNqAY0Q4v0FUTmt87I5BU4dpM90BrBqvHo5JErm3IT1YlSmDwo0dMsT2X3v1miAZ2XjDG3eL8RGQ70rsREChBdkTeLQQnGysMcf8MtAj8r6WSJ3uj7Q25nU1xihhQa,FeqAplHEcECiiUT62yRNYIJgXzt8aIMHOqQtqw2PMIMKd2oUtoUseYT429Cy9Dmhhtszb2AHwGzsMH5EM3Hayiy2PVgZ5dC6EhOCBkmZ6a1H9wHA1lnJCdbHbz7KCydRHCN9SChyOo4jnM3UQxuM7DXzYdAE9kAO7fgKIaRdlRCHpRJ8zaPuHjIsidQwDkGC5nB8HdRlBRk0RzT6fc0YeOL6ytx4EYDN1VvbKE1ijCDauURB7wBKK0u4GGJtZHuk,Yn7Oa6z7WgXt96stNjY76HFMrWQqwFZPkmRVeLGnZwIf7NJWlNMXWLLWYuia47o24FLbLtl6U65JP7mYW1KXfP16N4mWcQucSH1Y1wQ1eT1NCCJQXQrxz2PMdy0MdFqBzpEsw5dplWQjGftKkF7YDuD1pB8SztN6KjnR2P5wxQkp0PyfdkQJlDTYYM6wGsr6kUKycBROTQWe87UDBzCGZeQ7kzfV46NJgx5RL0GJIiBEEmYhcV4tJr5bBwUgKklS,zgPYRUQLRij3NJ1xRNbnT3SzqGs9uYwHFBu5lAis4YFbrsQ1mKPzglEAQetEOJ2RPPRbpM5cSy5Y1Ww1XmVeacPfgi3aYbJmo6P57yKHHg5J4JUPWkR1qMVoc1GE7F8MHKOYzWo2n5caAk8oPRvUL0pjvgum8Hh5tAj4nLoerpuwHz623YpU67AEJBrl74VvBeWUM5MLgD3rTruUFq94qTp9ZfSgg1iAwlnUSVBBRAFSuxGXxxg6CKBY82gVFwS5,E6sOFwHuBMCOFMiHhWt2Dpi7rRdKLKo6HAorkqair20N82VJ3b8bsqf1BJYJOisRNHTWBcDm1W2Fzc1ZXiqo5pzYnOhaKIYT1BaWharwqWQ1aQfuA2zsbQp2VQECxJ0NYB0lJvEFC8E0kY1wxiBuRhXzsd1Wcw6hgwhNTMiaju9sH0zsNIEKUgHKbgrFJUTT4QaI4qllq799QYOBNxpuC8JCpftZ7yK0ZFobNtoY4cy7hnAgxMEbp34e6zes0sJd,IJjKCoh9R3HUvqvLLIebUZeSY3IddyZafCM8Cllt64VLWdtDg34VtWGmGV63C3DB03oCEKsiijksQo4tDbFy56CCCcKzwSKgNqOFzpLBKqaELVuS0BrdhVpJ0qz9EeBLzUEZEWICfc86axa9MAxF62niUrluFYdIewaIO287kDZlLJ5ATxbRRRPH7siYKgVoER2yl1XQKEos5EQjv2vg9Zk1LLQvAtwvyva2oupLbIvXJCIG2RtJcsqkrmY6aYJ5,ezfMgVT3BD6QEXK4ITo3qnLzmwOAGZhFzNfNhbqKyPTyd885iGJosJVzL1O6uCqnj1XInTSrXDaRvt2ww76dxXYYi9mNGOk2D4L6XHN05c7lefmtEO7zuX2e3Pf8f6AyeTDKsmKPkUUt1IprG8ChTPSB373AHfTStFkv4sEbzcxZ1h4bNMpg50uB4NoGdWI9yEGub6kE0FwDvghSPdfjFawdWrCQGyJohbuoDjRYLeJpN1OAriMCYMISpwKAhgXe,bJr1PTbZjGNpNtHFvpalh98NH1MKaJ4l6BAnYcfsYz8xMpAUswBzkvMZfwvC9qdfbXC0bSZa8sUpxYj8qbEcU4uMyqFgdTMd6cUMgRynF8bq5UWqKX5HDHGwXCraReoXF7HB5BEexdVjVLwmMrKDQQ0DOxvVsDUq3gG2S89r6kyB70Uw2qxiSAXvQ7AWxoo7HzJ6VhdQKunBq6N0c2dnudxVar3EGJuzplgwBalYtlGSdp2j624AKKwutKtPYOKZ,0MFQ7Y9tggmOS2F5PNhkSGeU57PkX8bG2HKTzjEGwiFUZ1tcIVSmWYcqaLGpatGqhv69GJIwqApy7s4UkTGMzeN38krEmIOxJQjaUAlVuLAoQql2PDdPXuK6eYMgdmrUGEV0O1OZ71PyPHGkcDa2jfFxXp6pTzfllcrHk7eDoAlDdGCaQDLhohLrAfPCvwvYEb7tOYcItOAtOVXCNqAbgRMjb71sHNJU8RYtrI8LPQI6Sz5P3KftG69UeWTXKxxq,9DulVEc5DviVUG5CqHUpnqIeI98rix3ToOnWLiABDKoiCa1NlCuEf8XNgrBx6mlEMWC7gIf23rtmaCbvuu8gC3baa0Xh642fOXP8VWBvX9dsSVNrBiE3ukbaHjUHVsJgxBGPFzneoEe6bYSTf3uKY1HeJlcZuNTVe2l8iWSdCMIwHdq9CCP85WPBOfFAYYrcnO7cYuYWur7RVFO7taIVIJv3qVgCjNIMJQPWspBEAX24HLUnqU160r7tzOkBcDDV,RAcyQAPvpCRHthI8WsuzNmXWMCR8ruYm27SSSSHX3Mz73nCEorCR1wIi7cf73z44drS3mfsBQVyUIjQMKL06mRfGy1ogK9clzvasaV9OxYgbWFmkwTQPYHtwFgZwSHJjh8iPKqsgir30UzGiL2JUZnAZhYpfZWzgDwQiaqReki3DtwIA5fm3PZr5OmxQmcsQ1o43KpUTESGBRdHy1LrCdCG6J2vJ7NEWYXfvC8orr7KXMAiMGNFDoaefIUl93jVi,TgAKyIrNs7fIuVk96CAOYbBEBlvS48F5QJPNbotZrj9jExMGmLlxB7BarDhrkOGPXFSxSo2IIQHYKhl2U023tzixezC9Hfw1gucx98P8FoieRYhY0dJksMOZQP65vRRwP6pVtVEUXt2evc7UQnqCjYTPwkR80Jph1TTmOA42ylee1midnVVKrhqzE6AX4MPzmIW8XQMcFGmFYrFIF9fTERNEI7edXc07Dwvm1zZHvjukL4WyrRsMersAac7GAVzi,LduU0kcJ36Qp7mgoWWEaH9PBDzvph7fmSXkKesA09CjiVLfO5snGlUVQWMGHAmv6vo7JUuafdIoKe3OGNpphnlwhU5r0aFOb82ik2ERWeAqSgI2C08psTAdiuhzuTPQejBUekI39mTDhBBai1MQWMuP8kC498acmosIAJAkA5bOl40ov87yeMzZ5FePwwfjFk8gOw9U2Y3uTyFq9wj0trHNUrw0szF5tOoXp2iqxqYRxgRNh1vs9XDRzpYJmn6lp,wLCpodD2Fnkh5O01PtZdO4qvWeWvZ3XYkw9NyrV92n9fF3mvCrGf46N6bKReWmNWxD7p7URkHDqzfxyHTdyuuWDPYVxiC75quGqA5schSjCz6Ixb526dEGKAZZZ93W3lPtLSgHeCWXrydfgDm3vDZaNkTlv4jNwONoWbD3EmOH4gWPx6yMnbe3GzBazQSdNECK38HXdnCj9F9AIbdHTglCdN5r621FzhnNghchslt59zjClBIwVaNppe1WFcWIkv,m5Gg2n2mG0VzT0tdSzbK97JXyemqrQMh2TCZirI2rI4cnzdjVOI6OQ4tGCOLtkhcpD2YcvjMYTj37kHkj127QkCSyqsc32kidqTI9uqiwl2sOU3gZVGJ3RfDh6Wl84MZdgfcnq6GyoCdD74ve3GBu5P3k3MTyQdtT90XUZ0zoSNReVjCdm2Qt1oRMDVFiCCBP5AKVYlxVJuevTFK6ZPKxHMKuM5VdytNygkY6SSK07MVuj1oHqUvfN5yawW5oqK0,rVIT9Bt0Gjb2FjWiQ3DDfzQKeiO5qaRb8LNdtBBUJj4yILDAFIfh03lglIRbRmRciQJtPfe7k2z6j2bFMSV8U9qVQv68v0xV8IBAWQtU7TSw4MnC9vUcJT9yis9YhyHKjZVzl3mgXTly6GboLKNt9FlEk8VP1OCeWlpcYEx2IwvGnnOiWmmiyquC1V2lJEgmyHceKl6xIUUhmVlTU1F88ZxyUBgf3XlNfSoJ0HT7V2R4WlTHXKYipVC5yV8dreWv,NqPKfIoMLAGuzIOWbN9VrHToXRZL1JJAl6fnkpnIZgGjRGWjVqmCH3pX1A7Gxp1NbLXJuHMDYz3z6IaySIs5zGQyXLuXU4aHkUsTwuHyWfI5I4eGZdsW0feKM18BjAqkF8pOUh60Kp9diCuvp1NhTeNbC76YpSOMi23cWO9VWyt8ywrqGM5xwICeMf49RVNT3EhwZX4Wc6aw37Wz1yX6Awrlrv0jA2rkym8q2ySqn25oyk4qseyfxk54dQ7wOFuN,bKe4vApMzZfEk0dM4cWPAnXxlAFqg8tEIAQ9fh74cbPRQG2qKu2VgvYzaqGIBOqgV4Eiv0OCRP8YnEFB38FLAppZUKpxtaXMuwUx2z2gDDv9qrP3WIRavV1zipMX4P0GFQMu2EXLvEZmQIQfx96mZIFql6ee8yUow4HwZRG5lojaI8QjJJkbISSWinvZVAcxwdxPiQrilmUlAz9ErTLh1LSebO6QVYqf7ScAuAWVuFZeVe5dvT9NyZWhA4kBe6VP,EeT5trsIr2fCJYMZA7lWglJRXtwP52NBpCS5A6Z4iAt2WHB3m0eXh1WmAkyLHlK5Hke609Ut5fgBz1NXALb6iZra9D8TmGNoByaC2nql6MgxdcAyPYAFTTLgziR2yKjIC1KV3bSYBFhegFICFd5XtjlXKzLP9upPoXgWhCg4gR7kj7zYSfYb9QD2MUfes1O9plxcSMaAFi8bLTsZ1dLdfYAne6V7ze9eKJIpxSsfjOUhI7z5e4Uc0N1HhQOSxVMk,qtfeipEbuJuttj4ujmKUaiO43lLPIjgdFMbMZXWZ8BumoGIPFZCgn9UkFsnZkbVJNEP45vGIGJMGkxZBurj8BIZwGaKpUw0P3AWF09NFyODIX9jhGzjyxISg6LYSa5x6jVhFCZZ7rM5WqnRAK0jUAq8Q5OjclfpJMHx7zBPI4NcVDpZbw6S94OdYrSUkN3Ou4UikTHE3BbPkCKBRKdRtw9QTSDgkKde3ICRIx0cw2IXnV6ihbAVwUfIMJNZxbRhq,xsqIHX3E26qfQwiFJ9m7ajAmJPCfYZk7ZqGSWlREzhq2kavgBUXXbAZ1DI6sPV4dn1wW4jBPAZy5X22VtQ6NT0crfc1mKhbzIL4cMx4RBpvdxWcRScWXCTgGVbNSWZylgk8XO5u1SApxbs8oBY4PThIJPiq2fLx5K4UDtQjVbuSJL4WlOeB6Wj4toSi1x27KaQW1HEyRak9q6qaUz4fQlMEe3VAB9ycXz8dcNmPmgWW3bp4LIKhQW5IhDVgM9IWE,Fgr3e1dbmr5tGhvKszhpbSPX9oztqgobxdlQTGUrTPs6ZNVmXmAQ8eneK42Bd5gdMNOTkLoHZ3wvAEZbIzr5wL3Yh5SXP0JPVBkQ6e4e8NrDJXpNFRgzp7kqrspko5bh0uM09Siref8xNiC1bTXWu0N5m9mrS54LYNhC6JYmo4TWfqklF5KfJZwTHVZQSS7CAjv7w0ZziFORzlDP6w27MRrvtKgR1kWue8sj0SwzrrX12yTYcs3Q4faMcVQEQ8mY,KGQb90pwHTd3xZzaYPwSyOfM10KSlvaTpc22labgmd3ZAwC1fWEd6Mr5eYMWX8QdIweNipat00zvzE9dS7tVaO94U9H9ye9nPtW1xcLryQxZCjQq9uKh14Vauwf0RPl7vak35jgMQ65PJuckxQ3mEvrChHAoDMeWdX3RP3PjyTMh8yoeOWg27wM16jZTLrInPFHGAgkSnB97aXiALuHqZ1afGBx1zToM0ccNinTn9eGil9iKcVu6e8K9PSFHnQXu,3zoq1lViIULlCQZQMrq3I3qu2rEDRnFeMPNYBUvgSSw0kePXdOHEwvQP8Cqxs2TVBh7bX6iqK9dD0eNge57gBCcRK8zWI84OW7riH7y9ak5Pd0GL79g4BIZcO51RpeTP9YaT85eP4T6RLNR5GrWRyXDrjcXgUSyeHp6vALA88KAy9MTT2JY39n5a4aNqBLjyXwtt4UIkTJECUlrnzNtkVdksLcwpe6GyZOzbUsgWjd3xAO4LbM9q44hZVUNxZQmX,uSKeyqVYGEDQ4lOpszXGeoOCG8RAGVeqoq2VBuUUz4wH83F3HAdxaiRM4LO1OjnNYVJcUE0OQokeBYj0CmfyPmb1oodjXSDW3oIKN2yiSg6mI94affVdJ5QfCQLsVc7QKM5pujdfn7LGIPCCd17ZgvIGtPTfHZDe51mbgvhsWFB6CDeyz5TO3MRKBGxe7ssPFQT5mAWuJoCEzy1GZU06oaing7uop6dL6igulXS5BWBgGrZmJ6cJrvrNCt1jA4aa,cpTcFt6iSah7G5UyzPyDvJIklBluLB1uYw9kNlYNbFanLPFJV1YE2IoCflpUwZWvM0gmyd1J5rJd0jEoKleiwy48KRuOkyFopUQMthZH1XQBvOhkrFb0YDdyX717BH0SXQlhLAZ43NTlO6HTNBrQpesfvw8CcBZLcJQnGrZ9qfipjX3vXx6KT4diypktOAvaKK6vyO9pPuYH0qihC4CheWlBvHF6m9VQ95jG2YF7U0B9gOh0TWb0ZCpLSzRCMc9f,2qXtlFh6RPpj3Sd8dhyDrtIpGxyajFXe3zIs3beFJMtcffRJw7FfmfyaL03vdFAmy1JkSAmI7MAX6wlfImiBD5N5y7SLmS6bnx810l9pIpXVRrlbojcajSGFSRIN6VcPDwGClpRznCGgs1cLdDhvgfcDyGpkOi1c6kTT5Ev78q7w1NPFBNKT5oY3ahkRehvsd1k537XYr0clEmVodKVU6TVRjbYCOFFUkMsM2hdJOrBZ50ieNzITs5Y43N0uM3Ll,OPlrnQMs6MZz7zzvz9yyF7eTEo90opSUkeVBmtFUVKSLG7fMdofLeSPMEYaSxF1tomy9Qy362OyucMi7OJBYLegzOgvxQA81feyg3eMoknKWS0SijXhPoiyL0Q5cYA6ayilSJZbbzQYzk5jLYiLipARyKxC014GzYw1QhCtxnXcg7xjx2foQhRrvgZyboSxBaNHS2EyLecyMx8QGVX7i6KwyjTaDo5Z2231Np46pSs4RMeOgxnXFGGnWrBjc3EoV,FoZebM6MWvRpNpBP4NSvYAxPzlVglPFqHdf74mwFSp5I9qNi3NBJ5O2aQ8yd94RBUmnxFr4YDSEVnswVpZiYytRF3UKPsbb74kGhnfMSdSOgNY0UBZrgcKypFzThY3t4xTwZPcVUtELnjH74PzOIXkzyt2nvTc5anXVp4ish3MgB109pKGOjkkFc7S9aAuifq5O5beJTfq0SqFFUIvttXwf0M2cmnYP8YLRO0RD9cSk8PDhG8DsDSIf13RWU9ngx,St3volpPGd3pUvpfWWCS6B8VrwJNL3cQhy40olhT4dBTuh2T9UPgGEnkKsKY4CdBwNrKBk1gOZw4I2Pzfhpss0G2IYheRlCJsGMaf7YT8L72lUv3t72GwEPgk44dxsHSoZXW027NN8bExdf6EDycrAQSMmtlTxPG8AdtC9RoYUzCvqgjoqXpOs3bXCvYvBucpe1l77eDhVWbOROHAW8Eem5Vdb7kJj6LduPconIPiB3OyED7m3xRCJDAYOhIbJ21,VJrN8N87788R3Hjb0gWm40VvACJIQRuFst5tEIhMSYG24iwZoFlFoUOE1EKzio6TWkYvgKiexRUUnaePjwnGyphtXQ0VcCoPztJXp8WMFV1iLTQoMjxQ91ikhlthTuR0bBZh38Zrln7rlMjdshagIfCs1Uftv2eAu608SGwcv4hfZw0ZVSmlQZyiBLnpYR67TfM58JLopNyP02GCh1LJqSrHzIRO91ULdU6D22tIcSEXGpkE806FVufK9Y1BeOzq,4P5krWRDwqbTSWSfd38XwE5qdtFuLXouiHYlCy5sBoyYUrWzFASsUES4lvLEvZJZjEvr5PflCJWde6JHOS8sWAJS6GwrNNS7sAmWvIvGz3K80MUot3mYjeovkxcOVzVDlwiCiMFNjEvK0h7dNBqdmAYmQLDQE87KypXwlyKIp35bOJgNu22bJT2vuoCaqxhNOSbTG9CTmUFITNX6Lhr9OloihASe2B4mceY4pZQOMXRibfo4QMqeQLMC0k0nyY1p,RgqguF1ZbQLYE4XsOE9psV9Wb6e8xNaBuxk7t0yOpq054wA8umBZqjAOZGBWVoP2WgXD8hnXTzt3TSElIPkizpXTrsWJOgdlTVMnqXj6OmfKajui592RX0QWbywgrroQFSoP4vJQ9nvuxf2GzfzKDc5LCjeVZ1T6aglcUiY3bcQwZ69zbqfUSgQaSHzot8gOkPlJvNEe12sG8ZXTCFrBoPxruEy71PDn2nv9mkMCISIOIW8jDvQdds1bbz2UPwGF,u0EyzxfzHHbWITqZd1fcgUEGaOWpoTA16cmz2PUs19xdzagSSY6jNIaSYfqSi0vEbkITZy3RTNBZxpQXR4OIjzeHGLTOEfvODkd0N8G1SkNkLMIRyHf9ULVBWBdWIwRxJ5DtDlG1qiBxo9ONQTW0eARr1679p5fV3KNHyvCmod6vHOD1xR8UxqZMPIfF6GG1dhF1myQNNnN2J5oOdG20NsrGj9GKlYynHfidI5HqGkqFgrKCY2UTKbYIPYn06J3e,n3t015kXYYBgB77RwtbduygEqoD4YlffwmKSlMRvgIO1ZnadV7Qmy5glMhkz6WoGxqsbTrrPdC9b0Z2Qmd7VCn0HacigQtJSQ57h14CnJMXV5jCWhvRLQoA3yhAwEsP3Pxf0mf4PipV6dN3cSXD6demJqpJ4PjaCqOMUEdu0e90EozbljTpq5EnQcjaAzb9j0ALn8RHwn02fLzvyRsmgB7WIqfQ9VWZY6PExfoxGAuPOhNJ9vGpVwHs0sxVrz9na,K87XsQdYgkcha51Yi1mSaVaORj3lgpbGP5k1WVAwvjoOi4e7U0D37Ngqxj1IdTtFzOXCuKVCtPzeQ6fBit02yAzGnJYEVEo8UJtEmQWuigprqBVlbWrmt9sd1ghEetYGgalRkDlwz7Ah4nnjUMNTzKcMazu1tfnClNhXZI2kxyWs02aqPlBL0ajgWRouDqi4inGjjGha3VGzYjKy80h1e4aaKKsAnI4xGF6h7MyhjTpwNMyueHow0h3Fs6RELP1a,KZ0jldqiVqdKNhRtgTlFZQ7Em7PIFgUa2MK4qEo3ybPQJgA1tcvVpxrAvH7MVFm9K0WVMuE7Q0jvcCZUJ3LGMdncRbXgNd9WZHp0pGYRmhtZc9Uy12waj4XdPFUJKh0hJ5CvjwHVQSoblbJHDiTFM2DxANzsL0vq4Ttn59BKEXF0xlfXe2sGTnT3TdN4yP1fxcM4xZfqFfB9mtJWoXxEvF5wGnfFgKHuq5ebFqJiA0qR2At7dpw3rv0vz2xTgWPD,IJh42D2in83ziNVoT4iQuqtVaMJ8ilSNTaA4RMZ6NMOvmu7rUtLYNo3kmiytSW5mN2sRS8Fkbb7W0sRVoMKSIfejZaIFPXT4Gx8NOcwjwKr8hD8kzDg5vfGnNO1cUZF7cShCTXYZW3rm3IUJwBs16qGCXF7RjWYPyPjGwnguiRbzs93XkNoN5cnlptkkt3hDWC3TN6BAIHZcQt5EwNdFey6hA1uuGQEw5aTuYDBnYJxUeuWLqmxgj2uzu9HWh6vh,iXCV02Z5b560pZW1OVMUgYxcQEKdxdwqONaPjpBmrExUorxrEF9v7gH6mQvXWzY1mNPM8YofObujuDKs5tauuU8ToNdMy0dm2kFb5f2pZZvetr2n8NzrRuyzrf8TzPqxek9t7YNnUQewNmGWcqwezyNklnWkEAmEymmq8D1W8BO6D84r2B3xGYEETwrwbnj6I8wgygATMXP1p4x8MhS9msOIHm4G2ah3I2z4ZQFXzeHY51niANZhLWvUUnGKSLvm,oFpnXMHGyJdT5OyrcLbp0KO9JCHGlJ2pl7d4Cwc6bhN1vW0Eu3Bbbqp7v8eCMeKq6oI3XqSl5cLnIHBbWcCeykKYC5Nt3q3gQlSa1pkoMX0okktQjGFNckwMpxGrm9juG0NBb6aF5lGZITEYg8N9BodR8Jk0vaiHeOr0Aw7wrNVY0E28kgXBFxmmGKBxoL3yfOhUoin2cJaWmxnaT0x5mUAbpEzctILcDYwyFQ8xm3HN4yLjTjJ3cDMGLuqU6s6A,gF6LLIOJG32A0AO9wAu2XiypQeqrntr86bX7XmZ1A5i9Zod3bFlZpIKaBcu2OhgkvFi8AiNJXLfE0zMhc375UlcibesomIWhSfniBWFa0oCQyLQfsXCJwnLRErVz3t23qnlwifvFoIXMCKc3ZqmdfyM9NBSORhAsD9CnKv5gbFDxjvzuzXL3TWmsei8mwPkVcFm5riTDaBEmAB6bokGFzXCa8TA5bKbXlfBhR1UZOhR6PEjWkgBsdMBTCmrG5ue1,sdERwdfu9tGCSlvfgoj9HCgEtGcgbZjHUHy7jqZfa4SntPq6VVKhRBiPy6B4xmj0sgWxfResNQBq0o3qAQcp9RY8yOTxFd5wZdc4583YAl75b2xDUWomZeqai2CQAGhHuqlSAeh8UogFBOML9CGglIvy7U9JLLlpTenplMmegOIshatuGgcYMG4APfnAZoku0ZHZAzKDcrCZwKVFvNr9zvlJzgyFCegq87mWP9oAuk38sGxHWQQyYJzcjm2Jid9z,BGl2qAXWqTrzbNuAEuj9G2B8FJ0VMbSML7ERR64ko9WK0kOaQnAKE3NWer8dNvC2wUw8aahyf0ojSWnRiPgl1In5Ms6PcSigvXDIujeyIWdeGfXRM0xFRrvNhfHgpiM1CS3levDO7xB3gTC00vCNaKa3h8IbYHeZgNx75qRif6w7P94ptYiBQa7FjTl35S4Pw6ySfl6QfeAqVLi9xQCLLpl9HSPeqkMoXPPB6wzOqktHD6SOO1okv85pB9ToVseA,0GOWhGAt5Q1iDotAw5TKU0F5SjXzVWIcZNRMNbjlQdlJX0KegqftPrw2pXLd1qvgjpjU829hX3b3PhootkFmVdbUWCh4V1f4nCbu2ZpvuEicJms3wjhC2EUdgOBAFNjlDPP8IRlgJo3OtQOAi7vQcM8fv25yhb63mQj24U12znRF7WrMXj0GMnk7xR6oFRWvfgQbkjOgnIIi3hEdtk2DtA7xuvZD1U9ozvIXxVClzxpW8DiAvShDuud02p2SS9xu,r9Q1Xp0fQRczmkxeDeJsozwb5NE9nVAiWIhDaISUflfNBelpXBAeJ36T1rI1Za2YITNE5N7u236q1pcLfnpJQSPO5KIkwFoHXobl2noccwuBneSMnwMuQkrjgLEXbyVMV0TJsE8AhaKKroggWvGxua0PmZu6kTPXv12uw91LUW5fYw5MwmalbA4JTdUdHpa6t8VsV5iaTfclkMJNfExh4FIXjbV9P0O5dySRa84RQYTDoMq1vdugC6M5IogqS4Cx,HOyeMlcIQ1AKm7MtiBvmuiK0FPPugubTQ1agybaQmWWO1r6v3vTvY5dNleW2D2mu4DIRX37MG3hTEuCzs9RWkNbk6Yn4xstwbEbAa41ihg1PmtikcKh849v7n4F9tWhFPVEMZ4RNk2Gf0nUhZjTq66ikMYdp4JD3g3kafKw0p1zCjmfs7A0JHGUuO1CfLxzb5AFN4LwBpAEVDkTfwJlVAc5wQ7BJtL4UG1vrBPRiE83tvJ6oqB4PR0VPczWmGnfr,zspSoy51IqIo8YBqJF19A8QiInZJPBKiWKUhv5zy5NgE61S05ptFkbdHqH9Hx81gPZdUviuMBvt8cMyvDcg9JKlpfJFE4vnBjrF0Gekgqbczw99d21fwgFyvFcpJN69mzICDxCk0a7gJF1tXlCpRHrAigT3rGmmUIFbncsSrIUZ2eoQp6OkLsnCJ3XjPzP7g1KjwfkckKvb0ja98bH1data0FhmqVApGvOTNzZ5N537RZ5FtkdjtlqLBUqmhZhrE,p593UKGRMlek12IbWrI7MdesavvD121o3CuiLuP5HpVnH0UcZssVvWDnPbFk73cCKWNrzD1fUeYcklRyYSfjrncodZTLvaYmVIPwwTGqTNfwXqUCg85JZLF3DNIGbbcFpEmLYELNWhC5YCD1AmsuhHJLoD7ff56EoZEPjG55nJXMf2fW6renAKL51unzExfmsdgWj0x4gIfpE8YGfmHqNtr4opZSz2ISM40mVcJ1WJ1aUN4EII3RJ2nxDMnNUmWw,HgdrDzB38OSxL1O6JWmySeHkleU0j1LdQp935psSkrsi6AkIqXUXcXxC9P9YPeH0Fc8dPHpoI58zxbgoLlJhbloDNBM36X5RS4K3HdGzLOtYpKsmeJVWhMiMmR1tsUf5cIXDQpnoTaLKFYVx9qx5k8sgkrgS6W1tmN1XRO71RX0qrVfGoXwq7DfWMXo9gNrYnbhHxwktkHjLgcQ9hzVaVH4ejN2bNgRInrSSs9QNlbPcQ6sKZHmGxk7J4uB1ezfN,OIapZ2ekdwMvnSCV8761ybIgQvXhlBwjcjbzD54Fzk3k1nLRhsndToAoeKjQnMcAy42rEUWwt04J3tdyyBzGITCCjNYqtaAi4Il3XQm78QK6nLZHIVWSTFfFDDtgJxtcGsFQYCWnTjgK1P6p1hMhlb28ZIechgNITaV7YyFNPAClvTTnvxAj04aaOvwg2VOWs3bCoc2aTZ2j35Xc2kNcmMfWARtcDLqJpCmVTftaEvBfcrfyTnVWwNHQreXx4sqP,PodE5PeA1BLs6P0yEPO2wzTULw4S2QAtWrLZwsE4QXGJyvxBfi1ToGjylSqamHtMZ7M010sMVRsAKFNXTSjw1NWoDaeAcwDG1Y6aQFAoRaTLDlbJkfmdWZ8I4BugHCFCxbWVscQNwi9sx3U0uy0GMpETZqvenL4d28EkVHRKmf3Nu4qdCyHFp9zEHXpuEwpqchnLoVPuLxluz1jrvi8HR6nNwyLLM3aHSKceqip9mLCHIuU9LjUFt5VAIECppvVM,M6pjgIF5qOse5Rfh3vOgWXpsIm4a3ascyHQlNzOzfvPQtFimhKNXt4pYDEUXoFH8UDsOK1zfNvu4zsfwjRajXufPSBUraubITvj0wtroDJIZ7xboz9GLxGyDhleLvsBP4N5AUIZYyvIQiVA44pEMzTKAE6fMx1uGP2eqFqdGj2LWEJw21Xd10T5IVGpujCKw3WPskqQkl26puwnMg0lCgvGkXlmLi1pvJXT4kVljEOGVpcpB6H03DbQXPp2TXoCV,eZQQONSD5Imz05gP5D3FZV0lJgpFszFssjN0Gq3fN9D1rXGMcI6XDvckkRtq8dlDbXDr3QYQJFqITJFLNx3TPIQ2vaVNIvjcWfLbxGJHms4esDfixWeGfUkvPfEZFi7u7Ln2V2EqYX1w8bH4VG9VM01Ls7q3LP7HR1Iee5gxb0fwyQGGXlxZgMk2awELzGE1B0D9YJzfzSVrlF6L65dwO6dZzEgTaUhndXtK9BICjfHo0uYpeAIR8B25wbNd1Jo2,X0FirfBI2YYSdVmLWgC2EmLZZmr9HDMFgcb2nHowtHbXQeJUcQU9xgeOHl4YJ64aXFnvVbQwZPH3uzrOWLjNfSncjPhz7EH6GGAAUASaRa4cv9D3pZZ2sTszn4SSbc1HzjqjNWHJ4aBEPg6V2DcCYQrdS7KOgGhTB4oGAX20sjd9Gjirp2APeQKz1HEffIF5ToUppjrWxjrezPyLcLRvh4JarMMU26BPYYeae3uPbEONqa4r0rqFeqGqbq7RsKHk,Rrjj0urSmn2HUnrJUTKibltlVzETWbuHTdyP0dOPWp8MQ3UsAvHJEL6wZ9ohTU6EFCeP3h8jejW47ymXV7EtVsjinu20uy9kSmwXxtOhnt76rNAD8sQwmxZHvN4afjJw9qYjK630ki0lQuGdluM5LkFQSYNupxMMG0QSl6hpjDrkoMiLoiOkI4Y1T89yGZcdohENrwcEyWgze2VLUepf35OIcOTZ8PPsCwirwzFmpoCaQnyXkAc96nQtbcri5beR,IwQ2mh9p5OMGkTOAuZLMmnYUOcv7tG9mbXlPs53fVm1DrmKXpA2FwQAV17OrfgFaWrggqpBhxbujx1TSrHSYkW0fi927L7f8MYUaqsu3vwzJ0Qw95IO0UqTLoz7JHKa9WlatWXRTIXeFeIySTC1DUpdqQxqioh7WrPskOHTCsE13quli0J3R2vWMBfsA72cUsFaMmlnYYX74uwlrWmiNo2NgnNZwToh6X3gE02TYgd3B057QIwcJ0BZ3UQQoTQmy,i1xxNhGQgvI0xcseifoLLFx6L7sJL4YEIt4dnugzmgOJ2m4CvYvya4cFzqUPzlmcjVlSSlOk4UZq7jATISA3c5mCzIBIYwCwC4c0Y4Ww9G3asDCegZV2x1bZ3136Kkcen0bxz2vIhTosxNFAwdaU5v7fLya7OZfSuZyQ07qKdOlTl5iMBgDKNwMXr8aLz8QNdYrt3wpEUxVux3iosEK446AHBfC6qL6Gc90lKJJrXTYgxxarpp2AlO2xf7WrQ5GX,0uT5OuRE8KY6bI42ro8oGQ1MWZ5ulgIixEOn0Ljx3Mqv39pe3tkbdsxMl0J7eFs9kSLlxaN4nDu1mGm89wSpPQMqj3plnwdVPNQ4UguS2iSJOmmszxv9YEqPAwsiMv3bKR3paPxy1QdE20eAPPa5bmp994mBWLnuL4ncvMO5UNapJsCMmYBlHeEpwy66Bca03GADrQO0pf3V4OnZZNyeiJ6k0XKd8dbFoEF4RbXwlZFjfRCtXIxxz4EeFcCo1cgi,3C1XTKBfRx6WsuYZRCOiEOlRlcqEyrBuhKrDlY311sMbkPeR6jc8nj7DWmiEY89Y50IgEi0jh8G7ZoCHnviRTlM8v24QpEV4nQ3KmaVQ02to6wVZ0hzpOzMos1uC94r2mptjN4HDHcGY6qkMgwAk3Kkm7nY45fjdrqnjVoHJWtGrnKQemjRPLnU8VNrNEfH7SMyU2aqzQ0l3YhKUrrLeCha6VV8bYxMAKRLrPVXrqy6YRMmsLFW0Q7cVmOpIlHlN,Uof989JY70mfEBAhPIeNOm9vcaXksbW5105zBka0UCFHLard3OOvdqee52IJCQt2vActbd0xukPNIY8l8k44TtlOUt7GcH4wwaYURTJzyD1GxPFGrNr8F2MmWSIs9ML5onEkowP3Y28bDweR3e9C1f7aOhpnGLhGEpoxnB4t80NkOci72Jh8akNB3RTXiprJg0sEHjvgZtis7XEiULvQ62klHp9qB6oO93pXdcRUJMoM2NZStQ76Wt3f5pyNfOVZ,m1kxeyIrM4csWPwyKxCAD8rchwDWvb30bJkehEynzbWf1nIXK5l2tGWyv8WAOxeyK2zif1Y826rwMQl6PNdN0WSN2WAODgaiBExcYffmHelvoD3gjVzzSSG2HBLRmbsjef5Hf6pxKuCHnXSL2CfRmsz6ntGNn2OfFPwuo0WeGaYhVr5XvcXEHiD4YFMWCakVhRsl1F5TvaqJ46r3phRFciAjXpcR1cXG5R72LzGVgp0b4UUlvQFqFiacwz1hK8rb,0D0fxxgmI10F2PjznWC1EagUXHFcCz6xVU7lbtV1dd3uKDPGpfPgcisKFwfoG0qM57Pgu1laGG0LTevax40tFdJTA0nMEDvZRUT4B1ZcbujCj45RnNGzW8jsrULnIDgEtCNonTyLeXH1iLhH4iRIaZZF8IJzisnRJW5LKyBgrXFvV7O2PVhG4RbxlraOPniBI20pPX3MgRl30Zt1ucxM5QY4V04iBUsNWb7kstHSaDHxEUYZgOwLY6uErAhglXo1,U5nFWoQlVT6UM0v4dzueT534QiSsrop3mOFQbUeW9LWFnIuUzDJXd3a9pzweRSzzxOshLRJ5URPMIhQKBvewGf2OjTJMwDVeZDUspGipkoBKF27C2lc3H5NkRUVHAPQMCcEO7YX76K3k0J2zoDAgs8h2f0MannZoPDz04j0RejAgfdcqhdrV2Ir2QGDGvWPfX7TIOMcQQxfXR9xtMK3aZjd1S9itOODkTbbheMIj3DjwhEOjLfOKiqIzxO8gYn0n,jVVwG1eYFPRTd1if8ylVSAD542jVOfDr6R0scChI9XsXN3ZbGxbWi7IoUWZI17u8T3VbnYxjlrY6MigKVtahTzfjafdCNXFSsujKa9raD5hbLBfb52z8Mlu0zXQlf2ZPHwtHOcnRnvmsknSEtB1bGHoLqnzs9GPpRjO2XnfV7pHeV7TUlcgFvXY9ZUYZt8Him3NKOgbc9Jtvhr4YQ6SLMFHgqGFaPEC7vtLqrvWx4cia2PMyIfFtSK94mY7ud9ww,2hNjSpDAlTATKUNn5peeurOOBH9NXAFdvJCVWhFxghhFQZBMmYqo5dhsOH4Gw4u2LgFnHzMV4RoCYW'
2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [1, 2, 5, 6, 7, 8, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
,2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:5E835EFD-E820-42F6-9814-E20DFCA52E02
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57130
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
,# setup
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.session(_:peer:didChange:) peer:747F7346-E94E-4725-9519-7DD504D607E9 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C74A0AE9-6315-4D36-AD81-D0771BFBCC0A
[ThaliCore] Browser.startListening
2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:20:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C25CD1F9-CA63-4B0C-9A5A-335781DF3,7,1B
2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true},) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertising,StateUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E835EFD-E820-42,F6-9814-E20DFCA52E02","generation":0}]'
,2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5E835EFD-E820-42F6-9814-E20DFCA52E02","generation":0}'
,2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
,2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
,2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:902E86C7-8216-4B59-A5AE-F71A1F917619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
2017-07-12 13:20:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}]'
2017-07-12 13:20:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}'
2017-07-12 13:20:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C25CD1F9-CA63-4B0C-9A5A-335781DF371B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
2017-07-12 13:20:43 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5E835EFD-E820-42F6-9814-E20DFCA52E02","generation":0}]'
2017-07-12 13:20:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5E835EFD-E820-42F6-9814-E20DFCA52E02","generation":0}'
2017-07-12 13:20:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-12 13:20:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E2F1ECC5-9D10-4C9C-AFC5-866DF5C4FAFC
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B03B2F8C-999B-4FBB-A434-7BB95AD492A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B03B2F8C-999B-4FBB-A434-7BB95AD492A3
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-12 13:20:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-12 13:20:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-12 13:20:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-12 13:20:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:b2ea400f-5812-4cef-bb84-eda788d3af17 error: startListeningNotActive
,2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ke2oYS1SyBfImZL6jHfL5NP5oDG0zPGC","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b2ea400f-5812-4cef-bb84-eda788d3af17","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b2ea400f-5812-4cef-bb84-eda788d3af17","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2EECA91A-A35C-4003-9FC9-E7CEE4D957CD
[ThaliCore] Browser.startListening
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on star,ting
ok 164 Got null as expected
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"comoz2I5JaYcioKmFPUNGIIpShZx0mBg","error":"Illegal peerID","portNumber":null}'
ok 165 Should only get called after multiConnect ,r,eturned
ok 166 SyncValue matches
ok 167 Got right error
ok 168 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:902E86C7-8216-4B59-A5AE-F71A1F917619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
2017-07-12 13:20:48 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}]'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12, 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:20:48 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CFD1791B-DDEF-4191-B0D5-6334523B3496
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:902E86C7-8216-4B59-A5AE-F71A1F917619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
ok 171 No error on starting
,ok 172 Got null as expected
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SehmjRY5XUo4TI4gZnlm3y5lV3u1S4rr","error":"Peer is unavailable","portNumber":null}'
,ok 173 Should only get called after multiConnect returned
,ok 174 SyncValue matches
,not ok 175 Got right error
,  ---
,    operator: equal
,    expected: 'Connection could not be established'
,    actual:   'Peer is unavailable'
  ...
,ok 176 listeningPort is null
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5d16a19d-be30-4638-94de-1f5e45967e66","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5d16a19d-be30-4638-94de-1f5e45967e66","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
2017-07-12 13:20:,48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'Coordina,tedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/2BF239D0-941C,-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:5,67:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settleProm,ises@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-07-12 13:20:48 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios,''
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
,# teardown
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}]'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:49 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:20:59 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
2017-07-12 13:20:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
2017-07-12 13:20:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:902E86C7-8216-4B59-A5AE-F71A1F917619:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
2017-07-12 13:21:04 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}]'
2017-07-12 13:21:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"902E86C7-8216-4B59-A5AE-F71A1F917619","generation":0}'
2017-07-12 13:21:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:24:03 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-12 13:24:03 - DEBUG CoordinatedClient: 'test client failed'
2017-07-12 13:24:03 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiC,onnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"3e2a27fd-55aa-45fe-9813-64f7b6e4a161"},{"uuid":"71182d4e-e0a7-4da3-bc25-0736825c855f"},{"uuid":"f57f1c,14-6a15-4d78-99d7-2450f7d50b44"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/2BF239D0,-,941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Applic,ation/2BF239D0-941C-46D0-BDCE-2D12F7D5AB99/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-12 13:24:03 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
