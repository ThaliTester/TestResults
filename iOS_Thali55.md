#### Test 113351851fe156cf_iOS_Thali55 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of N69uAP 'Thali55' (d7a40d176e510e468af45ed03d4ca45fd18dbe43) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/110CCFE0-CAF7-4139-A06B-E31C5F42DE08/fruitstrap-lldb-prep-cmds-d7a40d176e510e468af45ed03d4ca45fd18dbe43'
,Executing commands in '/tmp/110CCFE0-CAF7-4139-A06B-E31C5F42DE08/fruitstrap-lldb-prep-cmds-d7a40d176e510e468af45ed03d4ca45fd18dbe43'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58469"
,(lldb)     command script import "/tmp/110CCFE0-CAF7-4139-A06B-E31C5F42DE08/fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.py"
,(lldb)     command script add -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_d7a40d176e510e468af45ed03d4ca45fd18dbe43.safequit_command safequit
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
JXcore engine is started
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2C0913B2-44A7-43E8-85DF-B13CA26870EA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2C0913B2-44A7-43E8-85DF-B13CA26870EA
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2948243-92A7-45FF-9374-B0564194E89D
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:779FD2DF-2561-47EF-A478-8805E781C9EC
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-12 13:15:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of fail,ed tests:  0
Number of ignored tests:  0
Total duration:  1.557714879512787
2017-07-12 13:15:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-Thali55''
,2017-07-12 13:15:33 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C3A4F8A7-2B3D-4360-8CC5-039EF1F75DF4", generation: 0)
,2017-07-12 13:15:34 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-12 13:15:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-12 13:15:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-12 13:15:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-12 13:15:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-12 13:15:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E6,5-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:19:06 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-12 13:19:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
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
,ok 5 should be equal
ok 6 should be equal
# teardown
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7E088A57-B580-4EFF-A1EF-53D433BB763B
[ThaliCore] Browser.startListening
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
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
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D35EE5ED-7DC0-405E-ACAE-E55C0B1D984C
[ThaliCore] Browser.startListening
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
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
ok 68 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
2017-07-12 13:19:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8770623D-243E-42A7-A829-76E638E6B089", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8770623D-243E-42A7-A829-76E638E6B089
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "60F49A84-CDBB-426F-9CAC-8CC446B7744A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:60F49A84-CDBB-426F-9CAC-8CC446B7744A
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "60F49A84-CDBB-426F-9CAC-8CC446B7744A", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:60F49A84-CDBB-426F-9CAC-8CC446B7744A
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1D34F925-0999-4B0C-A7C1-80153F143540", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1D34F925-0999-4B0C-A7C1-80153F143540
,2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B487126-3132-46DF-A3D0-5047712FE,EF1
[ThaliCore] Browser.startListening
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28D672EA-BDC0-451D-AE1A-310791B29438:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28D672EA-BDC0-451D-AE1A-310791B29438", generation: 0)
ok 88 peers must be an array
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D34F925-0999-4B0C-A7C1-80153F143540:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D34F925-0999-4B0C-A7C1-80153F143540", generation: 0)
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4
2017-07-12 1,3:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B
[Thal,i,Core] Browser.startListening
2017-07-12 13:19:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:29 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
2017-07-12 13:19:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C0AA7A60-8928-4575-939A-3DB9D261CAAC","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
2017-07-12 13:19:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C0AA7A60-8928-4575-939A-3DB9D261CAAC (syncValue: tz4Gnm7YGbN6o77c,Exlqiq3lbp9IX0uM)'
,2017-07-12 13:19:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-12 13:19:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
[ThaliCore] Session.disconnect() peer:C0AA7A60-892,8-4575-939A-3DB9D261CAAC:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
2,017-07-12 13:19:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"672362F3-126A-49FF-B6E6-EC96571CC220","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", genera,tion: 0)
2017-07-12 13:19:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tz4Gnm7YGbN6o77cExlqiq3lbp9IX0uM","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:19:35 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'tz4Gnm7YGbN6o77cExlqiq3lbp9IX0uM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:19:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"C0AA7A60-8928-4575-939A-3DB9D261CAAC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:19:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:19:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C0AA7A60-8928-4575-939A-3DB9D261CAAC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:19:35 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:19:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:19:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E59712F0-72F6-4566-A8D4-829A16C30569 (syncValue: NrvYuwpggRQ8msH9WRyCC2Sn3pzV9D86)'
2017-07-12 13:19:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E59712F0-72F6-4566-A8D4-829A16C3056,9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57257
,2017-07-12 13:19:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NrvYuwpggRQ8msH9WRyCC2Sn3pzV9D86","error":null,"portNumber":57257}'
,2017-07-12 13:19:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NrvYuwpggRQ8msH9WRyCC2Sn3pzV9D86', error: 'null', listeningPort: '57257''
,2017-07-12 13:19:38 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
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
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57257
[ThaliCore] Session.disconnect() peer:E59712F0,-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
,# setup
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1
2017-07-12 1,3:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:94152475-F43F-4A3C-A4CF-D8325F74CB82
[Tha,l,iCore] Browser.startListening
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
2017-07-12 13:19:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","generation":0}'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E59712F0-72F6-4566-A8D4-829A16C30569, (syncValue: DUcEgMEULayGOqfeAfIvnlBLfzKb0QeT)'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E59712F0-72F6-4,566-A8D4-829A16C30569:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"672362F3-126A-49FF-B6E6-EC96571CC220","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
2017-07-12 13:19:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD82B37D-D503-467F-9AA6-26A0F563A03B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
2017-07-12 13:19:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E59712F0-72F6-4566-A8D4-829A16C30569:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", genera,tion: 0)
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DUcEgMEULayGOqfeAfIvnlBLfzKb0QeT","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'DUcEgMEULayGOqfeAfIvnlBLfzKb0QeT', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"E59712F0-72F6-4566-A8D4-829A16C30569","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E59712F0-72F6-4566-A8D4-829A16C30569","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:19:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD82B37D-D503-467F-9AA6-26A0F563A03B (syncValue: vqhWeRn,MpStMj2uhYzQpBd2SXB8r1fOS)'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03,B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
[ThaliCore] Advertiser: session connected Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] Session.session(_:peer:didChange:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57262
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
[ThaliCore] Session.startOutputStream(wi,th:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
2017-07-12 13:19:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValu,e":"vqhWeRnMpStMj2uhYzQpBd2SXB8r1fOS","error":null,"portNumber":57262}'
,2017-07-12 13:19:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vqhWeRnMpStMj2uhYzQpBd2SXB8r1fOS', error: 'null', listeningPort: '57262''
,Connecting to the localhost:57262
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
Connected to the localhost:57262
,2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-12 13:19:48 - DEBUG testThaliMob,ileNative: 'Server received all data: small amount of data'
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-07-12 13:19:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,ok 104 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
,2017-07-12 13:19:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:FD82B37D-D503-467F-9AA6-26A0F563A03B
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57262
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:A03C951D-B245-4CFE-99E6-E334C2AFE3C2
,# setup
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:188FFAC5-6F17-4776-8380-760277222EAD
2017-07-12 1,3:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
,[ThaliCore] Browser.startListening
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
2017-07-12 13:19:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","generation":0}'
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5FAD275C-C5BC-43C3-B770-A6845C0A2152, (syncValue: oHQXdHOsg3EKPtJab2ZDbmPZlNnRDL6r)'
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FAD275C-C5BC-,43C3-B770-A6845C0A2152:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"FD82B37D-D503-467F-9AA6-26A0F563A03B","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
2017-07-12 13:19:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C089239F-FC8D-476E-944D-1E38E0C79965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
2017-07-12 13:19:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C089239F-FC8D-476E-944D-1E38E0C79965","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", genera,tion: 0)
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oHQXdHOsg3EKPtJab2ZDbmPZlNnRDL6r","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'oHQXdHOsg3EKPtJab2ZDbmPZlNnRDL6r', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5FAD275C-C5BC-43C3-B770-A6845C0A2152","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8754D0C-B89C-4AEC-9174-3F312C3160A7 (syncValue: QitzLK5,bA07gFCnB18QCeJ6Hgp4jAX3O)'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A,7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] Advertiser: session connected Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
,[ThaliCore] Session.session(_:peer:didChange:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] Session.startOutputStream(with:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [1, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] Session.startOutputStream(with:) peer:90CBF354-22BA-47B8-ADAA-B3D81226,A1D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] Session,.startOutputStream(with:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connectio,ns count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (1338 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSoc,ketDisconnectHandler disconnecting:false
,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'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-12 13:20:04 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57274
,2017-07-12 13:20:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QitzLK5bA07gFCnB18QCeJ6Hgp4jAX3O","error":null,"portNumber":57274}'
,2017-07-12 13:20:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QitzLK5bA07gFCnB18QCeJ6Hgp4jAX3O', error: 'null', listeningPort: '57274''
,Connecting to the localhost:57274
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,Connecting to the localhost:57274
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,Connecting to the localhost:57274
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,Connected to the localhost:57274
,Connected to the localhost:57274
,Connected to the localhost:57274
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 6, 7, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [1, 7, 8]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 8]
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [1]
,ok 114 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] Advertiser: session connected Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] Session.startOutputStream(with:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] Session.startOutputStream(with:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [1, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] Session.startOutputStream(with:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A,
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 10, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [1]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client dis,connected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:20:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:20:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57274
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8754D0C-B89C-4AE,C-9174-3F312C3160A7", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:90CBF354-22BA-47B8-ADAA-B3D81226A1D4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F813D69B-C593-4754-A03D-1675EBF9957D
2017-07-12 1,3:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FBA50905-E748-43CA-B1C1-5D5439B5356C
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
2017-07-12 13:20:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","generation":0}'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8754D0C-B89C-4AEC-9174-3F312C3160A7, (syncValue: MEzfQHNWYHE5NWN4zuG03BwrusabGj3y)'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8754D0C-B89C-,4,AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
2017-07-12 13:20:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
,[ThaliCore] Session.disconnect() peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", genera,tion: 0)
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MEzfQHNWYHE5NWN4zuG03BwrusabGj3y","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'MEzfQHNWYHE5NWN4zuG03BwrusabGj3y', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C8754D0C-B89C-4AEC-9174-3F312C3160A7","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B (syncValue: TsBmLga,z6Pgber4OULaMlWKMI0vAUjzP)'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9,B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:25A9319C-4651-4DA1-97A8-134FE895A283
[ThaliCore] Advertiser: session connected Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:25A9319C-4651-4DA1-97A8-134FE895A283 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:25A9319C-4651-4DA1-97A8-134FE895A283
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:25A9319C-4651-4DA1-97A8-134FE895A283 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57287
2017,-07-12 13:20:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TsBmLgaz6Pgber4OULaMlWKMI0vAUjzP","error":null,"portNumber":57287}'
2017-07-12 13:20:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TsBmL,gaz6Pgber4OULaMlWKMI0vAUjzP', error: 'null', listeningPort: '57287''
,Connecting to the localhost:57287
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:25A9319C-4651-4DA1-97A8-134FE895A283
[ThaliCore] Session.startOutputStream(with:) peer:25A9319C-4651-4DA1-97A8-134FE895A283
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Server received psk id: psk-id
,Connected to the localhost:57287
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
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 13]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 119 got the same data back
,# teardown
,2017-07-12 13:20:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57287
[ThaliCore] Session.disconnect() peer:FAADB9DB,-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:25A9319C-4651-4DA1-97A8-134FE895A283 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:25A9319C-4651-4DA1-97A8-134FE895A283
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:25A9319C-4651-4DA1-97A8-134,FE895A283
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5E835EFD-E820-42F6-9814-E20DFCA52E02
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:747F7346-E94E-4725-9519-7DD504D607E9
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B","generation":0}'
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B, (syncValue: XJV8lrEV1VgqLjxXSTvhooBGwDZvvcOk)'
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FAADB9DB-EF2B-,4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
[Th,aliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifie,r":"B94AF845-82FA-4968-A8E5-D060BBAE3A27","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
2017-07-12 13:20:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:20:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,[ThaliCore] Session.disconnect() peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", genera,tion: 0)
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XJV8lrEV1VgqLjxXSTvhooBGwDZvvcOk","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'XJV8lrEV1VgqLjxXSTvhooBGwDZvvcOk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9281573B-540C-4F9A-8AE1-6069B66045B0 (syncValue: NlbPL5h,sgfYRpRV8mvhpheWna0Ko69vL)'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9281573B-540C-4F9A-8AE1-6069B66045B,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57295
2017-07-12 13:20:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NlbPL5hsgfYRpRV8mvhpheWna0Ko69vL",,"error":null,"portNumber":57295}'
2017-07-12 13:20:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NlbPL5hsgfYRpRV8mvhpheWna0Ko69vL', error: 'null', listeningPort: '57295''
,Connecting to the localhost:57295
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
Connected to the localh,ost:57295
2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-07-12 13:20:32 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9281573B-540C-4F9A,-8AE1-6069B66045B0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
ok 124 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
[ThaliCore] Advertiser: session connected Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
,[ThaliCore] Session.session(_:peer:didChange:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
[ThaliCore] Session.startOutputStream(with:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received (2026 bytes):'
,2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server received all data: UdTTOGxqBRZrNb2CNPEPMWGddZD9Ock8g1b2cyvhDLcSlIwoAIwgvi3nOVBWxDvQqqqn6KofsxAQEv6OhNQstnovioEPsnGYnBH8dPh1N3nz16bHW6O8AeBMRp25ZM44ts1S9yucsYWvVNmHwO6NyxiYmxhzTyiu0CgcQAtNr3ylyIJTEAMKiBZzyS8J1XsTq1brMY1ijoWBDsmpuAVoY3ttCssWORoasnitIqB4WyVYGZr6gWiUh4D3h5fiSmEEdy99EfsvYyGd7UYzROnDMxPPiHe6qeK3AFvsYX6UBTwdxPgbxz2Mp7By4GkjMmlEznwQ4Fe7yracuT7BDDNVi44StipnNKuSBUvDWrf3QwQf6X0Ykexl1E4l3N5eI0M7fxDFnaa3i2CElV4XJMhyOXXhLpcSyVQVukEzgl0VKiRi4pFI4b,z1lO2wRyP77RrkSHtE4MlJiShVHQMaoefWxjhtSi6SJJrlVog6Vp5edyNl0sQK1dG8zcTk9rxiovW4lOJIPcyNQkb4mT6LKVs2qpqjohmwD1uu2ezDvPYvthAJFjE7L1InCX6tTRJUOKI8waJUgARrhVrLI6cRhc196nvcK2xrEXv3BkD5OZVYr5LwbkoGt5tXS6anU27qI3a5eIhRsb4k61x7Ae8kBsMBvA94r06JMIkWn6sxvETXFwUzrhCM4M,XNPiuwD37JPaBDLMABLybLgK4V3Fei8TNgtPRS2HINwxrTMb4grG0XZm5QF0y16V69FokRfRMix005ffdcHS0wUTUSwoVE2b5sCCMhlGy70pybnaW8IyBCBFcGl6ZE11lRtwCH9efukulgctwq2pgGSsxJZ3V4j6kc64oznd7Vc3O1XqNvFinRPcXO6nPNDvEEAjR6tUNE2iPdSVUOQDHYZWbdN1sHleSkKHQGFZHWk0q5dmwh7ynhmKjmerbR17,wZVLDa8rjrIBaJwxCf6RWSnq79cQbdpavQ7pzlESi2E0CUNai0CAoIx5A6CqdfdZHgHMCVEqCwLojGfvdINGckEp1t8h096xRedm8EQ7rzChp7s38C6r8t6hw0py1wmdsfoTEbhf5W2Vm54HdXogDenbI0znWuOSHlwgLlMCMNHK2wtY9Ij4dTag4SkCwFzPomg2nwyTcqRNldomFXF9rxRmC8tePlK3q7mbRXuY8uAmrJRRlXQutbdiMKJLSYYv,Twue68lUKAA7vrSBmI4F57edbwlaJaJ3MoIHS2VEsmHx4zHU0K5rLnyCY6q8ODffutT0VIvJxPWHtXiE0SStRGeqzQGQzPerE54QYQg7y17Q4wZ3cYRBdLSNGKU3LtptOj9CSOviIdVfohiBCcALoXd6hBaqYecEV5BytLNIE1RQmakYX1Z1tjlV7wC39OvWuaAEJkErcV9WpEEACfJYfvRstyf5otAN7bCt2w2eeb849pGElxyocaOU0V2a8ZQb,Yg5OnExiR92OOLpip5PJbdvdQAPHEOcb0pXu1q4Gw48GG4QaDfzz3an2UxKrmsHFGO3bzloi0Z9JyYIbjGMWqlJkDA15mTDxwaI62JvZheSzdlL9o8j5mFcezEgApla4JqMmuoMKubxGrdoThRdKVkgLanrJYfKF66iymalvKGNbuBOF4zxDq6V19GFLrdqL0kF9SuMK7n0RDbi5zD0u6cvq1Na35lXlqqYxgI2R3FFPEBhEIkytH6zgzFhxqGvO,3u0d5Qp9tADbUJkCEAnu0bpCStItyY1tiaT9ewFmHI9nZVLb3qCjJmi4d9PZiXCcJAnjGKp3JrIUrE3bl2cSmuyzopWbLr4xJZBFGkN9xdve6N8nUcbwpQHmtmruumGynjNECoNb19bjCb8aveFXZvfCf0SC0JWrlTM8fM3TkX73u078BG2KQ5P2iJkNl1BbYCH5h2204LdQtB6wVRFw5g85zOAkoZR41JD5Pyk8ZR483maPWMNendLlbQz4QLmB,BTIfPw9OSQfaQyoaoYMcrU07hZu9BlTStgmS2zIAequX8V0K6QuRkKCjHe5Fy4NGl1sU58WpWhuACtMcHrSN3OsvM7tq4VieHuB4KRx3VE2vQDAHOGAZHBm380ma0F82WntYbxJCTkDbq5cM0MeqBpiX5PS4WsIw78RacH52jHpAlC11xl6ioq604FbwImhi8kAIvTwZUqHEzVxhO3eKPKpmSuLs0syULOMLUg7gqRn0XuIxniMe4g3BGwJHbn81,7KYOAA7p29TCiHihzJSjeFE062KZh1AD6qJEdZTyKoSfKYEW8QybkExvtIl4dKe16WfhgV6MBHZI9p51CqY8emaerHE8D2ujlbq6NrnlCZN3XXaV34VHp5r9Pwhx85Rz0q58HJnBcbwzDEY77DBW2ADiCtEyzjOgGH8ggGeFk9FC7n3b90901MAPkO20qgoA8nKl787xlhF8Nhh1odChryd4WKrXhYwwgHhHev7v8Z0H1aQQBZaTDuOQkynfeiMA,8o4LYDhLT1HdGvc4l8PFrWEyRaaSZ2zrsppNLpfxQiUA19OoVEtwvtWZq2fmD8Y7PGvXqzewzszHHLupNMEwK1v2XjDWzYMNxYKzMzPbHdw5wYB5RFHrXyEt8aaJTZD7fjkKZQVg8MWfdAs06a8ek1pctx1C1P1tiKRWSwvOmf31H30FRNDY1AkOcFLMu5mjMoIl2yrM6yDvgFG5Sv2wrVpsUSVYWVSJ7r3uzusS2nHhzMmbmozsh7jORDs9AngE,a3IUX5GCl0cIv7Qi3puRSIOaH2blfJKfFA69lnqYMSPgekRK0RX8DPqZHlqDvrsUYRbOMuJwUU7Bo3l02NYICUp9iZdJOzJd4zYpUpSaQnoqI5b8h4JIDutidUfqeOnRenFHygbRFZ20ouxYtPhey296NbMymci9tXIOxj56hCdz0tGn15r12s4XuQSyq6jlMakTWNRjwPIXUT8xbjBxos2rDkXwq333V98nwvQ5KIYBEeQF00T2g1FdX3kExIVl,DxeY2xwhKBPFd0WoM5f385eNVxFxIl4TG6hb70ie7XNnto7PLytn4OC8X3hDUHiS4G7aLPfLAaEJ9jeptcCCbAIGipn06Yx1DBss6g9Ery6QvTpcsYQ6xTcjzPWrlBzybtoU2ddJJRBcGm33BM6vjRzaZhuwpz22voZMFWlO5LKaNfxbs14tQ94NagPVsvORnNDYwgEyoZS30iWbWkZHMBiFoorKyY3NGsDr2znhF50IKURdgnskqu4V9PCAc2Ql,CBAoTcSGOnYiC04pVm3oNBIMst4F5sWGcJm1PKZBqa59nJ9oK2kogT4EfXYqmXyoAWSORgyDJ8kUcE0V8l2zNi9SKrTz3gWuJo7BKL2m8QM9fpidQcxY3hmQqghZ5Y08hrN9UdyjHJj5JbVLLgl18hqhwKY6cLrdzk9tLkOHAs4GdtU0gubXZrCZz4bxCMMIbJ9r5wTpi4b9fO3V6HYxUaAXeietL6429Jek5RMMn7VIzMOEfJkHiFcyhN2pgpug,TqE24lekVaHxhJomDQOgtf5vMelb3bmFYMJdYSJMBP4lgEC2ensPpJwZis2PN9GFZ2ONb0li2192JtawppnVnYVOprhBu1kadO95m6hIL7IQiczhqwwCz7vli0EhlqT8FCzDNu3OSubUtQnEPcw2Upy3AC4jDDQ2CHOa44vmeT3HaVd1DxmQPY5XaTasaN8aeqP6T94YiSHpF5ZvIOOX3uWEBaX9PlyD0031lVEM8IGWgpj7sakNa7YqleNQPBIt,IiLJdddg79HS2ewjxbuhkhGNCkSgRgE0st1bkufZByjQQczYY0JX0laCMiC7mXu7BnAEyctWvgT6fDuIYA99AZe8SvU1qwgrnN8OOt0FW7EozvFZhymAhEaaOYtms8Y1JnJ7mL7gHYJiryRnxglIWr4lUyg0G3DQDVJvSLYZB0oDA2J8T8DHT4n4INLBWABlIqDM5MpUWdBzrbDEpsT3IOMfHX93ztRQeTXxH7q1a1lsKuArRAasmNsCKq1Imlec,N2Ua9rfCfBQRe0EgdVwUiS41WZXHcPR6LJpcd60eZzMkIXarIUSIcXjVWnHvXP8CDgvAsAamNouO7K6M0WdUO36mMq5K9GWshTFiQhs6636NLXrvTHhwgG093BwFN0Dfrc5DwA9KQZ2R8WVpvr11BiUFgVT0KeGQVgOYXlYpXkaVXrqdftj4UFoVsbC8prA4PNHoMbdATVBqhIgiASQQRsLSRnP6J9uXgJjpWkJQXW9vXU0lyOXVWhSLGQafKUip,GRSpsLHn94lGbBWUSoJXgw4s3daPxiObErq6bqG7MeupwKSKdetSFR54xkVX9Mh0MsrNbRXJGx4PpjbuRXjVMIADhrW5uD2mc8uB5BzDuyt8WlJTo4JIGYx2ekeR2W6qaPaHZxBCK97IcwZWMCF820VGIvDyn5aITuOBhzSUZzRRbbHsEb7bqS5SGeIZTi80xb2ETYziaybdL4ga28LvCzZqlSnd2Z6tpMCQ5pY0C8XTQw9SiXhpAZJYJt6A5fF6,IMjSROuLr0q88q4vjj2xN5x4bNwLNIgf3xvm7r6S2N6wntGQMhkTVUQQKig4lrMtmJk6JTyK2VDEIFo6oFV1Z8lBZt4aUbyM1Lmw1CWarpBfnH5RPHarU710jDE4AQ2G3zgtUA9KKVVvavfmje8q4Ool4MSUVCY6kLM6lI18cFXijKR1fq96VHhKNQ52ID3ICTlYZCKUGmLF0Rriy6otgWY5YYHxEjGwiL8PINhcObTWkLnijY48Eg6P92h6xliK,JHimjgBdfy8y9X0L3ko2krxJdqFqgH6sAAoXtma8YE3tAAXFN0RaXvCGZLtdRcbgSdyISRWT5ZD1YwESyL2RLoz8UxgUneLVQsWephM1ANlim2FpLB1QXjdPeCzI3xi0TkSnuLXcHeCukU9dh8sfTg9RD4iX2Z9xB6P6dJ0WupzOHgnKzh72qva7roiGFeLVyRefAjDom0oBRSsxtAIadOCUXEUCALc5IjuqXCgOybrztkggX3fpQhLhqtmwUqNz,cbdyM2Rw7QeVAGkVuFsQF2hrWHT9KBKtdSiHJFzVjqh68z3DDWqM0n9K55GsXT3QbGsiloiAazlphdRCoA4bJgO6OHChHakgKFOVYprjYNrlynLzKuuHOOg55nP8Do8xmZb2za2jz9sUAoC7IZCQaRlYIeIjm6xWCiOREFvwtbH4JkcVd70OPNG47QERxT44Uw6H6spC7czT3gkILgGZUYt4vEzOuBEbghmNy3NGoWJZGWiUYGZAm6nwZjpWfqd3,QIL5Kpd6v4m5DV2kUD6DmFvyg9lQlXqgnTCF7Va24QjZBjacWbopDeEl7VyyaHz9Io26xJVvnrJgutJHeqQe5hGqmiA5enhWmHNputOmL469Tkc0c6DWDsGuGbI7iRSYOGMBQmOxSSMPV17l1rr2uqzMIUpcV2cmjT3FBJfDl3DkCskzbBfpK5ryfv4EIT9BXDQEfal3SV8PPEtCd55Buv8wX5aMSBmnspJK0SQYf4l6LTvoQ6UckHeqVQnGMyMS,4fu5SSO7OcCpuNQ3blzXELSx92bRnSuoJ5AgxnpLLTsbCCxRoa8Ukvju8fCbxPKEhDhpMoiyqKKOGxKQ8aqE4mglj7qVLJGbsKLdTLHMK5rBHGk8lTxZRIKBdFXYj2cLO3ogztHO2R0ECXdZt7DbMtL61qXIlThkKEwVzxRLat8CODiADv7npKFogh77IiH13YPDx7OnVEsAsl0Lnle3xB2WJJSOUA3aeSMhpWq99O4z1h3LjskqLuOlAHY4pO4r,ivW1UUypjxq2R6AIzwNUFwau0E3TLdPFpTL3GJ0N7S7OsK17mRauC58yJe9oEGVFkTEylwkTBQIiL47i3bDYjUQhyfLw1TiulJyasoiAmxnuu0JKmt0ZnBb0uKTC5ujkbhgoysiJmHqhDKYcR3SDCNTtz7ZLUAAv4IFmG3vIARpuKvoKO3OH7lopXJVQMM2bguogZJTJEgk0M3i454ChKGVF0iZ5We4a9eZnU7KkJDWFSdOrjMFzznTUF56GT4xN,vubEfPpySaVkYeb3m64eq0MNV806nVMq2QyvzTFzR1dKz9rrrrq8y0TxvLCqrloSoRc6ZWIiGb1qTh8LlnWmQQt0JQ0o0ydssJHtjiWfMSt4NpuVI526gtdIqi0NRviKRppVnZo6fHbeVptdq4Dntu0OIowNsqUTLUainXa2zozaGYrS6T8JTgTFmJEGi4PqpwjjGE3sWG2KlMuLRgPF2F8VC64SV52uWMd9Afejp7LbpCKcnDR2GCMK8IHlnrsc,rL4Ke4xhAqbWVMUazPz3S09vqkCs2Qayw9NZmVPOXAVEoBX0TTqNaJd5XIw7yrS6fpkb6gDNFsKVz1RVWdYxDpAkvqf52VXYFL4shcCALD8K0uhjqsSRzwhG1ZIs7YXxbrE5xxK6mZbPAqu9lzXgZCeSYeW4LYSr8kRKfNA3z7jbTfuDJ3vW2tjoknlJXLhykmzL9wu01Z5NrxgwATAvAxTNEkS1PGwIqDSjrl130CP4oPniJ4Hgq63pOgwtp2c5,RIHo43ucrvYZmzNRLHS5FSPJUyl6uopLBJ3wRDC5T73cHCEb09HSOw4lEB8BaIpMqthOT4Jm3ktHC69ofRMxvnkMZKEIhZiGfQK4h3R6qIYpY3hO59aHiu2LMe5vpvM3MGSIhXQSBY96fosc8UZlrJkoGZfChIUqnyqp9spmOzQZh1BLn5CKN2q01vO58YxM2PErle0RWJXTunE7eB5raEiS8XmRCJlnlWJlvyAUwYCORYx89xAOWv9HU88FTA4M,jPclxzFXkmIdSAXeOWAKlvTRCB1Xe4P9AQUvJ5m9h5UGA4edWx2x4s1eXeOGp9ozavuoYUBpr303YwWofMWYzqsDp1pw38wVlSbqYfKnsTBaNikRsd5xRRZWkH57u1QpHtizLmyFMsywrPXRlkxanA06SN4nDbyCZ8jMLVD9qGau6mFYwhHYRN44uLAnQtmAmQQW2gxQEAIMIifw8K11Y1xSySl34RAn9VRev80HDrOEGr2ZtyeO2ySaU4Te7cYk,76MB0GXtirApxFv1I9TUnNHrV4nZBBLhOil1EPnSe8mqPWQoUvi3p82xnujZ3xBPcRZMGsG8UQOLWfpPWrIwL0yxkVUKHyyiOu7G6wb83NIk6O6qMRBl3dlzeeqJIUrzQs6c5CavXrHYd5TBwxSODsAomUuiiautg3OBRgquDwTAMF9DuZcR1VMvQ5uEikpnpU57VoihnzWbz14ctFjwrhz6e9kKdfVASGHm4Sv4NUVukCa80sEDW8XdVBgbppDp,svFvszcve23CkmfV5UmD0VutAbuOV6zo9i19duNpFdHVwUiSMNQiWjG02lFMPAUpwzgUJXlPhNt9H5lpr3ijDNs2eHoMMtmpPPHibea4LQBGHGic647rIgctGDQVMeP17SYIv6nsyzCUF0s7NyOurpHEf1iSHovsXoMoRgFyFUj3k7cZRdcd30g0Fe0B9Wza75PaXdCdPpYpD7xXMIVUyWNqjiAbD081gVgT7v6siXAkRYtNnC8PzKV5iTj9gm49,0AbSBY2XD3XNDR4bJQf910Vx9aQ4Jonk3Qkq3d0fJnDJQr7Zl6ufe1vb64TvSmHqCchnwzQ6lxsrHgx84Z9XCoiJKWj5CIXLFMUdFAe1M2Mf583LYfmp68R6LwB0peSLIglT1SEKAhWoegLHtFgXIwdn4kbC0AoKyrc9Ht96wRPs7v5Zo3jkgG1W0p5xNDmKMORXu9opClZKUdGVtzlo1qmaBLPotY8AzEHol2A2qyT2ObQT02entik8hFdGyR7y,FhlmWRwdLr34zuQE3tZEXNLDJ6bcKNL9j7tkM2aa6SqkzuQhFUrYlfKfhZO57lMsaAGRq3goOxgJ3gtSWYKdS5sqwgGqqwi3G0txCNfcQoOSCUTM8dAgTQwnjwkPoG4IyP4wNceWieQ2fNC4uBE9oC9q9EcU2SF5stEG7zjtDE53Gj3xnc7QClz5UIuTKSiXx4zrNXxWu1udLxZQQKpbMSIwFmI614m9CCD8PAw4zI02ys46UNa7GZQNPo71tJ6j,1ux4NPSi9fuC4F9ouNn0ALtXX3Lt65CdmCoLebUXLLggUBD5sFyoMnVnSIbzo5GBIZ6gfApoJsbekaZx3k66UOQ3cLzdkRwR2Yj6FUbYaUMlpQHNzKxZ2ZUrObJsC9KVEaZjVIGdbzL0okxIoRRIR4NAXR2odbL5secNXNNPNy62YN1xS5SKmQzUZxuOrOjfWZZhqOmvFJe3Hvdh5LXqmV2qAtReEEQusNCZ8XIESDMSI4npvirIIx3AwBSuoyii,TP0cXLc1qM5k9Twds8iVZQGmwUeMF5z1PuQvEsEbGrIeOPDA8IxXE8Wl0vsxFaJwHlxbf6qL6wDJJoIFaOLlCTDYFBwLQwufuvFYRjUyz8aHBs56VJUj3Y6mtX6o9VdwCMCc0nKdGqwsFO2AxocudYdYJ4IfdeeLQV5FEq3jNjrYZW42DL87BBuJnqVEJdDXxZKjmsp9bQT7BnjUC0ktMSYjCx1HzfQpckQMuxLC6oDbPRQm4Q4tBNXMk7MUQgwt,xV2gzeMQLwusJxVP59uwVLuqV3j3m1jjOi9pMar7Mnb2wyOetGJZs5Tua600V1SqSyTGDMzeRphafq9XsXl3Jt0ecoIv3VJZH2tz6bQTxu5rz3XAmYfZe1kLXMxfpshziDM2HjoYvjlZJxlAPY13eZU3DlNt2LloUFPp33lv7JOFa3rx6ckV7FBaHJC9cUkSXAoZaYoDz9LGRMZWiELP2Zedi4xEXgCov4fzlyfAQWHthEGQuVYzRO0KA9wRTig2,hDvgdufzoB91nXARCd9ydnYhz8khkiGOSE99oHAJMgGI107hDj30Z35zxkdHoyjRRU1z5MYGQpIiXA1fcQfmgU28FdzWuVA4Rkm5Jcv5Iywa3Z3HcmJyzWERKFarXGT1Wm5KLc7CN8uNiNRo1AapL4mr1Cdq8MPY1mLBjIgEisKrRjPbXOHsNLu1vQjmfA0fk2mLJKlAqEIWu14iwiY7If8MktsApSQLPXKh7DkMk7irGNbBBkhBMO16Dcd3xeV0,iUjbPVye7O8aSFyzkyLgVYbbjlfzx1ak6SHDTNw5TZB1D7FZwYvP9P22dytd3M3nOMW3EAEnSDEZgPHis9JBwp8O14GQjcb4FSxT4EaX865txKOmkwwcKHW7RDy4diMWzXtgEZ0KW7UpaUQoV3FD0A08x7O03ARKs9TlzKl2yrj6Tvp2e4zykQTzTLBK0UVLEsT9EIETtw8wj5mThN1CQDxqj2jRIDJTqhBGrIEtQ3cJKtmwaunUH5tlAulj9UTz,zW84m3XsHD82yIrfYapCbxVgfGGpWliDj4hDfOcUByssbKlg2xfwjJtiW3RriRXfQum1DhdK29qzUTydk6yn4dyaOxcn9jPS87rIILOjmPL6zSVGge05MDNDRhcvCMv0YTOyYhvP2nvGVQXIb2STBtxworukNtlKJwD5ITQOL5ghV7xujBLqcBdqkU9kXf35O3bC6MCcEiEGP44yFGMqICaJmHcSvEirVaBFzrWTtBiuMPaxHbPF9tSvRheQe7gx,0WHLDaYrUZC1PZqIfJNPvgoUoRO0y5K5pdl0fgbAeLjVXL212vW4EHBka4FRzDGdBSrWGceeAZeXSHnNskXJrtFnXkJUdkMt7stxFOHpptSt3O2t5XOTvXdxKkas80cAE6XCPPawEjOKIAar27HJ1Ln0Nqx97dsyFoMb4WtbXj3AB0S5KsnZJGbehA60spq33ic9EjRGnYgltU1bHEcBYQ7GOapMpGDbet51rsdb6nWnZnMKVBlWpS3pXEgC5ncs,v9JWd4dwkh3CG2oKAt1XKwOtx7F9cdTKl4Pk1FsGGs6fgfZhOFvddLVYPgbcOxihOoeKftVontuKjhRc3mQxJ8Dy3rWb7pxYqTuHpzfvSG5xi36wseASg71RWp9DoTeujQdWuaahKkLJXjI3xZe7EJF9AspnTdv6s9LAW0dEPzCBFuOd3dbMaxoxH9Biw7qkV9RVAirCyNjOPyFKbMjGjQygruTtEereFxvGVla7uZ4v6zdxMtRx6Qg1DLcFPFTt,YjvnSziFM1RBb8ECTsANFnT8CmukqGzNgJL0aqBBNTgyDku5F2vekpi4TATe6RHDR6FBqUsF7jdJvGrh0G1NyfMyGqKJuLkvipBDhygieAL6a9xE8PPUUUO2CMkrt2Jk2ACK77qD6uq2t8IcIrfzVc6QkfbVxBAq8LEM6alJgv9IsWTCFMtst7os3VdKFTPJfEPRzftQ7lby7sqACfQfKrtYeziyaq2S5MlgJbRwgDbYzyHaFnGevDIWGJZUZfDN,S6q8Iv9iUbe5AVY3WQbeMVgwlRKIG0okQAXOlaXJqQmC97m005H5SA50KmU9IdbXev5iQsfB4Oe62Glnh0zhF1keuxRMBCFsgw2ppqzt38FbZhqVhN2fzZW1RSc7lazPkauYHrt3WSU6l2Z4DsYjUsuldRpJitPO2fEXaR2GLhk4sH8kZBkC383Y79kIvYCl6oeMeXCAYWtzGS0rdVf6WBCpSFch7K8LJ3GkVBjBfwJWZV7B1UI89bRCrw9q1opC,tZ8oOLOUKAWmcx4HVbR19Etj1g9GIl6rdI4yuUqybGF4wJsTWoAgqGTsDHn5ofO4cMTPRaPyIZN72vl3kgR6ur6i5UnuCmXVUU2YjTNv25ODaKP2vT12Mc0ZT2hup5ldHja0XpVXeZyjt2q6xrbiGj2sKEwmm3ABLdLgpFzzzbvQYd2bcAOrXcSnQD9KirUAFVCqyA4I8hbaFQcGMjhdfXtnMCrl7a75sioUdL5Cjl67CvZV5cx9X5cLdScrSDHx,93qXy7mYb18E7HLE0V42tqhyeOIgJ95FfYB0qYzEoNj114WwcjnZ2LQJRXSphnXHkhv5Ozo36pJh4abVoRubcEcBkbheGk4bDxXCtp4WEPSm1xPIX6bLbAVyWGPSgTBEi4yxWeA7oAvMtlAEThhYX2F06LsAZfctid7E9jIig4L7i4n6g7M9sVKrCEC3pKYVlRpXvHFbXB4TWLJi84qbOZ375FNSPJPDFiTwwYLr0p3wjo3yK9brSJ5EKBcDjnQE,FFllTGpAfEtKrktoi0W6vDuOM9vbuWQZBCB2Wzl5EiKkFxyWgwyba97p4ON7vEv9B26EiE2f1OxBLegHFwIIylc7yAWOxaWm8AjPVzYX5FfAgzTo9ds1bqQmT0dZ5AzXhgQlqGHWL9NJboXVhtyHSg79wn6FqxeX6TNudrhTlSpyozr27p1inmvqN4fpZ2t8ITQ4m3fpjPooht8ZMCQ4dW50gkNH7GGs7eyfhpHgXNbr8yjuyPyP4w0Lp3QT85af,vauIU5G5sXiw6BfpV5QsIk0m4v2Za9xsM8nvHF4VqckHajNtuIdtj1Z1PdSylM379oFR7WV6LfmoCm9ZOMi5ip8dKEXXEVAjqSBsrNyxcgghvJdB9STjDzZNQIVY9F5h5T19BF3GRiWMpXVfdDt3gTI57wyjWV1Fh1FBi9EdeSWhkpSdetN94RII1aTTODNY7Vbm2OZDa02hEmASvLqLur8uU5ugsqsyotldgPs9oK88gqjYzRnXOzHyqy0q8vgU,uhqJsrhEjXIKPPlyW1D6BnDKgL6OcjDGJ92Tvv3L1LlGzYuX92Q0LkSiwUeOaSSMfoF3OppZNBziSvKwZmU129LzZoThUjqhzsjZUr7IiOI9NjIubHK4VZ4u71kX4mbPsrM2ywa9RyqXBhnyLxrwXHYKyWaXY3CR5Iv8LMphL8tL5hLLwNB18tCJpTWuHUErVvPIlEITdolpo69WIxWwPE66VFYUzo3aCXx0FgGjAVKmP8mnThEfP2hRwHEW8xZl,95yMEyRHGFLTgMhemvcizxoM4m7PLNF3udhauVy0p1pNKRNDfTwWSCey8KfpsJIMGQCctDscTmYTcho7SNFnYEEVQPbGp7J4sK8rU58fngMvP2LxDoHPYjUohJy4w6we6UblkuNMr0eu4KWv3iiY1R749vNqoEB59XtN0lWyfPEOrcs918QJfGdw9V8YxGFjKayXASRlGgg9FA0eaChPjnbqBiJ2DMCZDtPz6BZrQmWikzmVW7VjCngNJutedNFn,fvdEAMUUBhz71vBF6lvChtNjH0NTJIDps7TlgZFSIiAmKe6TDIQNuHnxRF4Ji4vi6OMYgeA72LhELo4vjMkx5oMKkrHlvMTinHAsXKvI69zVgxVRxXmTZ2iX19rnIlGy6VcjOICqxQeSHt3LGNR76CuehArV4WefwW45FDmuqBWWVpqgFSStKuCJt1pcBSM7VOaZpi3mUB8JdRLZvAWnhvglrtipZd5K3ZUoR3oAVBWMYxphhlU8XUwKqIYZOmtk,Rzq5i4iy53YnIrCkEvu9pVT8P2NsgDED1gimuPTHeLbNskevDAmA8eF0ftAlMXHZH6lS8ARi7D4Zu5wkeudqBJKgAd9VBrXa2ZcGXFPrV8ASwvjHNFfzY369VdbzFwAHjs2fGRM24clouc3yM9VUsHR7QSUqHk9aZniYxBtufppwaEzk4LjEnQM7B4RGr9evMESJEKHpr8oewrnK0wx8XVNcGWJGIPH8ID22GBxQ9VMgnNv56w65eJxNXxAVVmj3,3chz2F3OnaoOLhqk2gouhnFnIYvCuIZI1KIilt4DLASE02WRekQiGnT0I1zqF5oxeJG9gOu6UAH2d4ayWNUGDtTS9yGWAOKnNjNBWNlDY3o7WXjflgzeUXpNiehbLtZfAn9uk5c5yX1Oty0vVKVdlhiHgaq93POsRNpfaMaP5xa1PCDsnoXLCGJynIcNhvfi7FsvmxAt37PC4NPqJZ7HO1Ml8rTZYmaomNoEdhjluPrD4w99bfZ4Sq9tQYv5vGWh,WXF2uxKCmNJm7X71eCeeLybxvf26Zg32DCk3JqvzKtLBBQ2fDnIZa4kTxXamRBzHfwZDJqZVPlR0sk9WrQHE3WnCcu26KFQkQohBg0BzmC5PSHf6z3mPgJ37c4KLrmxiF7bPR7uffrNkiz7hZcvcw0byRL6bhS4wPK5I5Y35bumUtZrZJILmFYZ28D4dI1vJqJIkx5EpKhFW9jHCovewrAEDUtItMdPftj0Pu0QIQZYGg7jBOna7wsSzNnbAoODs,DIULvvy2OxmEGUsvpBqwisURu8DvGhbYvKz6ZC3IgwphvMlbcejtaqq9h53sACBIc5rsuiAzQmqjb5TQdFhbwhWKVsT9z6wbNqdHp0zdoMytLmMxCnlNutIe40BekS4OPcNLLVYeYRYqoat8biNiXizv1Xuh0et5psFvoblvSCTZpLmEAsuIL2jzwpWJzl9tG9Sj4TOXF6Zk4XVwpSJ7ulhPmiFV7nQ2D1iLK2buToeVlJdljeFsa2pCoh9JGP9w,OjYqdcesQGnBVA4vXGvLRykVZUKbcF8KTeSzejv1y8Wn17bLSSqa18KlZdml6K2IyN5CYKxVpYxQKNdg2BIz32d3PdZkUtWbwYIpFLkDgJNcLiII9mu9Zk3qsLI2IOeK9Q6EouIxqCI8kMXhHen9HsukcCquc790PZz03t6Dw84Wxj5MUyyzZZw1DZIQpAmxPHhw3HMojzXKxIjePuDciE5YXInYgHrDu9wvfYY35hAnBzBmFPbFQwe8c9Wd4VNW,PKF7fmmbj6tMYuT0xD3lDZBN5ym5xDfm6AEggp4zkfqvHlxWWxvSQgxzOfBEDxt8hXiiC474MZX3ONzrJsgPmH916jQksqcO7VvkMN1dCO07zkL7jW2v3pLsp9u0d90SELKpOig8x6kpQLIgfYDnTwBCkmAOfVlQnFJz7FtleN3UnZTYoOorVAv3CF84FcANczmm27IBmsVSNSEMQFyjzyt4i7deAXEhLc8jdFPXo1feu4IgamgFODkRUiUdGQeI,aaWFbVoUQBdueMIPR18hsHFbOHe4p8PzuBFxkj2O9CdyQ6Xtnsi99PNzqHylC1q4zB3gTQvJc0FplRuTtyTzAa13TvLqFarv5VgT9fe2ZSs7W767WjIDiG13bveleeIBSYWKHhlUOzp6TsYmweWroU7lGUpV85emPoeWAj0tiLxZ6iZlKdL0Bb9TYBABwI0drK01Li3ogAF39toJyMenjpn75lflBksXKDEKNliQDfVSjxvkCCiZaCGP56YOrbWs,IvR5U88MUCoeD6puqU4KlZtU47nSA8Lkf1b10vfPWJhiW9KnnDeLvXMlqAs7ZDoGKeLanw6Uy68vqRLqoSDznDacZZX6HRrlBoDWxbANQB4pp8IuHT8ImoCZxTPd312p1uubdJTzSP0pGA9kNYO02ddHQBiZSLNIrkOi8y0eLhmZeHFukvuWuiLMBEyuH7GQK7aNCU1oKeO81JNYJ3tz8WpUPvR2voXG268Lq7yHNaN4ENoHnpZJoq94lE9Mk7uJ,fp6Kx6vHgLrrbDuEb1kBPKBwacfgiUcTjwzCKwxfBt6udZd381O9gndynJ7wRy7B0MT8SSood8ywNlBQcbJ7uEihHg99paTUtdepOqfl4lRYLIT2YSwhJU63d3femRIraXbwc5L4bZOIsDukkwaxUi9Et5TkI9dhNw7IZPf88zmqqmpRVvzfHFP5CP1DfgaYHWRWHv7In7TJOHQCNmkz3HVizJHcU6yArMRYfO10nYiPytZXt9pjGLShENkdYmFJ,ytkfk73XLO42rNNP98GZsyw5BLDHO4aXt0sZIimcWdddNVo3k9Ge5hizbgFx3qkR3iIN0zexxFZRDJitpAResHS7tvA1lD6CIrGXUaWNJUKoSHbee3BzGleRtYzN0TxwqpbjdiYr48xvfS8a9fWxgCh4wW3c39VYuVr7mXyX17hulwViIkEX6g0FJQd0uv7954qpJ9J6s6WFJG14l0xEXzeJ4e90wYnNemGvlF7D1sAIJ4zMjulnwBXxCBS2XIPV,4cMboD9CYXoXECEEmYthBG5B5kVimwuIOswzzJ7GgzuXp8m4afcWoEi7KAFPkhtOKK9xzbvuEm00zpugw1srxHzjiOhDMCnsloY8VzXku42B1PszbG1aMZS05HSixEh6zbCzb7DwWQVsehNc1DgG504GGggjPwSl4dY7KqXfDSjGQXfbyTR9HJpn9hy5i0563GNCkxWIY42Vo0ud1n84ecuqrmAQj6gYQJxcN2KUKfSQHkzRwfCAc4zWFxqi6URJ,aiXc1YxN3qDL4cBOR9w0CZ95OrffBAj9MbDYFHiEyx0ZMAVPXf9w5LIM2GdMWPBhaSIaFTRx2YHlDwKzzSN6uZMakj6pKhdAwxsDFOLeKhZWE0uiNZsanchDhagKeQP8xsRmpEbLtCgTqK1iyQKspLkGpAqwvPDXR2aE9llPOvziYkUEL2KPprJRee7NxG7csXE56VGwZaYaKBtTRpMMDIroGlT974rFUWiexyhPTvtLtI4H55T6nBQxR94R7LeX,xvQnnzfandznHhyvjMs8W8qdfgcprPLTyoTvUpjHAUHcdh1QKZIqIgGhmAzxnZckx1UnRpk8LGy9r6iRj6mRMwK9miZfjAt1mfdhwKOmVJKzokNiDpkvDYX9pEjiiVF44XoF0MLoh4SiS6PRgTj1gvV9x8aC3aHdRF1pm4EHXKqpIhYh6AAr75FMWic3pxqRDg2xto3V85QneOH1CRM27yugUi0E1pXdjPPWtj4UNJnN25eH0fiMzE2zxBFu4kqS,eH0couZh3yLOP6Y4nbhDRkJ87Js1lJ7G070HIjdLP1oHsC0HN5mhEVzEEB39VBajJN6YSV11AAIfSnNQ0B7Vf993elXZzp583XrA8E8R13j0xCoAU5QnKVjGTybmeYOSM92UmtkmTNGDB5Oy8kuU5AGaXl0ZcZlVDr5xCqXLvVWSJqCITZ5JY3r9SdhkGROI5tCJFmH4G6fDpFtjNBozJGNiqiXsFUH36rtZmZbWPkBWrwOfuoiFT5RIuGp499AG,UXfyJudyi8qa4BZ9AbmMEmgwLYOJcvjSJgybWoDYhlt80bNzrHl8SYXdjLCHjwexIoDQZNn15bfXP88g0MKb2ujhq1GEBE4SFsvicunvcgBglTHOQ73gKM2cysgG6YDhj6L3PPRGIT0D1w5I6lv0wEOX8elvHHbzziUqkek2WKpaBN8ugal8nK5BSMAZaFxxV3o7gERYaD9GJBMJRiKPWiHV8wa8zfST6txJfMkljZaZvLRLKK0148GYWtFgfjxm,srrJ2BA1PJrPpk4sx1Ezg6bhGD2IMkb1d7YVlvXalzN2T2dN0lAcMKaIg1jp1Amp04vvumaX5XQl5qQcZyELm3uVF4PJZzv53CgvUjx2Pk0OzUFcP9gNPoS2cLereprdBvknnzl3xnLbuaWDANQI07iLPetitqMz1ZMBCwNa3dmGJN8Mw4OA4bxPfP2j7lDn6eiSHzA3hnWTLJeC3iWRmOnMYz6zpKwhUTyv7RlcyGekadarcxeNzS2e3t8LVyaG,pTa3CevdBEBEpXtkWgV12P0KDKCDxiUpiwHJ5Snzs4eytp6toLl6YNu3OF5z5ZlvAYBnLkkvQVtjYyw2jbgFItqqu1A5Fm3CJpHHzlOe4nJU2CS4CkO2NAGxnH66YBSAsoSiIO1xPcSxAK2StLC9ezjOMb6O5D47CFms2MEDmtXAYDkkUiNudo5OHyHGiFCSRRUpF0TFVhll8tnnVeyVX5UBaCHDwd4NWbMC9vW02gVEmZB74JxOYnKwuy5Azs02,T4fJOUbYcRmU8xw3jixbJTVnMx3y7bCeSYCVTeFxGAF1axeZ36e2rSAH8LF4q0qDp6njW0ELsGyfWnbPmGjAvDhKiCmKYdCqHu0khy4cpCF9MjvRyXixFfGssrSDc8fg6785uJMcuQoS6D3iRvra2s3mQBX5N2iEdKJRxeAhlWDFO9VJJiRY56i34rvXYPTAeSiL2bFJaGJ5jvJKxnYTTgbCCp02xHHOJFaJUeHV585Ii44b1g5xAohJfbmj8pqP,9UHG0vUodRXF1VUug87NqpsMQVIilE8qS0jFkz6z401VO0ae9KePszm2xTYztLUiUyltP71UCUMnDKQt0DtI8AlV6q9QT1Kr5RadVKdV9c2r9EP1dol1c2NsIjML2poDGqRVupNMFm0CkCyy5KLTMkrWubOvRF9fjxnrfX2Lruf5J2AdiUveoYxP8A8yWEtrsX99PUSj9LO8BONqbz2oLiJUZ8MoIuIC96JbzvE8GWlR7rq8YMGDNxMyKjPPnoP8,rAgduPOppLdqYA0AlzSxfIqzQYFYVA1Xr0IVcMPreTUNmEHNn7X3szTh9Tw6ItEvMlRivmx88ygtwAUKrArd8jnMhds8NetYJa5rCcwbNfCnO3s9ViuMEznbig06OYY9gdFJBanzuconxsA5aXH6rZXL0hf6CZCF9LIdUZbDTs3vM2saApy8CKmQ75FaRYKE30VPSyLZEedtymNYXNNYBU9IfxxUA3ycGS85Y6BSrZI1YKUPvMW9kWeH89zmhBgI,IJY7cVCazGBYO9gGcMWACNERE05Q02ca4c1x7baQZci3AfcqEkcjJiJQO3Gk0SHBwAjWofacs1Hc0lTAOe1Pznibdfi2cO07AIwZGeI6sS5FvPAsEpsDU383keMHIadjMuLiZZOvTarkcAzX8uqpSlWBS80k9CZj127mrrSGW6NYHoeXsF1GWiXG3mj10gpxyXIO8dMMWLWl3NLZhW3KY9lfXwT9qlSlZOWm0cL2f77qRhupzNUAkpFyHbdJS2iK,D6p85QWZDyHk9Y8uN8jjBOprGxCe7xfwsyyX9jmgNkw6S36CwwEcIr3kMMRjt8Xvw4zXFBy8efkTktKRXdwLKwG0urhYTa3InPJcgCl2JNuYuT4ggicFkoyWFqr14uk0dvVIVQCkHvgHkYxPhdvkq8ImAuhFIuqmI1HH7PWiy6MfkBAHkyTwog0n0apSxdL50OaAb3SDpwJOjgdf4SGMFCtu2rbANaUvNE4Dg5VKAEz2Q4ksmIAgH35MSbokwZJK,8sW8SYrJL67NHwxCTba2TgH7rvJxbQx10BvGKpBICWkjAZy7fezOuEKWzh9k21RU9wBH7ki1szEYu1JKYMc7tP5FYUDa581eF8Ej4aJQu7ROFhd9qFBwp3jKq3ct9RxImhxPkCOCtuXay3w6vH277NnFsBRu70r4JdTEkjw0YcZewI72RQHMb4iH6CSFEw3W5vy5HIA7nbOr5HQfxHCs4ftHYfcJIkjiHo7Di0HXsxIpSrV16g4re7MBVXJF2JlF,J5SJIdks9d2RknBNMLwGGTxQ9yM0IUAG5y6FWLz5tgxeR4pnpMzVc5cf52xXWwTUYE1QP8KbyAb6I79mHJPTSDsssNVseEUNlcFrAJ8apM0uciU9z68mqwqWZkYOe9FFPAvO3jQLNCC3LOgmm6R8R8DoLDxQCZQUPKAIBb0BT6KziQZji6OjU8t6PQP9pdeA2xIHOEPFIOEfNjq5yGH3bL8HD1Vrpokc8D7jajVfB8fl8bL7soNhwYwbgUEt8P9d,voGKBe71w2XSWmJXrWTjLmFPYSU8lcQPOnjdcecg6lNmLYjKWyrjjk7uK6F09D3MJumZMsD3lTWMN13IJUUoWI6wTcyvkh3dcuHoAzUk64nIh6PY4qsxKXan8svA6neZ2SFCLaq5BkzkFQZfUsBRQYXiCFaKn1smGg6TiCxNjrmPV7xAcS0Buw98V9mxQ11Br4t3llYbj2btYb8RoR2IDCM9oj4Ai75mq4RZracgRun7sEzvhViiqhN0pCk9qu89,CnfLNTnqMvwrBq7wS2i7PlUT6lZxL8UWgmL6Ar07Y7qrBro88OfLe6TcyqY0J7WtsQQzsZXQlJfV11NLXETjNxHg87cvRLI1WWxdMIgfFhlDc4Cnj4tSmT0AhLXNGHXAGQq6OoRITnpj23oF22PmLL6qTSs2oe9hDc12oGczC40yL1fX8MXw2bApc456hZzRxV5NrfvASaZzn0ZzrdxwcqteiaKVpOSpVsSK3EuUnacvgzmYFsRCvt1I1WbZLXVi,89im5W21Jw04UiWGenDLutuBFXfqPg68l0n9C3g8D1S2PfLx04wsYvBgqgXkaQoOsNNiiJSGdS7PCts7wyRsn1E8QNr14MQHhQYLXIG8Nzr7dClHjV48hjPNK0LP92c0LT0Glji2NqPGOr8Ah9P83LtbfH7zNDGerrTYgMQZCIidAxtAZTMcz0ZmTsRem1xurzSrKQec7VZUsijNy9veoGk3DPQyVWkX2p7EkCOZoClkXcR6fNcE8Kd2oPuFGDYq,NVERQ1L7bzQVplB6qxEPmpmBrVOT7VyS9KOSV5xzYby2qkQ8uUg2j1S43Z3B3VLq01z8qzzGXnV6dKAA2ojn6jXtcpRacNcvSJrCpVqtCWTvjPqjo0jkFkBurE0mGFncAB5Wi4KNSrWLlizTdNQmk6Px1dNV6nzCDVWgN7OlAUqTCZNzjeA4Uqj4qWhTPRvcJx1lSfkW3jVPmYUC9w0mXtdMgtGuTSp91gbth7ulLDbGDrsGW8CzH8aYehP6tR6b,q0hlvj8fqETX4R9L4W1GPJPwVIg5qapkACbEcn5NSe0jQmb8PbLfgFVdyELyJhNxcObrvpk9gest73iHrGSUWVw30Rfsc83AqIlh9gDgQZHjX8dFOFjaw5Px6sPeSm1ZwWZwAd3nuIuUz0REbgYmhwXErZn3itGksBcckDxXj2JFSMW1ysjyjVb82xxpWI76UNECR10gYKDEstZSDoQCXNy1W1hiovxcoH135nKTgj51lRAbkzjJu2nytDTivnCV,yZZNcert7xLMfld2VqaXe6wCdPCCOskFJ9AyY2Z417Hp4sacBV4Cu0GYbY7hbYzpdW8GVyyLSvN0qOXTomntyD988ZG7eSZJS9KQQSHJoR0AQFbrUXbwLu1FYn3kpgDhuRd0gVJPhHkSEKaJIosdUrKjSJEh82ZVLEX1YiWL72IWgVD87A8WhVzEoT5TNJw2vSJNBKimKAJRKn9aZi7k7BGHiqkkv0GinHbF8iOKra96gfu0iFUDyrVehsQ50x9q,pUDfNjGTkwjiZV4rpbchlnA6jZ9s9yLlKZN1UV6R3zm6WnfXoPGmI88TqE1oVPjBdozmR33aKFKmMyIGxocfIR6w5apdvmwR2daDzpd1TN2FmmNLrKdKZBH8noVPmkIzGDP0BGlSDurf2Gz3891eoRE9H2igSju7155hrN23p86NWLvx1eFuO7KYWneGV31vqlO6gorUOgRgTMDm0Tu0cbiyuceQAoTI1jeWCgVyI1yGhLLplYUZIIRrJGLL9brw,AY9Ei2kEPfQ98oeYROi6A5ZfPsXioSjssi1Biv4dk0Yd1MIQVQu2uk5EEDSBIyZRN1LbPHF2Pg5DyeoYaL8NpVSXdd4bT9cSqgmgSzAqET0EHQSPHzz3xp3sfiiEMkfp17ZLGQupdIngwDGUnVOBcSCbMMnyGnig4UjNb4aYvPozF1fcOAiQz7uF5Z8VrveOBJsjq1ySKUwywWdYRIxpUPKanp5i1VVc6rT592vUtXtfeSSq1sPm3opHSTKdoovD,3p5MLH2cwuds2TMz2ka1BBVr1AgaXTWdNy1Mdbnl7zuKOraTP5bW0k8CTNuFcb4EVCTMasKEwl4eDAxH0OHGAStJslIfahpREpG3NADz066DrnHfQyy39gTSaMklGcxnGgHsTgmyMWaBj8AqzrXrTEr1bbp3gWc2U9dILwU0vfb0DFMbQKAYM6BB0CBYLDyLP6foNcCDvZiHX3oIuHMm1nSsmKpRzbXzNMXeSnswmC9uLAcYmprS5BC2mxsHkNWW,Iq7dA0UEl0pCgDFg2eD84S1dBtMaNCemLeRLqvGQbG2NqsXVa84GY7ZwT6gyOSjkSK2WxYRzbkjT14ZNC9PtAqTj0d4EmFF69Pz7vbd9ndpBFTGo8lrEgEiwqGBHjs3E5bvffBpqsuc0ac4Ug3RF1PuGnJnbfEuzg4AdhFRQfKhQK108GQ3mE2w8RrmWiUQuoYVuIDwI5V43jqFyrQuoI4vXlgZhJtjfvGmBT2l6aW7094mVDPr8SaGAyl3H1tMc,bLTULWHPhnBeTA5WmiUdBj8l8WTq0XtQuzRet380VNjopIsgiu0BfAk7xofKAK63hLpxyputtUHmGOYvDcsGn8AgpkDh1a53uWXpDSaPEqf50JYHl8qQr06wNfDDK8NBqnjwE9LRfv9cTiO2hLheWJtIQecSlh5DbMIRKY72ZJvTXa6JNT7BefHmwEQDRavHG9VLAvtvqjUKrOYInZyPf9kAWKNpgIqEAjxdxxckHtgsk9HtOkxCbMLcC8McJe2H,1lacvCzrwSRXkHKqSLBa1fxrwHzf1Le4lbxWNOiOaWC3Ppr96PEflytMAIf9Vh0LUMoiVTGZRywXkCoSibRVLJJUVstRO7LF4d8Xugzhj8nsQljQY22pN4M4rMS6LRh7wRacU9vyD9YZF7TPZX7iN4ZWy2H07llu6vExW26RKRXsiyX48k77VQgsOnaHLoWGgh9PQYHQ5zUOG2RZmYN2QXyDZPX9fg6EumtF2Ux25BSHCxry8fMOhTGCPZaW68at,2gzKkzzxqTMu6jP215gO8tLN3SESlX9imJLRmVloWIXgojBE3QDXZx3Aiz9h6K0bP5CWXdbuRiqB3Lh97gWu0MB7S7anm3ncYYGYNcac2FMXe4kQYsx6aIBZ5xwGK0OaBjpthGa6rXnxPOIXzaCRRXqyPxpOhzG80No7tr1MAPJUNbuy27EnL9RvvIOYXozZrc1FWGTdqiXT0yODOVrgl5mHvVKAlHoYxcq0vvREIPQOZzKNgrHoBzHrrYsOytKf,JqG2Cyv93uLYEyOWp1gS4oxIhnk15zmdvzjXQzYlkXMhDMXucRB7tjAa4i9LMXEJHfA7gERzeo8mlBadRnUct5GpjRC7MAu3P2SUelYyOSKGDUBnogq9O72ZN4ce8os9K7S24PoCtg6sXgym1kano9NglK6hABBgRkeqJcDwNImEVk6X6aKc0m5C6BlkNK3UohNhFQ7SjMSOkkVgTApV37ru1JVDM2Gx8XL7B1MKd25gYrOPU1AD7nEGnyhgXLZY,8Kl44nUI8N2xX8ZX7MgbiXNlcG9WzwnV6G6GlBHZqQXJDwvggyC12ykGJrZZXNcjc5VwUS5SQUPmTTajVySH7IilEAqBDByUJy8OCMjUWFnsSjpuzqOObu96WZCbpMvVyuhMCc1MsFtOyMTFdpGOuaO1AiqLCWYYBqokLSt8Ec04SpvD64TejSIgCmZGlG5WjpkMbR36Hg2PwrijcSJGpbGHIxLEBwLgf0wcgiXwbGSezV5lzUMukOJI7KqAtKHe,LNBvL343r2yN6SB4iFqRgOLusezhbtwG4ZttXOpdjcQDwdDgCzVzYBwDkeOvUOyNVa91CPnPlDxAtRKlS00JjPZNpVtTQG7hfihkcSRjd0tEdC8gl0ka7g5crKywK52TjQSnJcbLED4CQQDclE4JxC90nwtTP7CxTWTkkEmW1hTNEntWwdr0GjzIJWQwymooKiPucgWnW6qAQHcZlQEqHBEElY4N6BKyj3dlo58gQy5a2MP4H0hjPCsUHe0JLsCr,czJwK0Sxwu6VnRr7VjUaTGCPLDTA0FYCABNFjXeDtvqNvsnAsITV2gqrQ7C3DoQI2cIIf1AtBn6oAmvonq2wAfUpN2PfOOsaSZnblBflyEaURa4Xh8KMsrhR17MhXAZINoFJJbbhWRLSlN475aPMBYwfQTJsRd0ZyVBu4bzlwdPh5U4ccUF11juRTqEMqXpyu4GiKjzBjVwk4XG1HY7MwLM0CLzKkUXzQ2oAaXRJpVqNl8ABI2qMhfaMCA05MU97,ExyyruADRk7NwgvQlajqMISgjUxKtqMoFY8u8aRrxj1oA9SHuAszzWDeooK9E0itrj75Jwjg98l4GVTX5wg5ZjYtNxTrSiznbl9QvApBhhLnf7bqfjelXq46k7xksuYUlRp7kIuud4qYLh0hnjpddGxAWDBsZxaAOmr9fVG93Iqa8Rxd4pkAc3Al5d88CCrOiNFx0EpoopON7WcEzHK2rfse0aY5virPPSGOKVngCiV7RLwCCVn8NcCCaLrGQUH5,FVNtWhOmBaAC2D9ka7r2doxYEIXt4um8TkzfFeJwcwaCtBJUldM0I9RzvIdMPSyoYgp4BDdocP7pKK3dAieQ1Ogaiy0TzTytZkeKVf2ejyR6uAUvQGoXnTdL7qVD3GgSKUcxfCbmzdnWAOKeCgHcHomfxxBaa5nbbbMfDveqspekSBwJwunwNO2vgbFoCnod9qzOrKqQpHtLuuH7qFSO9zAmKF62O14zPddr4N67tlS3UNibyjjjEd56hEjgDFSF,HnRaUjilt5HlCsOIGEYzL3oAj9BHXLyi4tKb9XdNSndb7Olv96BQePlCZa3rUAgFoaweGe5MyyDS6pEzG6adEkKfPsvVPnY310YEZo0q8BNRCoVeAjlul4PZv8p6rBS1yLxVnaEtQBjOfvJVqQNud4YKqUJBtF7SZGqTtJEYL7VzwbB6QPwkBuclKD79AUeFrzKehCr8JbWUgkCZ9rmGjegVLaNCdrnaglgHLtZziC0YEeU0H9V11QkwL7bjXG8D,JyZZuZKQSileSMyCzl3izHaVWlTzALXU8JhLlQ3iL2x4dLOpyB2o85Y6jkoOGuCRGSmY8Ka7vAKtFmjSYG4IB6R3gMjEJH8uptVKAG50iK7MTcbhYaBUgG16cu9gTyXZtidsBLL16fBVXkC1LUeRBGu78YvQfa8la4HG4P92qqz911aycDEup469EfwlTedkswiN8cnK9ipIbMnnfa7ie8fLq3qqWHoLsB4EBCxO6kDae6vtaAZ2Ekr9a0gdqw7l,w6aS39oZu9jIKwxVXf0ImnQqsEgu7cXvMSICf6kPrbsNKAHJnHwJ7kjsZKN6TvrTsIEbkqr2gCUNZCLKIU7RHmVF5FLJ5nRmmOeJS3WqXW4flwu6nVS4UPT65gcWoEbgIVMqcyzYTmzzqJJdZL1dmG8GpCtv21eZmo1mwgr2GYWjmr9n3V7DItyiiQUdq5KCn38rtZFw20Yaw8WpnwCyjzMGx4AeNtDEjp46vsUHRAv0BFGFAFtUjyKUzKX1xjOR,3fVpxyp59Gtvst6XQ7pmcVCluTJZOI46yykvLL96tdmZj2e7MRNMb3wHgSFQwWipKIbWcKMPsmNKE7cdOPCLhfccZ9FOCi11Maurj62FQgX1LZhxXkhf6zBEysZpe5sDWs9GPTtiCe9XyMT0iqKWS19hh2XxT0Zly25CBr4FPJaY84tzJpHIyfuvRwEr4HhIGo2o8sTi3FH4BxKf3RiTpkc0nx7jBmNQU141Riw10Xc5X3I20pyZI22YCsu7UTQw,vNJGV99LhIh997Qn4xg5T5VATJ4Y7oAvcgTkbDpGpI3Sz7zgMe5ImgyiY60mZbB6fCGxpQBj1v8DLHEpzuEeU7wfp8fPP8oIj8LSQH6I4HRu0SwyhnRsqwanT0u5YiR4s2b8VQzfX2ngDnEtt1RUVJVHOqzvmBB5xR69zehUXVb4ev8H1uGHnmsLCFeERNtPbn1pTloXSEAdrBvNKT9RENcYCpLo2SLoEfZG69rqB8fbN3D8Alv1hVBoLoXjcHGX,nfbjY8cTGYjEF5QERrYbMIbD3gWPEgl876vXNVGlaTcXzpCpGTNUZCkcsaBp2T4g48L6n2dUDu7MdbCWrwZNzBHWbivgyVJ288wfJ1r58Qoe5c6uj4h3oyYs1VPxmgizSY68mjyChNX3mcjXBtVGDbwTyQa3qDdniKKjn8qnopzlcf7h82Ih7kgoVKgvjc5dugVfbIyS96o1s867bp1BN3rgYw8xxxsQUtrXhqeGFrP5OnYihHqdClLcjqDFp9vm,umjWQf4sTxOGUvadN3BucbNxe13f6pGcGZBjBmh0zd1o14ohf3wBc1RvbZijZSBXZouPyQESl8E9eZb99I20FdtyHPqqHrek63AQKtCMG1bG6DBK51gCqUTHRzdZ2bUAi8RLmL53ab41HFueOvk1mwGj2L8WbYSFvpzTHTNyx9immqoyMu0HIugdcXKM93zSnB2vUjlS0UaJHAI39cpQbvdeGtkbVDLtjxJsPDE7h55jXY7G9eJ7K6eELPkpaCgC,DA66beRNkZ4V451qxIwejeKS3PMrW1c27g2FUcvdN8KSW9eC0N9AV8Ffrp6KXUNTr3O3FdwRpiJ22EFtPFwGZ7lQQw5TxepL4DQaNayFx3OrLgi2g0JZkjXigrGbpLavwXIvefsqV2jRvCiOw050koWO4vkeYtsmNO5GlTksMY4A1Fzy6FHxL5mwb0Su5T33cTzMLyWSoM11Vrp1x83ft6U6VGhkk4OcvERfa9raMmoWuCblntkvJdbTVrzXMbqA,eOZoPt8HQKfeNgwIES2sv2mVNDZZVsgbzMG0mnblud1AtQ01Ym5E3LGZMS6LuQDeiXynbWfvKYELgS5yIXz2AMmWxkLK7FryVKetGlsSILggJcrLuW6QAXXMCsVW7ZVOkUszBbDoYcJ4KotWA26ZSkU7DIUBKUbUBVFoKkNfQWlCwSY3BKgCdk9whtsADblYEHB3m2wBKPPX1zfKg9nxQAK15qC8Y0tVNEswb6tAIQ0jtx9rXGsH0gKTgXd8DHlf,HOis5GrFI4bjqfGFCrNoMQVTUKUhK5EHA9TQFzgfk3N6n1cfMh8hMZIoW55g0BIh1ZzkL55Y0XpezkX2mPRCB1DSlerxBhz4yBUCMDuHO9XVcXAh8Koo3TwsVpLlhMxgsfohxBx8GAOKYamfhqbqUIDX3iy2KgZbY4WTw2Y3j4kwFrQlqni8rwx7lfXPhafrYdZlf1MjUChj2CnaGbatTi9bht0Fn8tmvw3cHCrM35D9l9vh8vdt01klr3sMwRXq,IhxggCYqrzmcAkg1ge4kHMJQiDIxoU9r7uOYpRQkHOz0rWxRdXQFC27SzwtWSsdwEOI3BsWXrKv3xIWVOUjmVKwpXCYV2irT5WWsUWjkqaLvnYmUkVry2ENLBPzevnV7xLIeCS7KqftZHGNgU4rY9uNAQJvMxXbYmaPOAeOjtFDeSJWR0YzK1MaX3PuYMlHluOdEz8IX2JOE3AoqUeTQomVihs0Bu5ARuiGJr4c4QSid3xsvm0pPEnWAaw1cS2KM,P7FQAdPGJ6k5bVg9aTMCr55XIANKeMdf1xHrAkpm5MIQ9WJyupEG5gIL6bV2zTwGDPKOkoKNMsotRyqJHjP4VMtfC2OqPyp5JmnYn5pq1BhH17jccFc2A2erKjg3hkQ9LyGLlEx5jHhu2fgnBUuEVf4863YLUxNOkynDeXFKyx7oYaD2oF8e2LlHtshSi4k79m13PRY7UvhzZTtgxp2UWLRgaTSbwlYAs6V0V2xHThoR1lZnApuzvMsktyvAiS1n,BxqCdQjWY9DNURbAXZHLqDeTcfAzJKi1gKpOE2ELKlyvsDTp7fqi6Zi4nhOyoh7wTcea1ol6hvHPBsYqnSIFTAY4idac15ZSpE6j3usjtkGGuFNwGwJLe9gYz5Rgcsn17NBbTOS9tnwwQwsQysPdSvKJ9VuzpLb11XhXgpuq2eFOuUhlHRmXI6EMbx9sKvOI2G3TJDAYRNUi9HVfUczKotnvW1M4IA10lOenECjuiIuZozQhoLwXsxJLDeR3oX8S,64tDQTMKcUvzCarVUBceiOCY2MlTvcY2ODtah6cUXSxqEZZF0jmsGgrIbRPjOVWLC0UWRVtFuPZb8kSGpT9HLEMI5TTg4CeXsasFU7FQsiKvswnD0jkwfOFe3xYMhndU5XKb6ycgF9QkOiDcPcKp311B1HUujmlVSIEAVOgWhhaUxIxsOFODaYWhMKfcoZf7puKVk084I6mDVOrbODNxSsDYJ9gxMbKA0tLOX2fVgfHfTJAjldf81UYHJws3OPqM,42eMgK3cJont9CtTihTXUgu5AzqDUA9EfAhzT6klT66i1pJGUMXM8AGKrzjoMOPfIU1o38E9rlCGFedL6Qxs7dCVYOqwPKPIlMbrNQ2mmvL4NoKipHsbxdK330qXYqi8RikvELnKSDziJK4DiILCrCUKAI64Hb16SZnv5XpbcyAX7pibERyY1STxRHDo3qNdeWaHQBMSxssAuAb5L08CDjwXapFTWwMgeXH7ouGiw12tVygWMw49ZGGQ3joQUNKt,yWrRC4trSEqntRGt3QNNhvJqmEM5M5IttTbCV5CfVFKIPprrxg3wdcl631QAUONSgizTaWnAJXMhAx3cIjMGdSCtcY5YCJP8c4Iuu56lKTghmkrcSOT3iGwSA5RPqUj5RoQWvAJHeJ1Ja6Ery8mkpGxYjpHRojFnTsodBXvasKDyFws986AfkyucF7XD9z2MB5cLlCMHOtEhLH2EKd5ThfH32yTJFrqR5aTtPUwbNAnp1x6DSbjkoEggfX3gwNek,6uRlSdV6P3jNqH5OCLILHTXd0djIiGyaskPxBORwHAnVVZMibJOmtZVyG7Mu0Fc9v7og5ZKEmwwUU4ISpJvRbc8NfZJwBtXZQjiJHLNSMpzkURohPXtm0FpDwOJPDSDXWSSqhOUeuPTPILzkXmcwSdgpqqGP0F63XjkOMeHFCHuMUNtJFApP1CVjC5l5y5wPkbVnYD2F35dsqroRq3T4ZhGjh77jsSqtMlNYE7glNLKcJ6iPQ6aslAu7CCmzF4G3,QTFyyvnmSfgvvDQqDpOK8kD0OZSqo6SauQcFmulGNeibw3BacT1k5BIJtNUKl5KU214OyLruPSuoPSQydpw5621UCHDqqVtO3xQV91fl0xqnZspEBHkKUvKa590TD9g8tvpykMZMCEHY1YXO1whYsY6sMv4xJGCp0VGjhjhoH105FsecoJ82ZXrKsx4Mjk5zNFzsDsYXXovgYq6NCL09y5rljm5U63zsFTmoc8ee05iVdSFgbjqQctXqFiA0Wu7r,gSfPL1h2dixvLJm6CoRZP4zOthX0zNfy20JidoEENggd9RAIurTMoAddU7NvoSVUVljWiuvt590W3odA5EhpbExyCx4oD4kpAiGVefgef0n6AM1iic7TN3lOI2zA9eoOq51tFR1Z7kQ4q5wbVUGLOxkkEMGB5Uw77fZRKlMorLBmMnLv8s539mNjLytBov0YEKPRYOa3nDfmSOznFBepniLRLBvTWnHyUrMn5fc63yjBF0bJTJQvLmv7e5fJxJ7e,LKT0r4sYVrC5lrXEZEgnto0lFFrwma2MdRNbS6XaDDIBbSfIjVXxj6ScTo9wNdx8c9uH3qJVfkd5lnhRTx8Sgi0FsHwbMJLQGSWsWsuKJGxJeCkYEgcOWuYBikklByEfQGGeZPHmUV6qMKKHVYqmzBhIVy2tQW7R3r8Cyv6bLmSIuzCqA3308gOVYM1Vx3IeRm9VLcmIuxA3B14sIMMZAVYisuyJTNpXRfZtZ1lEGM4FMDtdSWq837QKc4G8bOVX,LrCicqxQaEFPhIFKLYBgIhncmtDIkxPeQoRwEg3qhOxvsw6zbvORZTBmBJa2yQ58QOpX7Ixx1pLs6lgmNMCfYWkpR8399TjnsBOU5R2QE3YrGW7tzXbvIu6s4siB9ASVHz5O9ZXRrSuQW86vLwieVp0UpwvLYVSENEztsdfCIigXPIrMqfwmHqsQ1mj1FA7USwSZYmw4qjkuSZ99ZguSDOiERIV473quji1W18QJ3BNe2zfq1myf1s9tLAFRCHza,SWImEpFxAuSQkAq0RHWElEVNdOoFmayvTgrKZQs9HlHQKlq9Q1namFapr55j4yjNTJgQarGlvoLf5tkL1VcC7LlHlH2LULAPmvA4T761QsEP0WVfD9uWrBCqVIjBgI9HugDXjXb59l1gxWldAcgoChNgMqp5e62CMTPi3qn7xM5cbkD4CCMGRvxhZTyGJKTN1qISIZRRRiYFaEeia4VdmIe9Lhk3nLSfwLU9iISiK6Nz7G1CAtsJnLii4oJR5qpm,1CXAn7xGaFYJS0qfqPMwgllwuHjwNEsAubUXCOQIopLTC2k1sJH2l3LGL5edWdXUlRCCYmKMkjmuXRmbSBAgynEkU7BYSb5lXjBzfANQIKZaiUrRpuZcXUS456qvuBeKREC8kRtrp0JbdzfnNtdp6iCTlJ8BoVC80REAlDUBAOAymtkGptygk4npCjesWsOmvwrTpg1mJUq7g5AtyE7oQxJrCecJpzAqKjuDv7mt04lspsxGhtv6rDhldb3yxgcx,lqAGih0iDJw0pSBlJ0sQ2A6BslEV8wgFiM6kjLWgD22O89dchUlDIHS7XSEK9GcSaB5ma9Rk2sX2T6XyKKHh8pYCI0gHAGL8kqOK0qgjg9Ggu8423MoyGFjCEYABwwHScfx1ytlSacVzQ7xDZwrVerviWfBsFKwEDkhWQYNAWt8lGc8vSMEWbU9CZ1Gz6Zv6fj28WtcUe5GqD0JzxoqEz7ecllWv7bIHeeJam6jrJq0eUBFBRbwqGCAFe0Ahv6ZO,Qh1yigTIneOFa4lke0oi5pvZfSEDsKmn9sgBaJdlDgfWpKejjqNib5de99LGyvB0HGEgSbNmJMjyQrd7Q3fH1bNuCr7nmNKECSnzSjVHQOOGI7kY9eIcLWzIRJDt1L1OSdbG3k3QaVneN0hCYVfMc1j9QHejSy3AXo7RkIN8bJzG3kLzaCTrdaBsFJ6BFY3UxQHBfqZ8eItY0I2CAXEnLtgy6U0mUukuyZLTcZlgJRnOPfhiG7dR3q41FUofkwgc,n645X9YzeCzKSTYLaXW4Gywwhcq7KGMbyYSXLAxzmktqHKHTTgXRV99ZGwQY5fHfUlwg3F4aCk3l69KhuTb6q6TN95PVFEVyubTvSkLbHwCdCQnVtQzIcKJeqJjoqJkDGS8e41WIJo9T7VSfuIuKOmtUBNNAClf7LJlzUcdPXm3C1lLJKHTEPn8sQeg15oj4HrBfx3EYQmmYTD5j9QIIoBrrga0dW8ugq0uUyNpIteE2QSXuRvftYh3xLTScuVma,EESCa1pAMaX94dB8JoC5tghgUxh75yljLQnSp9WpIJP8SdLoTs9YL7R0qa9iWVdH03lzOre7arnMvsQWYaK9MrQFNkLWP4VLNlbWZsPBShdFZlfjWr0Oni2fUEqcM25FHaZIiqBZANgnnXTpuiXXAKTz1tZuvC6soeS8bA5aLcb0mt5xLc7xrX5wG1QAbrp0QSawjVbRcWOHZnjNfKdky4FGgotJp9u4goiiFzGgu8uTAI69FXxE7IYOKf2mbLGw,zE6EZCZQEzDN1Z6JCMAxTOwIsbgZIUfln170vcCqvWFHKK6ygESOtT9W3kOPmEaich6ExpKKtgC7dI3IM9jGhNBsgCBbTC7EYRRuNb6jpHRIy8pYmBJj0QPoIXn6zf3T0ZM3yIZyKev7JjZI4q8fzXHpvZqHbavz8ooLP7mgyd1roeW4wljPuIiesyNq6zgiKwqYKTWGCMLml3alwLpZj0c4zgqRotyom1ljL8pldsHYBj88VZEe5incWXpNYcU6,2gYBWAZjZ14Zii14quXysPeCAMy6R3qy8xD7vDlyCYPMT1bq76ysQ8HzDsE8ond0voZEDLS4u5ZTDVpjvc9RW5Mj6ck2X9Z8ssAH88H2kSW9EoSgg19RLweRYCHvEBCxThbxrgw3YRAlm0VjTSPX4fqEaMY3HzrrKqYmWeRbn1fpimSjwyi7oI63JLXgjz0QHjVlDAvwU1iHPW2OfyqAEbYxpQFPk8C3b6y0WNhYeTnB4MOYvtmCdbsHi6f3zJ1Y,jJzj8xLoR2Z3zhitRqsw07dtvUrE7o3dFOtngnpozOXhE6jiC1SC5SESRXy5ncX1fIjbPydXqUukpjvbf0jOAJgDN8kDohKa1UefDoR3XKh9rbPqmhCsk8vLXFPDX2kObKZwO6ft120B3RNtYcg6pHgEYSy9S4IglbFVcw4AVvSeAEvLIW1OcSfArB6rXQxkDSwLNNlXDZVhGQzH9G6gYHUEYvggJZCq1ck8ZYitVEVtFHQVcHbyUGEdXOw4iVMy,HHmVAh1hiNI3FEeImXat5sMLqFXJbSpfACsJX5BtezOZttEwOvMTNcVY2Gr087cgMFKKRTbv2ZLm8STKGVPzZJvPjuiQ9kz0ESutSSvwerQemekIqr6ggjZuJHsVJEx9OpjaSY6aIfR4JtQ8QqIs3wTT0Xh1HFavHubJ9MaIU1vzMnzRezkaLIJNTwFhJEXznaVeEnWnVrIJGmjdFAl1cvcuYj2exoVtyAabHH9yJEBIEWdAJuQ16QRrIdJw2L8U,cIsGh4Bs8A7WIBeZk9argjEH0MQwBq2cXA96cAZKA922RwB56QBBDVK1P73LyAZLP7Sef2VT8eAJgGicUJQL1MfIKnuvqItsafYaFZbXATpRn29csJHPwed3uD89ax0mWlphLSSU7yrVF82V3gJKK7KnuoIcSavNPpNZecoeI8YlN8VIDksb3GLlNdPcUJO0K3uY2hRzDhgPuLPOwoE1GqDAXv3M3foaxi3mhlEVxTt0myCCA5HbvQ4U1JjiSrl0,RodY6FiLYYFywPVTpkWvL4cNV2qozr2ZTzslkL5YHppT3QxJLyvjiMZ408QVpO8chnqvkaqYRRvqyyaaR5kugEIu6x5TJRVDqKGmY5pNRb0HAIDzsyM6diXNLHLHNc1OGuXmWjw074V6N7VmGHJuLPwvPeFbdQp9Qijqd2x64czLSEKPkNWMQXK2UDdtnCHzWgH55Qq1MrHMePjG3xWSINI9R9zDPlJjdyoG0sn9RyD2Bl6QnTmu6QotaQWiEwfR,0IcTvFABGp3dLUFZw6Uf4fxdFvSjD9u4jYyM5RBoJtUaIgbmYvfGLqkZD9TN8g0k3LQos69gKR1p9Gbpa7XD3JPNkrKY0VLJCcTotpy92xc1VfoxHm8n2k0wfKzyS5g3gadJIdPjZzhSyzDkZrYK2eskMSh412QZkTmLGodclL7kep1SwgJcMHDRz3y7dEtfz0W80WeOhjUmcNUb1urTx3Cb9aPAFcW0lr732E2XNHuqBwIpqy1zDzC1QZ7p4oUB,nUJpgDL0sKlUXwDJSImteeMsV40K2RwVrfgnUsinLkCpvAEJuDwHiFT4VIsLEoYxB3vKC8llklIrmVgTvvuuhHZis5qxa9meRJwsNrLiOwWxuhAGY5KSlgwzdigtvH2S8U4WMWfNUvG4Iyk81lGtcxGU3kMKgo16Yk4MzsDamFe7ax9c9DHkNqih4E2PUB5gnUJSAO0tiiBTg8GeZzkFQuKvtDEshmjwTafk0VAV50btjrM93p7dOPWuqfL8yANO,ypClkYSWkzOg64ydn78u1378Qz55ryDtjJehtOxKxBOhjnyBOE8Xyn1D39HhovP1yKJ4xLzYlUbx3LAm5s2yfQLra9fL3nXRHrs7AMUvLYD5PvfR0qoCcwaILiCjXZLKMCA7R6QHCwvdvD45Tf4vp0MEK9ew1YIWBsT17gyfpGdM3fqfGmx9cw9pwczoeOZJm8sbzI5TJUIftuBGI5ttXhAvKEJg9QTgT5ER7VVmdPZo9d7REWkYt3G9YDKhbQLe,aDtKBUDIxrptcRSHpt0BhOlYi8QYEOZZVKbpe48vg2FZ95wgs5KOT7JaB28JnUK3kwIg7LSxIWLlhY3Yyo5NNRocwE12zthFrGCjX0Re7SYbf66wN7Lqv9XiZDkQsFTcE310fl8TqmWsHvKC34DlB3FQZvA1UefwgmRP5jpWY3s5r43BGKB5gGzvrZzvGEDIBZLIQnSkNf61YaMR7hzKlotEi5KMwOa8vlTDD86ULmxcxX5RrQ8UjdFnnUQO708K,mLmzkEVdMbSTcJB7EwVgHwyE2VZnvWJpIFitOOPHbgMPteIZ2fHjRZFQv2wjqnmEfVjsmvw4qKc3nWQA5A4LpVYn4bh3qysCs6gf2lsbuZR4SiYst8h8MoYcqaUgceNRgqSvMnWZjaVDZp72XqWK3PQoSeVkA3kOxac69SP6blr93UkQUcSVueVfMuN4r7ZWymYtWOrsrEX9ODi1bQ2v1uzZwzu5NKm5IgO7gKmp43T9RhXn2aDIizndB4H41wJY,0HIFwF1jBZWCZH920aklhCUxOuxoLrkSrUkQsfkLDYe08uAvsWVwh8ZMbmrjQ1Ydtoc8gkJW0QMdZozMFBaVHCf1nIotC4zY4kIYGOStKWeZlFy45oZerFPrL791tQ4D3jYokEnIipzAOzoX34FIsuG3XUgsO2M74y9CxRFpornpE4AjgtFp2HvZoWTMkmjdiMlCMNjtua6z5TDawW8NYrpS39XsXsWokTAU7OV7aHZytITBc9uuo9JVqvN7DAWd,tbEPoJkWXxEVklXtnuaQx7vJgJkaTdMerntuhQ0dK8TGh2LBUDJ6lbifBa392zRT7EDmPEh2qDDJGbAQM08fn3aiZ4Ru6xVI33zLMcoph6uoThx3WRTPOQKdxiIWmdMBsqiTZULpNInkSAwgVaWoLlDCsqA0aEIa49kJAMu48H7qgGRx3XUyYOAKOw3M0hHQ3IFun3C83mR6OsMLvVmasrqL28ZQcUnTjH3Qi7jkW2eBVCNiV0S7f3h9GZ8gjU8A,51KaKfGVGukx1wYTzZnP67GkubySl0eXp958FDNiGCMt6GHPhN4AOL1oGYYu8qfui0reYArKoF6ch0bH0g1vCrd0qAjfHZBcXSszsZnFTW0kcyRhCynnGCE2J7d5I4hDo3kVt3OC1t4vL4ZD4IqrxcZyiKRyLHm4NnJlxV3SQh30WBOXXW0bUEE9Txpo6XCUJY3sjd7IQfcPjtYVNGXFv5PoQVHtVagYeC0tiarfB1Z3L6mqwKRgTPKRS6vuyvzQ,TXbepNPWfQTO9E8D0NmNgl557Ck6uU4izIc5nFN62m0mOjhrB6aaAe3R0FmFza7fgFVUjXZBwAa2oBVYhmotfheVvL017i2ObfXkzdGZYlA0GKehodywGKwiohJMKmxXvpKGsHzX9rYYlNCnNntp84FvMrevFiYBqf09YkII9gK7MrblQRFES860LDtMzOFQs3IUsnFu882rz3WtpOEw489X6ySdKoeOvYXD8qL7kDgpBoxXWsLwm8H3s8swQbUt,8Agn5K6HSfYvzDB4tt8pNK3Rm5eT47P6159JEeCmnCiJX5AaHuEtlHbxVBFuzBzOBDnmCRKQJ7CthXzVNnKHG02ovGhijKzF66PbOBopRSSsdQM2WXZ2GViN7phu6WXt9L125E22rPc0GdgXwPMBOXE6yfLsyjDo5O4nqA26PjTM4fiNBj5yIYeFgmLdRSyX8UqhxuHlZAQC0GlzvMMQU9fu5hRfKhaAAzaZFSv80JNta8ZGK07Wc8xruPwbYgs0,wkD4U8ggusrvJs4aXeCZFJ2yYwRhmQBqO7Z3FuB6fBxovAoJ3jOVuv6yY0j4jaQTMHDz9JNNqQN00VO2cbLqmKm6BHoQzYmaVjaeGN8z8NcWQUOb6AVFGJct8ZtgpBJFQE5XEHrrUlrlRxaXAhpX0JM7Efg0GUIfzIli4H4eliHx8dQG00jA8dlKxoEnQ0rDrlCbaoFT54R7X2BeY6AZPvthmRVfTAn1FYvd6h2rUVXiAgRKdoX2W7B42wA5rJWR,Fb8ZrxT3KJnI1cEh5cTNHybbjJA37x8Zcwxrgdhpy8WEzayUk7TrjxYWeC9b3bcEBDbyfcv2Tbz3fx9Q5YAjjVw1lPZKEAmBk8AR2EV8TkVtdzZ08yGBmrJsaqfJWjekL7hfyJBgtPsVucHYbAqPkRLBtLval26GF8SnJpfZHtjXL2oLFaIk4wEPtUtIWzjDtujL1vCdwRKnwMe6QBw2TBAIYLRR4JsBkff2JccDufIoHczheqEh06hTosaXHqWZ,3FkVpix2MNL9pxLdEgnBHEbtYkuPbS9FsM8TBu4VKq4oM5zMrRymwJnwLGekg7tKpTutm14u2o9JHxoXHW2U7rSFQWj6ezDtnU48fBpgdeseCA0ZXQUJS2CKK6gVU3cdNmWm4Q3YaUOBgB8PC3lSrNS2ypfJxUPyNzcUc7xrUEyH42vkUxzAZ11aNvwCS9a52bWt1PMMcTMvTDnP3SNUypTxBVt3lGAfrJyUIwJUp6H11iS2x8z2CAgiCMjE0Uci,HUbxn2ADUh4hQ1LJaoDdbBwgBmrX4bKCedMH3VM3KWRV6Z0zuGwNqmipWOHcpkEOh0ijKm4UsOesbNvVxTmWWVNuEoKcs9BSl7imbZ5vo54ZSOy4db5FgdTpxMHrUBcRJHVrpAnFW2XeaUJvvOjHGMuf1TT3rGCh4zPFvub1nojO7jVzX6IETWVNJO2c2ClCtac1AcpqfM1nX4kKFJK9uVosIllAOW9qeD7HulqUs87boqjfYocd2eFO2wTE02Jx,lUAyDjUBrnC8bkwcQlWnqUCQPHAlKQd79FONwufLa5DoAG3a1g2q4CY6NagzFZwRJgXWCipgSaFCrqmrTd5wHR1YPrPK72Xns7gQlpxMgm6qjWKayZQzDoI9Ssd7gGMtN5Fz4QCWU9DX5vUCjyXWNqYkob7ViaBbCVUfpXGT7cdWQwHMqqY8RUDMCxuhzNO11YNM5WhUZiSWoJbibAeYC8L1mTh4GXpZW7V84iN3R63wNphdogupVDkVXeEf1tG9,hbZTzi3tAsRUjGDmDG8Y6z3yQx7XuSYjxMjrExcVPFJ8q7Rv2FRK65ckxcS5GjbO5sESDy69MhZ3ZbSgNazlSmw5erjAQF1gaBJyppBejnp36WghCmFOzubcPZnOUMaJilxULJajfxeXlsUpyh62q5TYoDqtb5fD538J2jthUw13bfzSjDRVpAUiqenxovEr3kROY17HrctDrwqvWHWx21On3XRV1vla1GZ9NVjMd8F3fLIHuq7s9IA1v3Ysv1EL,lfZwMZabl35E8ykyNJhL0lNG9E6ryZHCn7iF0qzGLKda4vyhgGVC24z3di5GbJ8q1UMXfor4nOWEEbj8yW3qb0DKiCw2JDuDINZSjk8GdCTLJM1HxvStk38w6X8fOMcE1sABByJONpCrK7kjXXs5S1Pw45CPBgfUlRN9uo6kzS7snhIDxgAtQasbOcArHcutG0O5miLILmBoHa6xdinPMQdWjW3hq2mz00AKvdIyfsuBqa0qfYM6kZjPPydUglxL,V9Ow6Zc9iGGjAM9erXDrAO0v0505lWN2xZRVvlFjCyzbfyPA1n1AjVxVZoE2iBoPoTwtn2Qx6plxq2yMoGLekWldUYSL0tXo0W4YZqeqnI9woWrUn7E7dUKSAAw4a9u8qinpCNZIeqFVdM5U5hzZBmTdZhudmPbVVaNoFXbpMc8kem0HOuAlxJCTCCnKMLAyOqRMXTdv5yjAV9d2VvHbFLigAN81qXODEr9hQD3THWXC9oPoTVnaqHco1k84aLhU,AUUAIxEG2VW6mmjNsjt2B0ZNVp3yQ2Wu24tIlcQLDWDg7GiIeK2MAXuctOpou3QK5epnJtRYSZhbkKNlVkxQ7LfKWCPO2RAg4SP1E0HpmaXlmWPiX960AwyRanGLaDEXPGXCjbqYtqCYubcxb9Ya7klsQNVO9QGA96TvboBzfCj53k4vxpVyW2YTJUFPcRYdo4s79VEXS6NKvsx15xTVGOYvaHrIi5n9T69Cey4gzbWM9WvUMTMILDdAEhnmB4kM,yMHOcLPFawYmEF53RKQ0UdOpJLhrnCSQJgAczJeofzKc0PUObk51daS72VnjzYxkyQr1wz78VLUaJxiyJdDysKE5NF1iBspuDfIg9NFpc4GQ3KOTBP1PRDdtU6aZhJXahrD3gyKFHh3qi9uioyfSGbdYUoDQc8a2e0BU6gHOsSDWmcP2Zi7aE5DIlNQ2vCvX0mpfCN0A371nKPQNBMNwWtRVWiKsz7Qi2iAv8lrYs8BkN2ozB4ODwYN5athB2Ge5,4NtNGQLL7pP52L2hTXPm9n8pplRhUQ9DWd9K3438VpTElT8DZSjE92dHCDSIsLHBW47YLAkj7OtW7pV00U858mcs5nfvHWJGntzE62zK4qkCWJG4You1pPpd0r13VOQGOwZQNNJL2F6C91zz7Rvx0QRJFLEZ2kYijEEukyQJPZDGLsjh60hFEvxqSsa9LM4L94Y1gq5jrp2iEGetn8g3j8BmgIwigrwCynPOCLC9BIqk1KORBOLdZdHYu82lx8vw,sywvxfBmpPYYELD1Ca9gjXTY81CJPYsxup3FmzWVHPkaAnVJ3h5TwUxaWeUxFrhG1NRF7FcNvGtOKAZjdm3gf7jd6ICNWMUhxYqFVaYH024mfaeSqkAs8Oyt4XFbWIUc3j8cw6sF2ByyDmhAQN76WOP6tipcm86In1c4T6iWNiBogpx9MSFYtQIdVsES0mmV2kP5sWebuq8GEsen4Ay7kDpqkdcwSWpfMlnmbzekBmLA1InJcj6CCJhpEIMKBmCz,DvLkERzc6rRLCDDyGDVuRrvgCnf1x695b9NrniIlKpSjACCHpEZBsjI6tGIho7FT7T47Bw7K8enVAinwBiJKgWAE0Uj3EtMr0u4oFY9eFVWVnbqlfigcWUQ7dYZX8Jt18h0mhhge4GdYkBPo2KmHYRmA8srqrOgCN7hLU9etFk1lr2drZJICxYahoZ7rD6NklG1qPZRfj92uD20W20XYIIZvrb1m5XUDMkFOXABYySAIcdCdmNW0sO1IM4osSk9A,3DODyl5CBmydaLYXBN2RvT4hKwfmz8rmXlajw2CiG2urw6gWrt8tgeg2U3pAH8pV8sXzbt90TvGvykyszVHUbKX938S3Lub34c5xmT2hrBYMFvGLDRsimha7FVB0hrIOrJ3BFQWXwihdvbwVg7arU3W6R2mNEEDE6GDcxe9Zfaq1vf6l1XTo8TMgMCGafHcOjuk5cP8JvBdePDeoV0MOXrSPvr0kaw9gErWzswP6c68j6iUXtoYGUsyLq4HQuHn2,Jo9opWW6tFINUXEw3meFcZoDVShnP7syWmIZqBAQHO232J53WGdrlh1pxPCIgm11YX6k5SpfLPwRe7GJrNU3rJ1fT6yjNldG7KXBjXpekxT8w3Fe33UL17j1ktNUEdAoPQo4lqkFdjKKrGE5cBCzw2W8EHr96dhr5HCVcgMxyEtXGX8Iir6LzuxZgkf1FC4FSujGFAXR1Ye7XNY1C36LUkfGKqf8MrQs1NQBXqOJxIotcCQgRjt3N3sK1rxFciJZ,AMvfucv6ePxaAMogEYM8LDW7d5h7iPuRxZXHF9Kzlbs7nx7XQJILbzCEqaWPmRMe2iUY6ie0X7o4qCXQKfsZ2VITqqEOdmYVmli0y2i12QDy0RlhNDsMw2HPAsyCaLk8tOhnuURd7JQid2I70aOa9Sw3Z1liEqGa6jpdmKJkFogvNzYv1fSZlv1p9JYodAJLr0an5kO6ahYjrW3CADwkDAwLiEj79LTuzmliRAh9BNNX9EUnigTt3oAL9QO7d9Un,3dU20nnqYQE6S8zV6ux8LULFQP3qK1pUCuvH19h4nRM2A9KOG91FPuRPlWjfV3qSDOoAxlz3lRb8MGkhl09F6VdPJOrLLfjT6uRMnQnQoKFsgOMuPvQ7JWLJF4fyS8ITF3NzcyCJX60YuDWTzph5LGoKHcdZV228eXihI1D5iuZrq7538YlM2CydDZ4RPZ20u9oQPw89NAdThANx6NO7QnHplUIHQrIhHpbkqt6JpfWH7iuDmKxqfdTJ5xUEoOEt,nBNu0bNlArs6lSnROYon9FKaTk3EWlrTzivyQaCOFIgYRBUvxInCpAgz37sirW12Gv4F6oaFWzVnzb6lKXPQ9yHW090snTo6JluTq4zVIb91huiVLUtFf2ilhIrMV6AjQbu50eVcBQ9AMPJNSLdrRBYDj54l3pAODnH5vykNbkYBYoUFkBRkCK0vXqP1nOU5l0c1WCKjJHNRgjlcJJUP3yMMs3pwjOmANABacuA8OVO20N4zz4zValDTUfGzzTgE,Y8fqetIbqQN8RVHrxNy7PwGKNVFYpOzLMRhsKAFFzCBLH7zKLHxPCcvfqjzgWEBZUqLmLMSPqOLSqwLf9vLfhM6loiiRSVrikxOOqT4NO7HNW7EwhDqiChAOpVUZJGSXMNbxNcfkp0ALQdEXfJaEaYruvzCoy8XgATgNWaHMQTVdKlOkMiDqGunh3UDmNvDFDz6K4KDTE5c1s71gK1PHK4Eh24jyURplRNZFdH4r6IUEzlj8SvNUtFFBYoXeyfvW,PwPOZFUNIBYUpKuCHkZ0Vnhi8XAKVRjhIpzqqacyhVfNZi29w6NEdsi1h2zqzYc1ry6apUfhG2r6glQzk05ZEF054hGjH5qJppmCZtP6VK6ZB934J5V5To3lpzhM95WGwGodkGCtbfHbhl209OFNld2BwF0HUk6k8yvcTcGkNF1xs3iKsk1wB6he6kvAFdCRB6YilVfUVMaAUtBYSZJIfodZMVcHYCIG4XojX53dfOWjvO0nT0ckgZuuuAgulqqC,0c8aLFDPZKMprf2tf8RwwRaX8tRSbvaaWnaDedWiZuiPVIfaPbyusYMpnqM5g7I0dku2czXkdMsWwraJNNg44JipHrKIKWyPhlwmHvJVDQyEFodQoSRfMJAriGkyvn0ZOgvDYx5oqQt6Ahe3BuVMMB3qJP4WVqApBwitb0OmFXXbcNbDRYkNySvjBjAoSz9qR2oOZQ18MqeTLgg1bvKoGY6tjvI9WvLelJTxtJEgJE4CZbGeNtmtgF9x5feaaAmM,30Kwz4KonGfMytDmeXACJ0qps94Hxcy0GbHbWFJ5QBdycRO18kZf2fRT8pSrn9B9kuvihnOK4aOkjB6QzfX3XWa4CTFmyOXx9Lh3oI3exURb9lWY0wSmUZiAwtofzWuZn3nyWpGRKj4ZoOK0mZpCWX9HkfbJImBol6dqy3lFADXZjpMHB5mVDcFbh5aVwu0lTjILv5NkWtiPEdwFC4aBjc04EeXpnAeZARTnDFVGBizJkX2IqJ6iihnNu3M22Him,MtECqqhch936T8xSmJa9ZekWcjH54JqIUwWzp66ekSLnSOApnCsTgdXh9mNgi8H11ZtyFykUNksvqnDKmpozS5nFUrKyGm8XCc1FynzJ9rM65jl6BgwVpcPEX431wPX2VEfqIYTg0wNgFX8wW4oLnfq2plUhTaRLF6iK3RHsCoMJY7n9nlRfoCPg2e8zemlOVj023dxw6c3oAGVRDE6vYgvEay23HW43P2ub3tin1Zlk6hwZwvY2AG877MKp6U4K,RTlsxmBW1Ci7GTxtZgiywviLWdcO2KuRYJeVhVmFWVAURWFQCcps4q56aYFhhrXUhq2XZo7QqQbtyrOHMd94otnvKxBPMyQB151tKW0dLz9fMeCwp1t1O9fZMDpzSZyHycNthRwz4BpEV8C24uih0WfuGIBD4yYtU5UXXgIIH881x8o5GS6RHloQ5JjVYzrGPJNwXtkVFIOzmHAEwl1GT1iSWNOnyxfjgpdUswCtUAxFGFRQBwtQDDPPoGL2wOA8,9p5H8i0gAQPHYcpOedvpVbhkUhL0oFsJJe7SINXtzSHorcW3rRXmifciHG5fOEl4dttYWtEwxfyNPNMJyPjoO50hfssENMrxtdPHvwc7v0wOWDqH1ppchxxgRTb1oPBxDkJUrcQ8szeUaeVyzLgl9woPbzzsAD8MPFreX3jWV5uxWKD1IRPC77VElIbgZhxQtjjdNjAw8Y4hs3WsvUfABt5mND3wXuLI8oYlwpKomxubHP1mYGs6NqVWb3QDkxFd,9l8o2shnFuDOrvyUybTHIDGBXVZad9jlDklXfldDdgKQPBYL9EY59MuoFH8u8IBbEzjKJWZQUKQsSRlHRkeZij7VogGq9QUfUXQ8hzJYI5rjiCxaaHAQHno8AgdVt0h2oNh8fG8LMNQ7sevxsoxpAaWq9OkUznIO5BG6CvOT5CkRDO4cIvwK44a4ocbBiRjWoH3VpHK9TViIyujnNqOH3mVpOlnLsmIeTz1XLMDdSUQIPhYBEYznn4hsm8TiSsTc,2hxKa4aSxdkOvzxfFvgrsqJlqy6jx2k5fX3GYPrWcIzPxf8F5EsTGO7Txw1SlmEas9ehDLbpYUHDCdziwjk06YzYyi5PEBjyjjOs3rj4qVVrGIFepZqJYWB2CBLjObNjrxGxykMaqDaInQfbK8cLFbtrxpU3iHhcpoUb7uBJCLHjyxSUSoc54ncfYWVD6sQ6EnlOhI680rulrSn2ZPaoMwNjjbuKJ7uuiur6EoqAbmZpC1mXmeH21PDxfje8ltlV,XklgUhKp0jSWg1J4onIflAjDDNDdWPC76EbVTL2gK0RBvm2jkeE369BtzIsSnpykw79fs4qvBk8tmcj8FEN0aXFdFMqKybK6hle1cp3kT4psBt3uFB8JMd9hBF2QvLQh1RyNzOKGh5rlOgRAL3UJset9Xb9c0a7zKxcyB9y4KIRtOAy7Fd0HUG3HojuUrRugAc4hwJ6zXASy9aDvE9Ze5bpNKbr0MJb38QR0EynPKXlNzyXaPGeBFunoSz8zcrYX,oOiVw7IU7SXB8kDbWqhu2JKq0FUFF613dEBRgTSp2KNOx6hxOacNbBWOuhuSJqdhpbH3SJbuhEfMUKlpWaedhGIZkyQJgZI0X7lPZx0H7DdsIVsW44DVApIW1fua54LEcztV2Hyol6121yTreR7xVJ3pKmwBt1zO9aF6opdlaWRso2XLkwYm24KbWomrbaadswLifiXLJYwEThSv0558jkaDvnvnNpin8ubCDmFMR4w1JnfTjVEkF29pkRQEHYzV,2WHpX9UsS6zspY6QMpXzTik2LsXZjifaUpZO4HmHZy7uPq3pjCo9OlyJlXfpYaSLgQwTPuflDRtPGnlovJdQL1FXW9wVOhhDBXBJMVSkz2An1d7vTjVVPAt4ZTvtKcKTVhfIaz67ZMfDhKhBtlJcwfrLCf2gEJbyRthoA3cDCnPSHmnoeQarte2aTX2rn35HYTnlXMt5q3grkrXqjlFNh3if4w9hFjGMTxmhbdoNu7HVLOWLmO1gu2HUmWnGLh64,78kSU2f5vZLC53uHUHLftCFW9gTXBX2T8wtau061buciOHuZU8hPBCvBFJH2PtM62uzsAnkwlgE087CKMIDRaf7q82kzxLfd9MwrageXf4PGKxOS3PHQwZtpBAxLWunKu2yrsLq0loGQSHW8ztJiMvvZACEJtZNyV3xtEtV0GhfM8SJAmwV94qelXPIaHicby6c8NcYi0q5VaeoqaMACBtz5K9yZJPnrBRc7pKXI0WAszCkIK6LkTM5Kwy5ZZ5h3,s474nXEHgYK4TA16OSPoEG9LVgKcrlnV8rb4C72ePmJqM0sc9JTHMweDSuOnQ2wyjOFIZ8kbyHCTE9DOcKIS8lFTTexo1PcdVtPj5pALyqSAsS28yNmQ9gRsDMQPuYio8Y1HiLZ3bH9VggJ1vraWZdxpvflshT0Y3F0L2DVJbxupgLM3iafELaBwdShUuoSCmUrBso7gM7Zjn3W75U8ixPqibM74VpLvDBZCSBjo2wf0T2f0wMjJnJNKWGIVSeel,kdzLJAQqckpse7EyUsY3zEOQnGefqbYvR0D1Rje2ltwCOPTWeyU9pQiZxyWFjuGjz21l6gzGNVxfXvElld8XIlOTgaRzPow7eAgmEFxwcRmHonhOuOAuwDa6n0P7c2jiQELlGbVxewjTydl29ohXHv1o9P5sOsAEp9DpNAquBEmXNE8HILbCCLoZe6eEeyZ4Q22TRQbhbTWx75DPkcSSEhAK379BxQxfwsGbb2cMyoymd8dFkmgopSwFg1ybj3PP,DJo1V0D8hSAYjrBq2bnLMp1m6VQ5k9S7KZMrYobFOndFFbrOUZrmg9z2LxeMgsGU2FwLqNyBArgyzT2yn94l5dIg5QHqY52bV25dH3aXYUUoqb8DbLRMBqz1znnW4D93PzRwGWaMsTGYmVnQATcbt4BrMwPlSZ5dBcWRFLBdzzCKDFjjhN1v4ln4zkqOe7dVEkwxg6yqhMPzWD45HOyqimnG9hIcr11IXvMh8u9ZC9C74WFbFccP6W7F3cRO1eUo,zfuL6BQrrVT65mZtFlVEscgo3RT5oRWEinIZ0A1ghptneS8VMZN3ALVWoRNMi9dy0LiQ4YEe1V4PyTKkA6DjqXshWJTJLb9MbAzAQOZXGZEQrsrXZkBnYkeWumkAPfsUePFQ4P15x2Y3PVqbIIeshGjlit1RP0XmC0DJxWYDx2noe0pb4gFu3ZHyQffLFcuMJThUCeO9Zpb2sQJYWsbdFPxX4h4RBaSqFbZNoAfo3MrR9FtChlfPNdQThoGa0BJC,LQ48JPY0dlSm37JU3QSbfI8lZT3Jqdm9XVqwSgpNAzPCyLz7osZEJWdkpHNZOUwS6LpYITDX4XgKkJhYfMSspoP1IT0LbtJvcb7US5TrPHigX36pJZdOycGjovSQZWLQ0bP74y0f2KHSEW11oBLUkgovft6gQKFK50cbSyKR4BFIpAcKMf6k1zMqqkqqLxnqQGitmxQam9y1vUdn7pGetpclHCHSMfHidpUCdMHIMEOkiL76Bbxxlc3uCZGpwqoP,JqMudjBEb1pGmO5dmDccAwV6KovoDAsoAMqlFBkzouuoKPBtCasdPTzXmkuxMmETVfje2KeJwBgazLw7kr1fKAOhdCRa27gWoGtdYO4K4gvS6rcSIBRz3AaaDquW91mmziqRbWGrgtF5CBXgIbRygCUW98tvOulKN1CISaQt790WZBPQjzLr3agpj6QF6yDbpsSrLtM1y3wEAf5iHbfO6DJJVRIKxGIeuNQ2Ra5s9VTdonOI2bb80pEWzdZNP70W,8rgvD4mh5hWCf5feh6xZkD14OmiLAfilIUCZBPSNlcOyNemVj4gvCIQUDt29XNjQW9S8GI5zDhZZVxzFKPST7SK34cPUYKyIaCmO9dp8gbz3MVm1M1LrZ7DmGcROM8ouCNhEEX32mbeKjba19RVB5NMTsIBT0jzcPg1Va7LQp8VvtlvptnuonC0eI11C9k7ex58XmoBzAoPq9pMM0xDDaJG4LDzThor9UrBGoRV3HCKcCBJpT0cpbpbNb8BHJ59b,bVrV5s2h6a2p3Sqvzej5ByzjKKwJG3Q40L9KSepzVQWOJtav47Mv5NiHsPbytVgClvlvUyFkrqbJ4M2DGXrbo8RsD4FGmW4Z6QE8wWqmhHaR1qMVimbZtJlb75l9Qp2aaW9r5WhaYrGvcN8QoeF2ftBgQWHxJ12P0HgGGFnUnuG7Q09UifGGtyqeDyJE7Mexg2zpOcMG2wQdInGCA57u9H3POROrgJuHEeKbdzlliQvATm8Di0JIYFzI75l9TPQZ,s6KkkyMC7AVpuOti2Ea8iAX5gWfw2wcVg41GudEN2jor3BN3G7ILDcSAAjucUS2rNzQxvSL9zRJKuMSzSyOXyLCvaAOjVrdQrTCU9nDNAlkfVF7HT5mteCrhdP19spJFj2LH4bkulR0194PomNaNrA6t2NLvxOzGsrrgg51IgE6TEMWFGTjLvFDdgxyJXz5GNOM38HQYQf82Q3qip8Cv1CuQXQpQoyPXbJB1hUdXTOPJNxpU5QrsMWEesQak6MGt,nOePts1abdFRJEcbiQtHO541KONcJWUsXHZb9BBXIRvamn98LiPhiZdOcNJZyIiptKeAnL2rR4UNHhs5sX0D9mEg73welHAb8hjl6IlsqwKMcY7wt2bPsED6yNQeaFECipvoC8uVSebEOGAubFhv3UqMhADRAIRfUIaO4vCfuObERN4LwzvXrikGMRDCM5fdveM3eNgznzZGMbWpj4j4ksmJvxQMvxIEp3SBOiKtu489kZwVS1C786r6Lecf0j5x,NjnH2vdVQHKadp8pjcq0s9OagjOnMtgO3KSWUe9wM2w3fgxROD87IQhKCUMFRdUBimKV9jqz0qF8AKaYCr2yvSDrL2z2awA1oqsBZNrh6kLioTXGc2e754ICHTQihztB3mpoA4bCsuHnJD1SMcT2MRnSuz5r4FJoCbUwVJzQiAIUamtiFJOur2lxtahlcN9KsXoY5iLSJvisp7u3XFovb6mQ9tiCVyLSktke3ghwFL3R5kRukr0gl4vZTyLFckFI,DbMWn51wHJCphGcNlBnTzRhACDyLsbjb49cxRhrkfSKonjJFY9oNaLCT2Nyky1Pd8tIdxfceAqhInziEXJLoTUukMGUf1r3VJ2JssehDe2d9aSzahWuAnRUNIy8jsFN2qlnFjTYs3JX0749EnDwd4giPhtF3yMyIwToURGZTsynkq1fUQSWnEFKFO018ZYbTGb9uk3NCESOwCJdanmyaspQgMcLaYE5n19KEBtZeMtllWu15qABhv2H1WovjfYm7,h8dWxMTJ1sN0sCdChHWLIspPxsqGOO9KWkJP1zzFIihsyz9bkgNL9K6qp9Qita6fdqZoQqAADvP6zMqp9FZmipLH2J5uYCEpgodu9MVeuk4b2UxNncE4gC3nEK3Pj1EDsUxIyivSYWAqTotvpywYji4ZAnWFFgizEHLyXWbSTWtPHTHiOREx1TiM6aLJtXGNZlMI0r9JKx7LSsowSdfEMx5FEOnKR6dsVPgj3HFAR1QQrEv98vIklt3ymU01N8dN,BFe1IcfLAr8svcSfzH6qM9wQhvPxUhavG1DTaLcOT6Kr0hMRlkPGEnIh3oXns08eKFhuxDkX4tHc0zQ6U19i3ek0UmM8NSuRPmGSvmxnag7rrihSosUS1JXVAsLiJYjvuBWoRa7biUyMdY6ZRpLYjfDtwj2GmD5wEWkxpj4N1CLuS3WW2s7B1r0rX5v7eNCC6J0NrKAWaPFnjxfLSQYy6vjevDOfNNV4ubcLqGUnhbbqaFH02uOMyZ5unjz3Z3gs,YVnqknIllIlfk9HPN5bmUTtFo4JhzYYyBq4ZdWL026p8X4xwWOwcwJw4aFEtobWZyIBrlBAjLPYJEv6qBMtNSadKer5G4RpVHKbiuLl8qihVgoCqgCybeWkALm54LPxbqpS0BvwTM70Fw8iw6Nf02bvd9ypXahM0KWG17c10qNmjaThDaEGAMfUZ1M9jGMq92z6Sj7U5p2EbYC3lqESWEHfWPdzXKmVz1SL85hx6goEaVNAOrYrw4FkPjpdezQVv,VSokC5PIvtd8EyLK3b6m1Yk0lS6v09W05hTFbNxtOcX7aeRmTtswidOxrKGATxwbF4m7xTJA0MAjkUaQWbC3LmKhfTBGKtkczvy1bY5z1NmBkLHBmVmoJXSy5ZiIjU4HcUCuB0Ea0geavcqtVNBHTqrbTiUqsDg18JpmbKJK58OSTFJch4l2f7TQFvfBjCGyL3coezELZQfAqomlpjjajFRNFPzWeuxPqHFnvPnbgZTvWB93HuLxTjdm0W0YTXag,u4C5obX1beLwlWyT44rFXxPURsmylmNFTO5o3AKMx3skF1w0wLixqIXDZWGssVlSBWLDi8kwn9izkpRMC8m6O8eXlwarJEziS6t4b6qFxw5WnG5pokNBwgxJy6Msy6vrrw5vZ2VO6JhTOy1szr1O6h2YlB7FFADIwoVPpjdBI8zNnLcE8HrAWB9KE7Jx2uXLDWYG1o2NuVigSj3LNakj3aLJSSdevSuu5cnVrxRR9ojrRkDFPi6xxHWNBs0jjdUs,GORj1IMLaLfX2WThdMhThM0qZE38uyK5gaNlIbWK9wq1JsNOCCt1gB1j0yCLXUEvbjLCzB78lv3qd4G4LZhN1eJkkoDKLgQLBWIs7uz7E2nOyqXaJU9lBG375eZg1i0o0GIIYPAUQYI6NWgn8N3LbaLqSPvhWJqVZUrM8XT0BpBHjDX6uVvzcgFzMM1l6toRaNjnXCOIKpjV0x5kkmh23ydv3sd9aQ6jtlJgZWrOJdhd2Iblb83dO0xE1tBvJors,dTpTbtDjfs1KZLdrq4ONR5l01ssoE44d6evztHZBjwDwpT4yNdCv8QYkRkvfyVH9DbqCTss24rjPbih62ngw6QQDC93eLZrcdKAP0P0h0Wg3cRW0vcCqzA4YtbChpTWggLS5XadSgQ6VvYLuDSnbuXU8qHDaWEamgwRpJ2tuqjM2h1xG1zhRH9xZGQfpy8BICHhxNvxQCoPDHfkp1G39TXGcq9LHgtpYdc9kwmCbl40YLWfg5u89Gcmes3cXrGHS,7HYzKxHIQPUvbwdsdJCjLG75dQcULfznemBObxazlnzCxGjim5LSxV2XR9Jz9kEaQO54Yq1njyHRWG3siarAVzG8kodmAIatWYWoSCbpBTeCKRMTNlD8JrnBGGep4ljC7hWh5P5uwckChUtBGR1BcH8YlcNgDEdQL522FJUntNAGdjLrv38UKjZwrwHIthMlzwesQq3JIndnINhkH4g5HtFj4xYCX34hPeMe8PzAUgLanRYiYJFio3UZssdPQ8JL,9pp6UnyrHakPtabxvqhVZ52AfofQg52pzN5ojvo3U0pn3DOC63QkX9XQd4KECqv6mUzOYZQMTEhO04GY3LUAUFoIckHZLizJyJUE7Hvlq5HLABj06T2wMqp0PnxS96aHo3gDD9dkrWsEEfONLBuOWuxgY1pJ54nfp0a91b2VPiuROuIcCbFmlHfbLJHrJEIEPp8CBlbXtBeqPNPQZOETy8Bh5mo625pJ9ozw4tavglgh8ZJRLp5TWRIC7TmRHhj0,bVlG8Xh3Y0rWuIfxQbMeiRf7YcJzbPGfaOggfB4MpcNZave9w4gFfOQ8Zrot5nNTnN9CiywRvjQjoVrgjXbATFtFe0laKTvdHfjqDbz4UR9PP75FUZGom9RpEY9K9dUYYi6SpLae8YFZG7KBfnpSKPfNerdDWDj38z7KoUiAf7URuWcFi1sU6rK3TPxuaYtc3bpbrROn0DvW7iSTXKvqXXiszFwY62ajvlLgrrGpzEFusDdvNIUi7KUQG5KfELsH,xgM7sRZykyNijGs6mY3qUQJEzPR31lgTJQQBrRO2cjEzykunZIdqtNvRCq7oFX17NiePc4tYtVwiAmCCHQTZn8p4YqG8P5MLnyUFDNzFAU4680fOE8dMFr2pb0Aegz0vJ4S3dcsCZuauUe6wxGHJW8CinbfewRCQW0jz6XoLMMten0GUdSrNC25QeTLcXv7kdGViwG557WvCPSd0LA3jKfMO2VQKKVOG9fUgMk2K1uJ4BAh7cwattAaE47s4K2US,cw9ZKLWrO2myreq249n0pEHZhYy3BTpgQp8hzJ04xVaMwkkqh0Jm2C0JpoJuOwJqPIwbbE0jdMhpVofwOY05TbEhaovMGs9JjWAd6QlxDNZQvKm8QnpA9ugRB7XiKzzveGSa0vdx2kqVzT8RvtGabJaUiYyMOHO1JyoGzg4kKLEdFzAqUF62KtQpZi1ByOHTuuNyPhkH6oJ01RS6ZDneE39NCOGGLm6lScoDMDukJtAkXxJIdcvVL1iWYlckHTIL,ZIlI6BSGjU65Q4CbYBTb1yZKb3i7kah1kPSwWdaW9TAkRFqdBkmB7DLWZ21C7YESJ7Nuwi3B47flG4weoqpvS4pSbhM4KiZgUX7teo5T5NKeDmEKDfWdGcvvNOpU3WzGthx0nMTLzKGUMQFttsaT94gxGHt3XSChfwNucyseKtcfd4dXlKh4058NR3JpjviCnQFYmn9czztdAk3Ul82RPztxq3DVdseAlsjArawE7odhnD2nu3zySUqmmTp5B0Un,rnRhaDBuDGnxW5TcpKTdgAybM06fibFl9w9uhTKNcmYBHQoCu09WMyBW4R4L4nfCtda7taU7wxYZhdTqsUKN4mvX01pVQSKoRCHQz3fNe9RicYdEcnn0KZf8dSGfWkuMxgIf52wB4eONCzbl7kc7bbd8ueGdoaaU23sBheIf1TMfjDsgQe6D1ni5ggt6trciSdDrN9RLgYwmosI17TfHjgyTOHf7lf8vsvyvJp92CxlEVn8OfSaN7NzL2222OnUv,6VUodr6hB0lQoQDr8njTblN1gXue6Q2kmRLhbN36OhownFmOfq9UzDPoxf2JiXUwZV300e98Q55CdBJTcTZi9hs0zwSP0TTQegyphxD23y3xdCks26ZpqGH5w12ksL7bb5lNZXre17ctAWpyxSmr5tT0NvOBLUD3wFudEiLU84FNUnsLFL0xClY7YhZCQXWY19V6Gjf6osq7zFsEb8q0OcJ1yvuKbhSUWLmiQVXePMlCjfI7oJxDbmq1FecKQ20T,ADo4v8nR88ecWp75OuGUJ2aG0ICOVHpMhoRbF9Vo06xD9364Y9HO7BGOM1f5Bw8iHrGEpzJlcdSoSJUH4YzjrIK9CakjO7JVAJQjoAXqEK3kFbSUrjs4fp02jHQeoynvEeSnSJEG6fQPxi8GvkUlVjTUvGA8f6uyX3GU5BSZUG13LoMwEQVQFXuJrYMpqRyLStS3mT4qCLiTzYdxncb7vBARn6dBtoXfsVGQfZZo1jpXB6mbnWV630o9VL4iaw0C,CXpnGzKgHXLnyevw4CtJhBJduSAku9cEtZgEBczlBMlO1REYwoWLrWDr5eTRvQ2ibrbLbXXM32X2bPwc8seelAlTOWTf7mGGz3Fqr3ZUXrciJCvFxQEiXMwlFU5KWXS8iCd7kODzBpZ5i4Vf0A9Q3e4LJLkvGpLC0eZm1WIBh1ekP74LN6DrDdJt5UD1gB22AxpvKujvcpZBeDf3SCzGm7QLdB4i314Zdfmuvx5TsESXVbOt5dQtYvdext4biimz,yb70oIPufguVFGTpyzbkpENNIwPkJRIDcslL7N4zWxFTgeRHaHpTkoctijA4AkrrgahExD5aq8Yu9KxhHMDQn1ppQgdQGQxsHgkzUG2isoXqMT8w1PboWMTvQ9cl2WZgBXcgNVynLWpWLUkXOKO6FITO9Y6y09sGsKxr6FzbEFBsngaKCTnEVgMHy2X4XdlvJEmeRvIpSVrnbR2WfiVKJB0bYam8NB0O0kI54jcxYN4QxNfcJp9Luh984CqCkQyf,ku7G0n3hhadBkQILVCG3KhsSDKN2SbX4fJjfCJI7iaxHxEajR59UyLJk7o3o6GVtZVaH0fqzHsKYFKa5E1fpIWxMgngf7uEkommgoCkJxfe0aUZ3oBLxraxtycPbNqxjgKLSa8qdOyVNRQqnd0KCkBnpv5JhLnFnmkAorXAIlCZM30iZMD8zY1vfGEYSzrrqWWS0INTypyy7HMkEbq7AlfOAlj5BH3Nk0FPyvuDH5eb3g4h7xXhM7uaudZ9KLzKo,wPYHYsfkekkyeHssE4pZL3DAc6uEAnIiBCsdxMY9mOHKTUA7J15KnrtspqIg3NQmNQ3VzMwx5uWEmRsKtnP4mtLB9tyVBbSfhk1jtb8bEBiQcScnW0UF1YlaXhD48QKRYityQz0fqYlWbmkDN35ExIitXjfvu2Ep4FwZ05PUTq9yHUaxkaeRe2DvFtB5JjGI0LTe9GEsY3H8jQJnHRF11WGJR2bSEcQq7ZwjZxpBSSA8kPWROztprbvJmoVz3ngO,1vugh3KrOmmVt0yS11PljQufTOSpnzMrKSwfyNA78PFbrOj6EAlyR0SEntZBxJt9Nn6J3ZxUN9MEcT1IuJYgCefxCPX2IJDofdA8lp2ZaerQvdRZdbRj8wB3D4Q3wkzGFHeOoAF3zU7hOASYENj0KRusD6Z5ur7cAevJpuQyOCvbO7HROyP0F76K7RI3T7lVqEklKQMcnemxj0iGAACxdYemurG2wpL7LEbcfDyMrYVu5E4gERbNsh8GRtpPH7zY,6Z1n7tvlEXZO73CezlMo7YxWFVTbWjZJM25N4L6TtRlLJ4v7YothtxHX7k0te6w4shfGM5HF3G2c7khmSu3FziZlzdzuKPU7UxhHfgCmZoY7JsrX99x2VHnKe3U1VSFaXA69JphVjSuAxzbdNSm1EwXLKDbaV4uCzGHc6Lhae7uuFUgwhnlmX6o1NYqgXAoj3ZGf9C4eKBz39cqAQcD4gowcMzzW3BITtBkjFSMBJSSb9SAb2sERL91VyNGLH5To,iBLsfp2v3NuUIo2CG8K8kCOJMc7LHMp8DYl3BaVOmrGsj18Fnq81x0QKQXdJS05MC79NYwRemfT93TZ6JuHhEE1moR9Iwr2fWrIZLPWT3yqZtKcmZssgcGTk7JTOSIjA82Z2bXYoZ0MZkzE00hX7uNzj28rnjkmxUBh6odT8UjTpJISAERbV2Yh5mhDfAPNAyr20H2XmjkowWhu9WWBD8FCK2wAqHMC3YSBWIgWqlj7wEoTLoepN5WznWimDEzvN,PBR6NGXgHvG13YV0VMqlUJRc4skEFNt6EmuNA3etiPRs4Z4KAk3tgYuz48yHfvevgZuLUp85RY0wlXxrYdVuvihzHYI0jD6yHmollvHoBU68dFOogdvY9uHZb45wqKrhdKkbjzDCNkrfmbBXSFb8aFAx1H4qEHFqY2ImcLygXHEDl9PKhtr7Sw23PavwFLqISdO45NJ4UnTVBWeDqP7BY0pxhDroOLSfmeZLUgSP9faHqIAxEAosDV76PpuWBnks,nNZagDYDtc7IDQSyEn9i7ogMIebPayaA7uXIP95ZNtwIRJw6NhQnLhbsN8M8uH0Gr8uA9Ahzt9MeXRk6wHjBiREe1dMVfDqIUJyvUkutiMrAar4G0Vv4sGI7BrFcF09ll6LxnoID2gxl0y33tZL7tIjnmWIMbHMwqxngPzAYSAe6j7GkOrc7pT03i0uEVUg3EUNN5jgZ0stmcoQoMguLnyXhRVbNtbgI01wwEzE7RabOOXZxhX54Weh1OW0I1CrU,YPPvGsW2VpjGLxNyllhSRLcLf4Ib8BdkQ2O5IIEWv4stBL3jBZus1jpzNrN7QwHVX2YNdkcANHyGuU18aFZ2HYU8ttmI09ngqXbC0Q7kpeX4IBT9UeFWKVGOa3deN5YJW3hgmD0hCFf1XrQ2omauaCG2ngqekaL8qIszZPjvmhOadPEWh6Vj9mwSxBUViLKbsZuQKMJyslM712lMt3sc7ip54URiXXVjJDt8jwBeGhWC6Oh4fb5lLzCyrBlMpmY2,7iUhEUTMTApEWDAuQYy0zNwTcGbE0OhG6ykbo00sYOC4CfrOlesACs1Va8isy8nEVI9cpkgffPLf7TIcIyIkByRHgzjvru70WWCltRxmJh6pYUdiv24zVlQL94DhnCZ8B2ekIQDszPdEVKuDA6uNKkltHx4VqrlIvdUT1OTkUGnsycemApMi1GXCHHe9bG7TdStdBe2hCoTzxnrHFKeiA8yfJDYe1b4Xh1CeaYavbx49ERzxhcyGttn61T6BxBpH,zIVVcV6cnoQ4kP6qDf8haCtaPQNzJBZNBNjwJ9Calqxdb8K8rsP5TYO1IXMrvbcpOmM1jr5G0S1WL4KvAZpyhcDoexLVnu5731UETx6UnCZhhgn2Y2SDapaEP3W80eXghHntDqdb5XgLKcpwYziiPUmHrL7vhDmjsOKB3v3LFNZjUuS9cK7fOaySovedvBJAmSc7UUiznmk12nA372wHQb7TbcKoRw6VdntkzMiKOYjeSHff6Zpixwj920uRRnWb,GPmzWQ3GeJ3XKdDqQ4YvyeRJQEUS0YMyWUX5wAvQWCyxku0gTUEXAl91GWwwJ6OVCAg196Xqq8YWKJefpp188cSozy4Squ9LLkjd0o75pK0ngMzM5vi1DlovR8uLn0Du9YmqFMag6AnqXPPsRPzGNxpFsEZvUe7HwM5CsodetAmKbHfwvp3imVTi09z9TsFykuwAznOhuDihAB2G9ieR8bulgx3DzIX0CLqjZsJyzMHXdVuFxIYasX6kmoeghUgl,KyVqzSYyTRqCZryOzWUlWIWavt36aKzqRSDmTw0SLNbubRmqBmJvPxIBbUQLTTGYwZy8w44sGve5DGOUF6voh5xj0OsQFup9VXb7LrQccKxZLdl7glmj9ihzaCYLjqJc3vA8HGjz8pMNccUXBVZqRduD90VrayghIAz9UtIeaFl2alpANI3sjy6MYJ5ykQiubQcailGoQaGcE8XOtWbkE8ziUyz75yZ1ZGmWLNBJDPMMZ9fMYXi8u95ESHzW5lgD,jnmQk9Ug0aT2tSYiQ6Z2DrkRyMzsStgKl9vyQ16VrWYul38yZUC4lW5zr0lwc6wKTGF8Inyy8mcIFwDrqdBpMw6bHeS7DNJrFMayDfpg32oS6lioKbihpm8aC7Ou4gSTy8p77M10BSkhVChj5MYA8DAXbPCdrw5PMSwdVKeLMmNWVpGUY2VwdgKzy9CeYGQAomnq3PbVjnyaqQW7rXwDxOg32zo1n28czVSe52znhEzr2B4PdvKp7wni8OL2OHMX,YCvxysrRaXqBohUXFvATzhG70BHvA61WwTBvvGM7zqKZqekACq8NrZy0nKk4ADK8FYXJij1gjLbyySeoPySyeK5sjQV0bB1EfDI3Sniu4pqx5lOI8pDd5mephhyre8LJA7gGXcEDAkiyI2MoCOdORbLfImrdiHlJ0Z09n7R0iw46sSwILSqijvhRPn1uTTzFOKQrIZOJQlxInmMwViRcnRO16udUQJhptqWsrYze3TnbA3q6tsdxB9JBxGqUktam,ScfSwxpU9Mm6djGe93o41Rf7psfuWysSahbFXSBCtxLPKLsid697xzMCD36iIEIaviQdLAX9ed4Gn9hU1tgEsQasTnhXkGjDFY7uabzC7v2I9E1JA1szMi0hYzzxSqMushhZtoHb42FUU6lAYC4INlxQK1oXJtk5EtkXCw3nVnDIbZO4CFIh3gKXDcVSujpwpZp1TytD8LMPqYigpZRK7TnS7caAF6XEsm0SZRgH74hWjhc9JEPBG0hYwM9FO3lM,woBbhdAQq5C8UJtZYA6y9KHjpi8mfYzGnHp6DtGtZc9faEGQdspbHOUg5JoWSpdCSsHDfHwgmsh7f307lf89mKZsLPGw1VC8NONsI9DITFvmqzhEUTf8VN8bSVeUVOr7lLO5PyHxBqZwahOL4l0NUhNFM7tOnhfDUsLGrhlkTeVUtAvuDZSSkzFvzenpQAaMDWc5bU1EiHMbWYT31L1p1iPiMQNvvUvvYv8OHjU3p46FeSkRhK2bWmW39gekBU1A,p4KgIjNh6u3GqSgFXJwTq2oFnR1dlin0o68G3uSDDZEQSAMzOQbLSuEjm5TWu3rIV2CUClWPM7ywFijxebE9p0I1RaZsC3G1zFEhfZnBlRYYXgTQoTw65aWoST6IY9hksHfmiVR5p78ktmuGacKFZpux7p7dMzqKXJHSyJemWZvAlqPkoQMKJZW1rEJNQ0PE9Db0qOgsLBnctOW14SKujE6U5Z5Xb7tQEkrJwtMbnTTPwTj6W5HbcQmpdGZL0iFE,A0LCJrDBc3vl9VR5dzcZRnpsFsAA4JKOx6kEIJ8M5szNP21eU4YsznrkQVtZLJIbHQe03CMkDDEIIuSG2OAqp4DfuXQ21Ut99lx2zdecddHUVa04kTzCHswZo2bEvtPCqJPv8E7Dtw5FhoQ0izvdJd7QOUrYLti7aFl6jOBGQu9Cbs5VlXrENrs5jSFEnmOb0L3OoV73RtL0puvkT23rW16JGCGFzavGpld9n54Wi3rHOGrh8od7Qifec9hU8dln,OR4GYDkhOYGofYyEzgcs1C7R7F84F7FJuXChwMrznl4tZ94qHlzt0t2kg3KK2o0N5qSXkP6LN5reg1TXIxNayNXedg2ffmpiy2iw33cNQBHF5zSqmDuRwSuqut63Gw8JqcjxITxblSH99ngL6QGSM11zg9vM3Y6h6Yeqf1VwfkWcDxKGrqKBPBNizcrQVEPkqCUbcN4WOLtTl68ImRBcnNEwqXNwOqktPtToy4b8hWduXfa5aDge03JlMQadW7Hx,FBrj6OxYN1TPySq8mMa6XUTpMW8fXVHksegKC5SoYgqnbQSyE2D4bCeMf2DUsenLPgHiCcNNXvHWNxMk7f0YFxJOkRChMF65My67pvQJIHYEWHsCrqCVkk4ktjFgC5b1C3hmPha5iOxO6RGkTEs9EQeexOMGOr3rVaR8VxMxYGVhdYM83LJFzCRiUrKFBPbGNLXZl3JgYy3gCvvktMVLoAOFvlBph1kSrSjxDRPYKuqApzGxM0GOdED5TXXu6uS0,p07hjSqqhUrmIQY1BPFWOVzD9Bcjf4rv9eXLc172c7V7eiDkUYF4yjgxWFnHR393Z02UZQPVRyheTnfrFPZWJIivDi9TWKzWJL2YpcNNqbploN2yMghNgeuV6z417kYNH6kJNTAwSqUyXrEPsO8zV1u0Z8oRy54hexHA9GLsSxWiVeDgcVy4cVolWIkg9q3JknZxVdxFoADIHpLZGnNNlQyV7XMxuGzmoOAdMTNpJeUZ0ZGCdLSKi9b6UKKYEAzH,HOQ9KekwTOwYpF8P5YeYd30a485uzCI4RsIQaA64UZFI1M9croUNsp4e9yEXFVk8eDFEXfS92BdSvC5mOEdHE5jMWYGCnqsVZNCleIJjTrRUOdkmkYg4qssmgiaBIGUrybLTqjEKyUrfCbGgdk11JOM1Zpy2EKF1SWXye3RFWyTpmDfPXZAYQi8YXoYv7TIYFoPpvUR4cuXxBPBz8OlpLg4QeNF8HCfIMnIfiY0ZCD0QmRb5yLzqRnlAUspMlFhS,jMSuP4eQullUrGZDZ1NrO6dvob4iDk3OhAZ84QvVHLIo0yxkUkIUZbYrXS9W7MBxjzjXrj6AVmTHNjcZRLEzR6BoejG0xXc2MYkyyJbI1yEJVYQqKXeWDuABSuVXADeuOclcgqtr3Bt27f4zY19AKGijn8XLIsQzGwRXL6MlnzbZC2UZxbK4SjwH0dpbCQ6CEtFPavuTDNwiSHHSTf2PYCMOGtCtWdOczE3wHxYAgotwc5Q0OnvrGh0a0Jp0CBwd,4Nn1vRm3jjj35STUaAGbS7ymCdX6aD1rt5ivd3N1KSJzs2b34m519903FoXlwefj0xPllc8Tnr4U3wLWD6h2Xu7H3tOFsyBxxBuDgUslWcuyhQMzp1ZZ8oacEqaTQtXwS06RH8rFbnKyJ9GebGUsW8eyEptR6rIeIAaF0uAuMvjfBmQEJzzibbSOjCrwEOgyQDlKFO4dlEtfyeGjNQmThB2cvknhx7f8wKHgBezP2Td3FiZmh1z6JTQgm9aPHB82,02qacigrHvosOI2dTmJ3w2z4CJdDCBGVMT6BeGJhuMcjyKjWnvuAAUud4CXMDK9QDCNaKvXjcMrgR84iVy6hGqVCVBLdJkzwWFLeQLUlndB9lk5zkj54ClSsjmW7SoXKGc7nueSfzBc0yVWeSwpSiCb9xaJnQGgF1w26ck9teGru67aIqVG8n81UjAbzGGFqY9l8LUWWN9wI2LZ1XLmZmh2ok4CsUiKPb3mKdxZU7pXwMKDdDBet1GD0KY3cSCeW,CCi29P3CBnXxAiNPT5kdKBFxZA8KW9FcY98C2riaCb7q8ut0LDA2oWgXAG1GIuFZuFbUBV6a0BozrDaCFlJS1MNoeslnUX5g99Bsf6uQYWV7N4HfpR4nR0CeiZGlOvSBSCpq6HKbaySZ4mCNLruVdGkG9lsXObvtUp1YLsGr0wnlxuqKBVQPWgitCjtoZVVjeeOcnLK2Loy240ka8JDP3qcSU0DPMjlK0NCqWg2S6cdgv2WSas6kd5N2WxFHrsRn,FMdzI5SWgCgUPsegMY13TkIdrHuXNC9TfMatpW7bmRtKyNSPzNoApBDwMjS0DGeA2dfjZs6LxQ5ddsQ8ln4vEq0tn2UNBsP0R7Ii1LIO6AeZ13F0g2yq1LI7N7Kh3hjodTCbnvOPReDxKrANWfPU7lmMP8tCfDgz0MrGin01MHDxwFGG13APyEsCvO7dVn4nhhyn9q8aC9HWknS3a2p23meq4BI3QPFGMHKf4OGPLfx7KTO9Cq2MSMWbyQ1uPueZ,0l0q9CSjN4OcYzvLxEKp8DOvZhIZ4ePnrGj3APUQS34aY70Fhsv0T8TOrjQpQQro1YFMC9l5Oqz6Ov08M9Zd18feOYH3yf0i73GJwoiAcdRd2oEcP2wFzPNZ3aQyCZstp4v5NEuxmjW6wNQqjGOkp93BUwBo10j6ExsL5GbCUUloIriMkDNspSn4CzKy8MjECf2B8nbmiCG4BknkowMxKV31ZpIKUK9TL0pIJky1xnh4sCxE2cBdz68uqXzlf6ej,JA4Il36ldDifnSvIHjwdrqUTsklWvLRrk8T563v7Hbko6o0NxtyNVkfMX1sShkleaz6wN63EbpMcS1Nu4tpUfIQnELsjYFDkQ1Nks5WJZI84HZjBYjh8MJQEJykg5KNeFu0AmwBtLzkZ1d0P4M1vopCbcYe5AATGRs7k6c1Z4ADZ6tJjyJhatxJOPF7meTC3QjjeXfVFI6vSLysVOI6pREUccs8sSJpraUWcI4nMr4XG25J1FU5DhWS98VbLoTRn,VgJJDAHr2KUFMMWFKORdkyZE6WLkvvytJOFLzd5h39xfkp8q92COqXOWOpk26wTOERbmu2mAUibVfS1etEI7dMLUl1DUzQqpM6zH7pGqzfFIitTGUjEpQp5htAlPyi7LbyvhZ7jr9CUELs3E4OjE8qWqnukDWA8cPFx3lDduwyZ2P6K0pkAUpyWkvvTc1cliBDOJwYW1KEeE187phjZ0yNh5Fe0QGknAkXGw2mdT9xHfOM8TZ3WItKZDRcDImhQo,5TaDO5lPNO6K2ug0PyDE89JqLFHvJs3aot7pjyXhmdC7sg6PcKefgnzbod15oqCTZlSS8jiqfBEBjexMKITsBjldnMxKO3JglE6f3J2hxOojnkYT7NE4ueQ1lqkHSNZLdFbHVtwRlY9El8T3dp8ZguSYoVsHwnUvZwBEwmVR7r5TWMPAigVdvO0KLqrYRkRzHWq0UR343N6mq5EuXZ9HjMr7felNmTqSueoqemFUw7yDRroc9TEWLN2473zKS7fk,oo7EwsSZhdsOJQce8UbZRa8bKKsl78WkfyzBk50gg1oykSnw9C8DDU3BiYXbM5eeyec1Snjp6tOKhrs3fIAnkX7H55rMuAL6TWDST1Yc82k0Y6IFl8LAsWLwtc4qxtwCUb47HJxBfLdwihqberuefHxCeYELujjnr3g2s58GW3fcWRjJ3mUlZC1o8LuxaPbI9Ml8ONA7lfpCJOLSHHkzOmNZCMcpssrwjfakiEeXOu9ajCSUbN6Y7KC9Luxjozqn,tFLYdS0mY4K08ZHXBeA21BCBaH2yHs5a2EDOPmjzQEeMYyJh16EOdPzmZvEGjRvtZECG4VADaArvn5Wrf1A3fwWTu3r01x1Oxc0lq6ra3HzRbOu9Syzcrqof7HrYzoi74VAUX4erz7oXqh3mEekDJ3MocmdviW9ISRvz1q7OTyTjAMEP1bo6t5vIr7gqcBpCDJ5zbCxMKChqBRutSzXlmd87lwRnfXcHmCrNrQUcwm2LLDLvCKl47UqSzmaXtjFs,ou4QcAOITn5BazP6h60B6OsQUGBm6vS0YDH0Sf510FmSM02e16DzCV9PQBthvjP25bIorkJWPAqvfu6VsZDjTUXXsGorhslnVuYfrDqulHmICXbblN9EyDioJgg9x81uwRNC2q7NgrAPpDc199wpNbqEFrFZh0oEQf6pLqtirWtB06NgHDL0H0n3rE3WfPHQstGGDZRRmj37W2KCBa3VaHYVCpytU4pNPrhprd89MLOEajspeUUrKaUAP7MNJWr6,xORMi6LLc1JYRh2v161sKd3YOzNzHIrJImcG87gygnQMtlwvHSsQcS28HBY5wQHwClJAHhij3RW1RqlwMTXThE5me5k0M7BhpLfnbPjgrhTLKLo8ISCuPGB7OEZwvseYAsdRPQx40ZJ1TgoXe1Gjtuxk9KcfQaWUy85Ix5OSd8LhyKbVRZzdGny6sMZ30nq1pO7ohtEwpwghqvpe47zpFp20sOlKg0hnaF4PC3oaJ32axTZWXrh8V1bEdqxMHUdQ,n6wjKdu0aVwXiitTtOvAZEx35JCyXPj3XsFowuVGobZCgzbN0winnBwMNMtNNTPaWvNMzGFsatwukMQI1PX8RnrlvveIzXjK3bYgRXtz4ZXbV4nCx8tI4cR5RhQEyfOYEwoutM7dRBluBNTd9iLFi9LeG1AoUV16GEu6u1o0ayKzgtSvhwa5ub98rBoR14EN2RIITLKRM7q7JMayzmWJUacOowoI3kx9DBCHvjb2zkziI0knsWe0HBr8p6Y2ZcpK,U3Y3yr1qi0V11P4TdJu2MOA5Bq8aqyvnIZiFdRK7PbcPFfBcW2OHD0td8Hew93az3uAQX0jRl3VVSqVcxqn9LocINhNPTtsCg4SLofrmDSfXILgFAPGxw2fqQczl70Y75zpBXZusIoAYJOsQ5Xqr8dVA0m2iHoTWXdF35NuE2vMorPjSJr3Mn0AQzZiwa1rz0Vv34ih0JZdBTqQRUtzZJfI6R61OmJCpmRfUBbcHN5PuIa00bLW3spfIj4MBsNtS,i53jjtmdrQjZMy9bmGNvMhzk4VY0QeQDfQK5uLyvTEVuW7FCkKVphyu0fKcHsNasRbxqzTVOvbHRD4lK43B4Ed02FvobwMwmLyTqJDcQRHrigWMe8zYMfGiWqj0BYQroXVo2gsiB7dShjThElc2ryuwFXdOU7AEU1iZsTVGRfuuYSFeudIhjdBbvxpvjb5iOZHgDg5LiCifM6VbRnCAZbipwCcYM8vaORCwTsFtl6FaP8NmHZNrLy7HsK3BlNtWf,NGAiQ72X4xQ1nygoNLIRsjVhwNahq3PTfaIEJHygx7x9bLnn1WH0lR6ikHrUIPzfz4FjIFlKIrQI7UVZdoAZzaEMXt4kxX6861RBMfBJFgZy0kGrSnXCdYn8SboOCPEnfxJeFO2il3p1IOuY4PN8a0Rygz7HHoND0nDNMxTUAP3PQLTdsZTBjchOsvLjD3SGnBURqmA136ZwNuuW0WORuHdgcZm8nXfWz1FY7gPxAgzZaEvYXWD7j0H7HYqpm4zp,JG7W0675SM8emSXulreKCoUDrKRQJE6xd7XzQQYtpsE3Oqr0oaHMnfA6aqmSwLadwB4czoQcwW79Am686bW4JXSxCZbW1bOi2DZWYocWe7Cmb5VxadzDbYSib1jraRRxDMwgKZ0GT2YUbq0EtN72TZSFmvw0bPIIRdpSAT0SYcVHJKsJYYNr9yfu4d0iFY2OcIFaF7ZWhi5zsRpOUC3vYEqw9oPPBYje4KYiVLThzbjA1fEmEaM4s7VNFfOncCI4,c909BuipYjtEbFf1mFcQHfbTkKFhNLZY7tW5qYLVtejCuV7f3dVFl9a059WHlLEhLnXoWFjphrq9aD9wrhYIgvjKshoN7dzHuJy6uMZvq0rof45gHJ7PtsfbFOW2ent9ILLmR9kqfnZvZ6Q7tNlUlIFP89KlNAphrqsTaCaXjbsmNoM7fxtiLqQ43UOzqrmY3YY1I5RHDzWfMDSQSoVaPf2cMhMySfnjRrrfJ7WlEGasPPndjjUuphKe4Ok58PMn,nuKWfQ1iKJDzSyXuxjmBgLi6bW7RCiwaCSvGkxX8b4jAzoJA3ar8jLqTimGm7SerQ8xNtiCRmaYulxcrYQQKebRCwvD1VjZpJFBvJ039Kjzq9vOW6LUuJKrQqR3Lm8fRQnk69gZdkqvuCglhBwpvGDPiMQt6BsA2qYJMeGJlavV1hef25CD45WybERl8qrW3ypIU9RbL0djwNMaWPCgs5ysmXZ3wATdvUfuEfhZ6M7VmEBykWNhXJDyYlMKoGe8D,EdDskTlpeJyQgzJe1abXhpA3PJK7JzAjId5MvJRV0II1bCFZ7SnAxBzbLTjp4lVskbEb4D29B4Z79UqMYbO0y5M33jp5MnsAHRtnhKoBdtYEcmYA54KihhXeCuVfkWNNxCg4qYqHlXnh1G5ifwjbi389Pb0vm3TWmbvOoPBaDfWBq2xKvfUjmOmQqz632TJ4FIgHj6AWpSoaKUwn72hJJCR8Rbqi7xTSG8jtTljj34HnBDzyEFYGYXfpf7BzHoYI,jt253kZm0cToLAsKs0qbOa5dI9YJgnSxZ5V2nuWapMoMbeFS5lUjK3WQNd9G7if24fs7LFz3PIccvOaWiu6DEVRvBfk02okK6w8l6wyeZ7TiE9PcpfUeWq05ztUFnRIC0g9T0We9RO4DpcOBI2sEeXqskjr7wo6R9tMjcJi7tI3TZI5rHLKGDy5BMaTSoVuqe5el36Cue7J02UWczfqImk0uAsWKnX1AWiJRNGcDOVvii3Gr4CptCs20ZiP2HLfI,q7mh9asekj1BU2gWjht2Wy6qASyiVKP4PHjnUWOTxT416U1rlIZ07ZPTJ1OH1mIL7trOuB7L7PBVd1HeSLnN3uebQDTzZaVizM7LkYerG2I9botfKz0tnCVonNipSYcPBCPyMxwmQU67vF3eMMuGYdAAnljIv3CHOePh72OCxgos65ZwBIoIENXzSBuEsY9H6hfqxMVnZJu6r2Aq8JZ1aS3f4D9EFwBziQri80cH7BImyv6mspon8h5k9X3VxY3R,E8Mxk2EfSW55h6p89RjEVO1uQkH6HFSKpZNBwu2ius99bICH1H8of2xFjk78mFg1fA7j4tt7o3DfpihqxtKz8vMzGx0umIdmkBhJI76FZTD0Zk3fCaK6YIg4Qvaavs90a4aIrz2lQeLmynvtS2GrWqscVoVYOVtbeVUrd8sZRMkxAQOODqV4LuyCfxpq41PO2fvwbrbWTVIaxEUpXinktN1gSYCjPYGRSmM5TrfKfTEGbrBS91sTyGMEmmMMJIBC,oqKLmbFtHbe5Q49vIXRUlsHCgK5ntKjqWRBz5cX5advZVlOfgaXEWN16GLs2JjfgPZ7vUKiVE9pBHU20xJ9MAQAuFWcJ4oP3Fzi2AtUvpID1aeyFSAJtkUFNzhkuPSphXR8jB7PJjqpLo4A5oyr0o9uhz9V2jr5PCOSJcf0t3gJuFXCPVEu72UMVLkfS0W8hyNqcXXBjqukO9ddfEIDZheNHaSbBm2h59rzDnputWSSXshUfQGSgjOUNofe0Gw37,vdOqPxyllefU1FdnTcapucUHfa3KZ00Mrgp0Tbttt8xA7nXqUkZ9M21lWIqbh7cMEetdBknLme49llVoy25miktP0qrPJtf8WzKvVGDiaYRGXXbBv1siBEmEUdhLP86DGMVNEvQO22MiFQYERdU5Jtv5hw4Ils8RwfdbJKQqFSr5hRNppdI9mRsGQG1ljh34EAUBSwMbZc3QcW5RUw2J79pYKgG7UxlD7qqUJGWvQRnlqR0L7TmvQR4fx1Rf8TQs,WfsMN4kU8Ca9QbkEQScWkkSXXZqQWRVTSntyym3X0X24r3KEpjCNju8Ft3pfqFZMZ7N2deJO2143NumgtmZZBMngYIiGih2QOuvLm6xUIYqKXjT3YSGHdcx61BL3tPBi8qkarxxvyK2xduPVfPRgf5oJO1R3aDYZynfVJWSL0cmg1jaSt49tVGJkITO4d9OqG3d15oVJvTYuBUhXfZWixR6ZMaXRB0EPyG1woWgAIrvKqE5SuOXUjI5yqTitk7tD,M2ttR5HBNm1GHmjFOzohw5zUDCmUa428fBv9yp1k9mXlj1sW1ljd85EwUpgYlIrhCLQPAPOf6maFphtIdQoFdja5ZSofF1Sccz0Ffa9WBVtcdonE40EIjzDGn3EVtvY9XBu5CLJPVEyx3NhIGZLzBXl12DPBmdX08Qvd2DLm96StzFRwH4M5UpEIi8dHg7UeGZDUIoQmH3vdvAyaCAW2EGcoBKFQvCbo288sHUwHBeIlwqRgx3tLfljsFvh3GLxn,i1YNhVDtYM8YqiN8LD1P2f9suqvTcdwRCJJLjuIXhpw5lyaDF3CwerWnglk44wTQwy2YaBfOaPsMzUDj0F0KLbOJ9EikDOPhVBylUI3SeHacWJX0UPrhioLYd4RmgMUZ5IOphq5aOeaPy0295D7MAxlPFUa4m6ZbqlJmWYSYlPEEpNWR0FehzPTJ4RrlQuTbynQLDLdkY2wYFlQPibI0x1lz8G41U9dsPYkFQUMB72neWGjYtIaWcYONdAcHpYHQ,oIHHq9uqIoxwaUUd0J54KLlIVtAb6aKEkeQNzbYpvtRMTAqC1lG7H23Dpq08LI4bJTCVLjvMha2KziH4bnx3uUFGkjiUGAqYyEBCMf571YjP6HAZfKnf3pU9N092HRtruqVDDsYnftE9ZKv64ChygnkbhTwBIaCi1mvzoECHKvq0SC7x1euxlwJWuEM3xb5cDFjD3meA3zzPi8wsK2nRRB0DPSo3KXgTv4ud5SL4DjgeGrD2QuTUAVZvWlGY1odi,9G2i8kSMLc7AQdn2lD3PlQHzOp8LoaKwosQhaAupWO8mv2qWYBW3jtrGyZHxAmZ6xjxSJ6pUVffj5mTGorCD3hDgSfoWLtqxqSc8yyWnNmq7ItiTPRbe4aGlQ7pgFXKSqvGQKFlE4EjogKjFbjVYmDfJJK5qi4ok3ZCqzzcdPYM73P3hnFxw8jE7eU15NMNoWIYVL6uGHfp2ePSvT3smmZEY5SEfqTcQdyauSvt7Fp5XFtGNu1jfAJXfmHCuKPeY,oRjFh41pGzPSsZSKhcBEtiZf662wAKE6PJfSQaxGixA2zoRN5g9gfEadkOhgCafWG9m21J80W6EiGroi5GnH7eiP9oqwpDAezzItvyTftqU9s0GNwRHP7X06KvF9PbaFd2RVq6vxtDHiRG1wC7w7dCzcfAGb52RZQ02FA8ZbhOgQkYmnH43503gwIZLQP87Uf78htZ6JTjq8U06s7yL5Y94fczBg05lI3P2KxkZ9bS4SZPAHpKjgi3LM1Zb0kAQO,If00NH6EqkHzamGgTNuE8AhR6VkgJbEAldUfXMxmripcm09CsUyUSayLzfVSkJFE91hgs9cTCYSOHf22ZIeJWjph1jcObzavRRiNiavFcKOEyGVTqK0cjyHwCsNt0LmqxCFlW7rfUWoyUYznfbVQQOg0VNqiQ5C2xvFKqUsnSbLi68gm2DVBgBS836Q1HP8DvOIEgcLCsZ0SpoQUhOeOLsFd6NFnVHEifjChCQ9jWa8q1vBFlt7uEC1NK9v3XsV5,5bthPA0bXm21z2YF93um8Cu3mcR8XkXBUDLqjsSIvYsw4m8AbUGWbbCTVBe3rtu7jeW7WcjQXNAtJCdbzKeut7I2SSNmEqU1qj860GPqaxFKlXUKGp8bJj6Hk9BHpQOgG4gBcOZ6OwX2gMfYD2XHs3bjYXKPkrFBsKLah3W9Q33OccN7GBnDdWgwhg5a8A28gqIocigIMfpKpNCdmdPAS3aHx8i45TxaLrWyrEsfw5JjfKfJUpmDWQpXtainqrxB,P3zYxSchOmWjqb42EPTdhEmlBDEOm1j9XCct46HB3j18axpqeqaOa37QxlXOOVeVd2p3VNwqqtvB0Jx8PyF7KRd6Qs9gVuYd3kjhiwXJVpRLytgAHS2NKhAE7pMqXJgq8ZnQhwGpx2GtTzyH3Z628DTFoYljKyiilAkTvonUvveG0cWdOGSwj3KQTII39y0GmQuLwax2RFzBORhc0WWXDU25jXhPFwGBUQTk32xvmVhWiKVv20c6DJ8n9NMMf50K,F5nSSPAKFOrt6EAebxmlz6S4NpWccOP7tTAtmGxpVo9qL2ePxxjyKzYEFtShTyNsE8fAXh7el1TokXUvKMktypWNAoAIxvWy2ECy9nB8h8lUNqUVvGD6emx8SHkj4CubbvAJ7JbtpDr1tb792WfFlrcyG90AUo8XJk2zgKbjv0RyTqnvu3BcfrrENHuYiJt3SeBZXX9aRi2FjdA5VpF6bS8Jm3wbHfRDsKBqKVcMXQB8pqApGT6qk41p3202YZsM,LnbuLa52mWadbAsG5aEeFBWZOMcoUXj1OT66X0JaXhly6RGR8mp5FgWq9Bchnga03CURe8FcB2OLyF5JhXYtDJEcJ1o5yFKJrSMQurRg1XqewU2aM4A9kA52vCh3UEtZAdh8QLyfut7nbZd6Pe4e1wSDkMR4EGOJSed0gridEfttcjwdcPrNB4E0ovtSeyc9tmUbS8Iv9wd3xhYb18QJjq8tLWTlfDYLmOrNyyq1qljqRraPr5zcy6h8VHCgQfBs,fvykW1jwmwUD9j67J1fFAFXOMRzyl2ONqEKawIYXVGvL0GajQKGY81a9mSNZGDmyqdQ1oXlCeogntbMXLfFlscleBLkw8715B7eOrdXeFzXbIN6cX7hgovYvO2y3tFYTrw1UYEu66xtOolhG9pwVv34G0X8yPEhovd7VkmKrPYRoJIV3HG6QZtRNNAQROmuwDZ8z3JrjWdm1Dx77VFJz7lXHFXVeLGnKYfPGJkDPVuIzBpJpZymXDT55w58cYTRY,rZVjxbDD4kV20zmeZjxQFPQ85mHEzog2txYXxPxxmwcQNpFmrN1g6sEEhfkQOwv8tsV8Nnik6VPaJE'
2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-12 13:20:37 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9281573B-540C-4F9A-8AE1-6069B66045B0
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57295
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,# setup
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] Session.session(_:peer:didChange:) peer:B646DE46-5115-43A5-B62B-416AA42BB8DC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:B646DE46-5115-43A5-B62B-416AA42BB8DC
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DAF61D32-2625-4ABE-A86E-D81B122EE73E
[ThaliCore] Browser.startListening
2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:20:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start ,listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:902E86C7-8216-4B59-A5AE-F71A1F917,619
2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true,}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisin,gStateUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
2017-07-12 13:20:40 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}]'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:20:40 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:902E86C7-8216-4B59-A5AE-F71A1F917619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "902E86C7-8216-4B59-A5AE-F71A1F917619", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C25CD1F9-CA63-4B0C-9A5A-335781DF371B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
2017-07-12 13:20:40 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}]'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}'
2017-07-12 13:20:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 ,13:20:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E67721D4-C9B6-4546-AAF9-C53C53C1EA3F
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "40B0E517-0610-4DA7-8150-B1B65184FAA3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:40B0E517-0610-4DA7-8150-B1B65184FAA3
ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
ok 141 Can call startListeningForAdvertisements without error
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
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
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
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
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
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:da7c30fd-b097-4958-8a06-046cc3ffb990 error: startListeningNotActive
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValu,e":"IgrzgtZKezWh9M15l6IYtFrXjLJVxMSL","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 157 Should only get called after multiConnect returned
ok 158 SyncValue matches
ok 159 Got right error
ok 160 listeningPort is null
20,17-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"da7c30fd-b097-4958-8a06-046cc3ffb990","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:48 - DEBUG thaliMobileN,ativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"da7c30fd-b097-4958-8a06-046cc3ffb990,",,"peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 162 Should be able to call stopAdvertisingAndListening in tea,rdown
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F928208B-B344-4D86-B12D-6505255584FC
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on starting
ok 164 Got null as expected
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5AbI5N52qpU3Fpt4vdYJUudUAfAVDyrr","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
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
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:578B6B86-50F5-4E10-881C-743FB98CCE17
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 No error on starting
,ok 172 Got null as expected
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UNdo7yPXQLmuAqRtM8fZ4rfSUkL5VaiA","error":"Peer is unavailable","portNumber":null}'
,ok 173 Should only get called after multiConnect returned
,ok 174 SyncValue matches
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C25CD1F9-CA63-4B0C-9A5A-335781DF371B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
not ok 175 Got right error
 , ---
    operator: equal
    expected: 'Connection could not be established'
    actual:   'Peer is unavailable'
,  ...
ok 176 listeningPort is null
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"09e8c14c-ba3d-416a-8659-e44b4818141d","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"09e8c14c-ba3d-416a-8659-e44b4818141d","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
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
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
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
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'Coordina,tedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/F2EF0A7E-3559,-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:5,67:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settleProm,ises@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-07-12 13:20:48 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios,''
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
,# teardown
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}]'
2017-07-12 13:20:48 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:49 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
2017-07-12 13:21:00 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}]'
2017-07-12 13:21:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE","generation":0}'
2017-07-12 13:21:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C25CD1F9-CA63-4B0C-9A5A-335781DF371B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
2017-07-12 13:21:05 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}]'
2017-07-12 13:21:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C25CD1F9-CA63-4B0C-9A5A-335781DF371B","generation":0}'
2017-07-12 13:21:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:24:02 - DEBUG CoordinatedClient: 'test client disconnected'
,2017-07-12 13:24:02 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-12 13:24:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: ',[{"uuid":"3e2a27fd-55aa-45fe-9813-64f7b6e4a161"},{"uuid":"71182d4e-e0a7-4da3-bc25-0736825c855f"},{"uuid":"f57f1c14-6a15-4d78-99d7-2450f7d50b44"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/,c,ontainers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www,/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/F2EF0A7E-3559-4E65-B58D-B1C8D6C73DC5/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
,2017-07-12 13:24:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
