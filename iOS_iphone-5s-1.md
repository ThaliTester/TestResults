#### Test 113351851b6d8223_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/5AE5980C-FE74-40BE-BC3A-D59AE1A3A373/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5AE5980C-FE74-40BE-BC3A-D59AE1A3A373/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851b6d8223/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64106"
,(lldb)     command script import "/tmp/5AE5980C-FE74-40BE-BC3A-D59AE1A3A373/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:19:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A3DB9DAB-CAD8-4E31-A4A7-E1FC5EE12210", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A3DB9DAB-CAD8-4E31-A4A7-E1FC5EE12210
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F63A790-3A06-487C-AA6A-C599D838F402
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:145EAC30-,618B-45B4-BD59-C2B5972DE151
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00E28642-4D06-466D-8CBF-8C1F31046286", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:00E28642-4D06-466D-8CBF-8C1F31046286
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:00E28642-4D06-466D-8CBF-8C1F31046286:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "00E28642-4D06-466D-8CBF-8C1F31046286", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 15:19:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.525708913803101
,2017-07-21 15:19:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-21 15:19:07 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:00E28642-4D06-466D-8CBF-8C1F31046286:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "00E28642-4D06-466D-8CBF-8C1F31046286", generation: 0)
,2017-07-21 15:19:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 15:19:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 15:19:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 15:19:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 15:19:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 15:19:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 15:19:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 15:19:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 15:19:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 15:19:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 15:19:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 15:19:15 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 15:19:15 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 15:19:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:19:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:19:57 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-21 15:19:57 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 15:20:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-21 15:20:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 15:20:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 15:20:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 15:20:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 15:20:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
,ok 14 should be equal
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
,# teardown
,# setup
,# enqueueAtTop and run backwards
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
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
,# teardown
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
,2017-07-21 15:20:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 15:20:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 15:20:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
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
ok 52 test participant has uuid
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
,2017-07-21 15:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 15:20:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D6BEBE56-FD2F-4A8A-8E3E-0764A548BA3C
,[ThaliCore] Browser.startListening
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:14F66564-B28D-424E-83C2-2DE213BB5C2B
[ThaliCore] Browser.startListening
2017-07-21 15:20:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:20:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 15:20:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:20:20 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20,:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:21 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9EB0ADCD-5C1C-48FF-94C1-515111537FA0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9EB0ADCD-5C1C-48FF-94C1-515111537FA0
2017-07-21 1,5:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9EB0ADCD-5C1C-48FF-94C1-515111537FA0
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "946698C0-05D1-43C8-BBD6-CC3169A74DA5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:946698C0-05D1-43C8-BBD6-CC3169A74DA5
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "946698C0-05D1-43C8-BBD6-CC3169A74DA5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:946698C0-05D1-43C8-BBD6-CC3169A74DA5
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:946698C0-05D1-43C8-BBD6-CC3169A74DA5
,[ThaliCore] Advertiser.stopAdvertising() peerID:946698C0-05D1-43C8-BBD6-CC3169A74DA5
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA891C12-4A6E-406B-B453-87C1D248744E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EA891C12-4A6E-406B-B453-87C1D248744E
2017-07-21 1,5:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7B478F3D-83BC-4EFC-BC93-A1B8AF8A7FB9
[Thali,Core] Browser.startListening
,2017-07-21 15:20:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:20:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:20:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:450B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EA891C12-4A6E-406B-B453-87C1D248744E
2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4A9A96FA-DF92-4FD6-A890-D3B343A025FF
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CB938ECC-7A3D-4E9B-A59E-2F356C41B0FC
[ThaliCore] Browser.startListening
,2017-07-21 15:20:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:20:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 15:20:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:450B323B-3155-4965-9439-201530AEAD9C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
2017-07-21 15:20:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"450B323B-3155-4965-9439-201530AEAD9C","generation":0}'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 450B323B-3155-4965-9439-201530AEAD9C (syncValue: fqDNKiu0KOG1bp82wA5uAGXrWPj4VoO5)'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:450B323B-3155-4965-9439-201530AEAD9C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"78039CB6-B812-4699-8F37-95A7049BD39D","generation":0}'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"914F9D5F-A356-430C-B7C2-D99D373FEB10","generation":0}'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4A9A96FA-DF92-4FD6-A890-D3B343A025FF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:313CB512-0B3D-465C-A046-81F763271AF6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "313CB512-0B3D-465C-A046-81F763271AF6", generation: 0)
2017-07-21 15:20:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"313CB512-0B3D-465C-A046-81F763271AF6","generation":0}'
2017-07-21 15:20:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:28 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:20:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:20:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACA58259-1F4E-446E-A0C1-99856C64C279
[ThaliCore] Advertiser: session connected Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ACA58259-1F4E-446E-A0C1-99856C64C279 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:450B323B-3155-4965-9439-201530AEAD9C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,0B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,50B323B-3155-4965-9439-201530AEAD9C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:450B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:450B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACA58259-1F4E-446E-A0C1-99856C64C279
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA58259-1F4E-446E-A0C1-99856C64C279 state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:78039CB6-B812-4699-8F37-95A7049BD39D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "78039CB6-B812-4699-8F37-95A7049BD39D", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:450B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:450B323B-3155-4965-9439-201530AEAD9C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:45,0B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,50B323B-3155-4965-9439-201530AEAD9C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "450B323B-3155-4965-9439-201530AEAD9C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:20:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fqDNKiu0KOG1bp82wA5uAGXrWPj4VoO5","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:20:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fqDNKiu0KOG1bp82wA5uAGXrWPj4VoO5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 15:20:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"450B323B-3155-4965-9439-201530AEAD9C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:20:32 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:20:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"450B323B-3155-4965-9439-201530AEAD9,C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 15:20:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:20:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 914F9D5F-A356-430C-B7C2-D99D373FEB10 (syncValue: CPJDMkGBjYealAVmhWHi8TG,wKHneFWUr)'
,2017-07-21 15:20:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91,4F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:20:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:450B323B-3155-4965-9439-201530AEAD9C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7
[ThaliCore] Advertiser: session connected Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58609
,2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CPJDMkGBjYealAVmhWHi8TGwKHneFWUr","error":null,"portNumber":58609}'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ED5C3DD4-,01CD-4CFB-886D-EEF305048DB7
2017-07-21 15:20:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CPJDMkGBjYealAVmhWHi8TGwKHneFWUr', error: 'null', listeningPort: '58609''
,2017-07-21 15:20:35 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
[ThaliCore] Session.session(_:peer:didChange:) peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7 state: connecting -> connected
,# teardown
,2017-07-21 15:20:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,15:20:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 15:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4A9A96FA-DF92-4FD6-A890-D,3B343A025FF
2017-07-21 15:20:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:20:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:914F9D5F-A356-430C-B7C2-D99D373FEB10
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58609
[ThaliCore] Session.disconnect() p,eer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7 state,: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPCl,ient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACA58259-1F4E-446E-A0C1-99856C64C279 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4A9A96FA-DF92-4FD6-A890-D3B343A025FF", generation: 0)
,[ThaliCore] Session.deinit peer:ED5C3DD4-01CD-4CFB-886D-EEF305048DB7
[ThaliCore] Session.deinit peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:20:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B33DB10A-70F9-4008-843D-2783D939A459
2017-07-21 1,5:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F2525017-CC9B-47B9-8EF4-3BA6E4C985E9
[ThaliCore] Browser.startListening
2017-07-21 15:20:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 15:20:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
2017-07-21 15:20:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"914F9D5F-A356-430C-B7C2-D99D373FEB10","generation":0}'
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 914F9D5F-A356-430C-B7C2-D99D373FEB10, (syncValue: pRvq68y7011PXTB3n3KXX3yakaIhOlrD)'
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373,FEB10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
2017-07-21 15:20:37 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"54198955-F3AC-47C4-8811-A0C5C9298506","generation":0}'
2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E3634E9-CC73-4960-AE64-6DEBFA30E0E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E3634E9-CC73-4960-AE64-6DEBFA30E0E8", generation: 0)
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E3634E9-CC73-4960-AE64-6DEBFA30E0E8","generation":0}'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B33DB10A-70F9-4008-843D-2783D939A459:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B33DB10A-70F9-4008-843D-2783D939A459", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,4F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,14F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,4F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,14F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,4F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,14F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,4F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "914F9D5F-A356-430C-B7C2-D99D373FEB10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:914F9D5F,-A356-430C-B7C2-D99D373FEB10 error: max retries exceeded
2017-07-21 15:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pRvq68y7011PXTB3n3KXX3yakaIhOlrD","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 15:20:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pRvq68y7011PXTB3n3KXX3yakaIhOlrD', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 15:20:48 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"914F9D5F-A356-430C-B7C2-D99D373FEB10","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"914F9D5F-A356-430C-B7C2-D99D373FEB10","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 54198955-F3AC-47C4-8811-A0C5C9298506 (syncValue: RFCVCGenaKkI4MlP7NGyJx8wGKvSgsj1)'
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:914F9D5F-A356-430C-B7C2-D99D373FEB10:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58624
,2017-07-21 15:20:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RFCVCGenaKkI4MlP7NGyJx8wGKvSgsj1","error":null,"portNumber":58624}'
,2017-07-21 15:20:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RFCVCGenaKkI4MlP7NGyJx8wGKvSgsj1', error: 'null', listeningPort: '58624''
,Connecting to the localhost:58624
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,Connected to the localhost:58624
,2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 15:20:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,# teardown
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-07-21 15:20:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B33DB10A-70F9-4008-843D-2783D939A459
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:54198955-F3AC-47C4-8811-A0C5C9298506
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58624
[ThaliCore] Session.disconnect() peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:417E5300-4185-4168-9885-6C92102C4586
2017-07-21 1,5:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:142AB96B-FD73-4D79-990B-FD7020BC717C
[Thali,Core] Browser.startListening
2017-07-21 15:20:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:20:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:20:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
2017-07-21 15:20:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"54198955-F3AC-47C4-8811-A0C5C9298506","generation":0}'
2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 54198955-F3AC-47C4-8811-A0C5C9298506, (syncValue: gkmTVONuEL0lRm9Dk523TshicJtvX2In)'
2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C92,98506", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"28724137-54ED-42D2-A1D6-A3FD843CA3AF","generation":0}'
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:417E5300-4185-4168-9885-6C92102C4586:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
2017-07-21 15:20:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF6C166-AB5C-4B74-943D-F876A11F6ADE","generation":0}'
2017-07-21 15:20:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:20:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,4198955-F3AC-47C4-8811-A0C5C9298506", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
[ThaliCore] Advertiser: session connected Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:54198955-F3AC-47C4-8811-A0C5C9298506:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:54,198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,4198955-F3AC-47C4-8811-A0C5C9298506", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "54198955-F3AC-47C4-8811-A0C5C9298506", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gkmTVONuEL0lRm9Dk523TshicJtvX2In","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gkmTVONuEL0lRm9Dk523TshicJtvX2In', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"54198955-F3AC-47C4-8811-A0C5C9298506","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"54198955-F3AC-47C4-8811-A0C5C9298506","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:20:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 28724137-54ED-42D2-A1D6-A3FD843CA3AF (syncValue: IrYDpWnSmYFgXR0dOZkzDGT,6ea5psPSF)'
2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:28724137-54ED-42D2-A1D6-A3FD8,43CA3AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:20:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:54198955-F3AC-47C4-8811-A0C5C9298506:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] Session.session(_:peer:didChange:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
[ThaliCore] Session.startOutputStream(with:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
[ThaliCore] Session.startOutputStream(with:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
[ThaliCore] Session.startOutputStream(with:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (6144 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (11690 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received (3670 bytes):'
,2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:20:59 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received (101 bytes):'
,2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 15:21:00 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58639
,2017-07-21 15:21:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IrYDpWnSmYFgXR0dOZkzDGT6ea5psPSF","error":null,"portNumber":58639}'
,2017-07-21 15:21:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IrYDpWnSmYFgXR0dOZkzDGT6ea5psPSF', error: 'null', listeningPort: '58639''
,Connecting to the localhost:58639
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,Connecting to the localhost:58639
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
Connecting to the localhost:58639
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,Connected to the localhost:58639
,Connected to the localhost:58639
,Connected to the localhost:58639
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] Session.startOutputStream(with:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [2, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
,[ThaliCore] Session.startOutputStream(with:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] Session.startOutputStream(with:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [2, 5, 6, 7, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 91 correct string length
,2017-07-21 15:21:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [2, 6, 7, 8, 9, 10]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [2, 7, 8, 9, 10]
,ok 94 got the same data back
,ok 95 got the same data back
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 7, 9, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server received all data: 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[,ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 7, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSo,cketDisconnectHandler disconnecting:false
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'
2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 15:21:02 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [2, 10]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
ok 96 got the same data back
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
,2017-07-21 15:21:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:02 - DEBUG thaliMobileNa,tiveWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:417E5300-4185-4168-9885-6C92102C4586
2017-07-2,1 15:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58639
[ThaliCore] Session.disconnect() p,eer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C6630F2-B885-40E2-A493-AF39994A8CAF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "417E5300-4185-4168-9885-6C92102C4586", generation: 0)
,[ThaliCore] Session.deinit peer:E7915C5B-FB68-47C0-8A7E-DB3904E76E6D
[ThaliCore] Session.deinit peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 15:21:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:71D06222-295C-4BB8-8A3B-D1FE634FD4DE
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5F7F6312-693C-4E2D-AED4-A1EF1137760B
[ThaliCore] Browser.startListening
,2017-07-21 15:21:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
2017-07-21 15:21:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4FF6C166-AB5C-4B74-943D-F876A11F6ADE","generation":0}'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4FF6C166-AB5C-4B74-943D-F876A11F6ADE, (syncValue: cLtluADHrEPrJDwPup8bvrblpDrVKHEh)'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11,F6ADE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"28724137-54ED-42D2-A1D6-A3FD843CA3AF","generation":0}'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
2017-07-21 15:21:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","generation":0}'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:04 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4BDDD64-4029-4E6B-BE78-E9D242224BD4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4BDDD64-4029-4E6B-BE78-E9D242224BD4", generation: 0)
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4BDDD64-4029-4E6B-BE78-E9D242224BD4","generation":0}'
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D06222-295C-4BB8-8A3B-D1FE634FD4DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,F6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,F6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935
[ThaliCore] Advertiser: session connected Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:28724137-54ED-42D2-A1D6-A3FD843CA3AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "28724137-54ED-42D2-A1D6-A3FD843CA3AF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,F6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935
,[ThaliCore] Session.session(_:peer:didChange:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935
[ThaliCore] Session.startOutputStream(with:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [2, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 15:21:13 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 15:21:13 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 15:21:13 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 15:21:13 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 15:21:13 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [2]
,[ThaliCore] Session.session(_:peer:didChange:) peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4F,F6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4FF6C166-AB5C-4B74-943D-F876A11F6ADE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4FF6C166,-AB5C-4B74-943D-F876A11F6ADE error: max retries exceeded
2017-07-21 15:21:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cLtluADHrEPrJDwPup8bvrblpDrVKHEh","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 15:21:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cLtluADHrEPrJDwPup8bvrblpDrVKHEh', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 15:21:15 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"4FF6C166-AB5C-4B74-943D-F876A11F6ADE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 15:21:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4FF6C166-AB5C-4B74-943D-F876A11F6ADE","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 15:21:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 15:21:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 80E413B1-FE3A-450A-9B20-73B6C55150CC (syncValue: lw8y3AW4Nz5U1eXtEi9Sl31IDVT15VKl)'
,2017-07-21 15:21:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4FF6C166-AB5C-4B74-943D-F876A11F6ADE:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:21:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58653
2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lw8y3AW4Nz5U1eXtEi9Sl31IDVT15VKl",,"error":null,"portNumber":58653}'
2017-07-21 15:21:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lw8y3AW4Nz5U1eXtEi9Sl31IDVT15VKl', error: 'null', listeningPort: '58653''
,Connecting to the localhost:58653
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:58653
,2017-07-21 15:21:18 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 15:21:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-21 15:21:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:71D06222-295C-4BB8-8A3B-D1FE634FD4DE
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:80E413B1-FE3A-450A-9B20-73B6C55150CC
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58653
[ThaliCore] Session.disconnect() peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:030D3DE9-5210-4895-ADF4-AABB31F02935 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "71D06222-295C-4BB8-8A3B-D1FE634FD4DE", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:030D3DE9-5210-4895-ADF4-AABB31F02935
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:030D3DE9-5210-4895-ADF4-AABB31F02935
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2
,2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D06043C6-7706-4FCE-804D-0BCDE3AF37F0
[ThaliCore] Browser.startList,ening
2017-07-21 15:21:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
2017-07-21 15:21:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","generation":0}'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 80E413B1-FE3A-450A-9B20-73B6C55150CC, (syncValue: mza15q1Vt0yjAO3TUbjWMbdLxT9W7pPI)'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55,150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInf,o:) found peer:B4BDDD64-4029-4E6B-BE78-E9D242224BD4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4BDDD64-4029-4E6B-BE78-E9D242224BD4", generation: 0)
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4BDDD64-4029-4E6B-BE78-E9D242224BD4","generation":0}'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","generation":0}'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B4BDDD64-4029-4E6B-BE78-E9D242224BD4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B4BDDD64-4029-4E6B-BE78-E9D242224BD4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,0E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:80,E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:80E413B1,-FE3A-450A-9B20-73B6C55150CC error: max retries exceeded
2017-07-21 15:21:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mza15q1Vt0yjAO3TUbjWMbdLxT9W7pPI","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 15:21:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mza15q1Vt0yjAO3TUbjWMbdLxT9W7pPI', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 15:21:31 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:21:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 15:21:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"80E413B1-FE3A-450A-9B20-73B6C55150CC","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 15:21:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 15:21:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F6D29EA3-480A-4F67-9CD5-38A122C3C78F (syncValue: d8GWs18,cYvwwTg65LdjCORNDe78XoAdg)'
2017-07-21 15:21:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F6D29EA3-480A,-4F67-9CD5-38A122C3C78F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:21:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:21:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:80E413B1-FE3A-450A-9B20-73B6C55150CC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "80E413B1-FE3A-450A-9B20-73B6C55150CC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58669
2017-07-21 15:21:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"d8GWs18cYvwwTg65LdjCORNDe78XoAdg",,"error":null,"portNumber":58669}'
2017-07-21 15:21:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd8GWs18cYvwwTg65LdjCORNDe78XoAdg', error: 'null', listeningPort: '58669''
,Connecting to the localhost:58669
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
,Connected to the localhost:58669
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 15:21:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,ok 102 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [2, 12]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
[ThaliCore] Advertiser: session connected Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
[ThaliCore] Session.startOutputStream(with:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 12, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (10950 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (16425 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received (6406 bytes):'
,2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 15:21:41 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [2, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 15:21:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:21:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:21:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1D9A3D8B-3C2F-4998-9257-A991FA5C3FB2
,[ThaliCore] Session.disconnect() peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58669
[ThaliCore] Session.disconnect() peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
,2017-07-21 15:21:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"d8GWs18cYvwwTg65LdjCORNDe78XoAdg","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:0CA2A5B4-DBC6-4AEC-852E-B12313338F57
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5622FCD4-D2F5-4C1C-88DF-935DE83B0416
[ThaliCore] Browser.startListening
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:79880EFE-5106-4A10-A98C-DCC560D09CF8
,2017-07-21 15:21:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:21:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4E,B0-8738-6F7DCA10BAAF","generation":0}]'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FAD89D0B-CF43-4EB0-8738-6F7DCA10BAAF","generation":0}'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","generation":0}]'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","generation":0}'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A8356DEC-E68F-4142-8FBA-FE2C3F945A22","generation":0}]'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A8356DEC-E68F-4142-8FBA-FE2C3F945A22","generation":0}'
,2017-07-21 15:21:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:79880EFE-5106-4A10-A98C-DCC560D09CF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "79880EFE-5106-4A10-A98C-DCC560D09CF8", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F6D29EA3-480A-4F67-9CD5-38A122C3C78F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F6D29EA3-480A-4F67-9CD5-38A122C3C78F", generation: 0)
2017-07-21 15:21:46 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","generation":0}]'
2017-07-21 15:21:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F6D29EA3-480A-4F67-9CD5-38A122C3C78F","generation":0}'
2017-07-21 15:21:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,15:21:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:79880EFE-5106-4A10-A98C-D,CC560D09CF8
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 15:21:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05325DAD-D566-4CE5-A4A4-7C25AB33D044
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6D1EA80A-EC53-404D-AA72-34B2C97DE196", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6D1EA80A-EC53-404D-AA72-34B2C97DE196
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6D1EA80A-EC53-404D-AA72-34B2C97DE196
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 15:21:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 15:21:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 15:21:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 15:21:50 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 15:21:50 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 15:21:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 15:21:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 15:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:ff689fe9-de03-4606-8cfb-e47183bb1af3 error: startListeningNotActive
2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"dDXy2qk0AZnMLIotPaHNJ2K7BcO77VDZ","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ff689fe9-de03-4606-8cfb-e47183bb1af3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ff689fe9-de03-4606-8cfb-e47183bb1af3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:315ABFF5-C2AA-4CCE-B909-6D01CB011234
,[ThaliCore] Browser.startListening
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GN3OarBzDMnpCNyzHnbLcUE16xbiJjMy","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 15:21:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:55 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B9279637-B0A1-46D4-A5BF-0E7115FD6ABF
,[ThaliCore] Browser.startListening
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:77d775db-3989-4690-85d9-051baf58828d
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:814704C1-77B8-4718-B0BA-A0A557E53065
2017-07-21 1,5:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:21:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D649905A-9A6F-4D34-AC25-2477836AA3FA
[ThaliCore] Browser.startList,ening
2017-07-21 15:21:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:21:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:21:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
2017-07-21 15:21:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A8356DEC-E68F-4142-8FBA-FE2C3F945A22","generation":0}'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A8356DEC-E68F-4142-8FBA-FE2C3F945A22 (syncValue: uvtb5KCAtRNkKSXo9Bj16URylG6e5dy4)'
,2017-07-21 15:21:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:814704C1-77B8-4718-B0BA-A0A557E53065:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
2017-07-21 15:21:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","generation":0}'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20", generation: 0)
2017-07-21 15:21:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20","generation":0}'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:21:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A8,356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A8,356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A8356DEC-E68F-4142-8FBA-FE2C3F945A22", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:22:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uvtb5KCAtRNkKSXo9Bj16URylG6e5dy4","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:22:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uvtb5KCAtRNkKSXo9Bj16URylG6e5dy4', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:22:01 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"A8356DEC-E68F-4142-8FBA-FE2C3F945A22","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:22:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:22:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A8356DEC-E68F-4142-8FBA-FE2C3F945A22","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 15:22:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:22:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21592C4B-4C4F-4572-B106-48B3883ACB80 (syncValue: CApTknzgPZpr9CKpneD0XOH,6nmdllKdz)'
2017-07-21 15:22:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21592C4B-4C4F-4572-B106-48B38,83ACB80:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:22:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A8356DEC-E68F-4142-8FBA-FE2C3F945A22:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58684
,2017-07-21 15:22:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CApTknzgPZpr9CKpneD0XOH6nmdllKdz","error":null,"portNumber":58684}'
,2017-07-21 15:22:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CApTknzgPZpr9CKpneD0XOH6nmdllKdz', error: 'null', listeningPort: '58684''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 12, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) found active relay
,2017-07-21 15:22:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"644wcvIkjJ2s5CZU6HcHpmf0c1BVluAF","error":null,"portNumber":58684}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) found active relay
,2017-07-21 15:22:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CiTKdHkrwBM8sglI8CJ5KsJvGyjXPhVl","error":null,"portNumber":58684}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D
[ThaliCore] Advertiser: session connected Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
[ThaliCore] Advertiser: session connected Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D
[ThaliCore] Session.startOutputStream(with:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 12, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
,[ThaliCore] Session.startOutputStream(with:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 12, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:22:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:22:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:814704C1-77B8-4718-B0BA-A0A557E53065
2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15,:22:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] BrowserManager.disconnect peer:21592C4B-4C4F-4572-B106-48B3883ACB80
[ThaliCore] Session.session(_:peer:didChange:) peer:C1124706-3E29-4E98-AEEA-6AC836BBE397 state: connected -> notConnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] Advertiser: se,ssion notConnected Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didSo,cketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58684
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocke,t.closeStreams() vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exite,d RunLoop vsID:16
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:16 [2, 12, 15, 17]
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] TCPClient.deinit
[ThaliCore] Session.disconnect() peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.deinit vsID:17 [2, 12, 15]
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [2, 12]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CApTknzgPZpr9CKpneD0XOH6nmdllKdz","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D6782C4-E530-4ED4-8A35-B5018E173E1D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "814704C1-77B8-4718-B0BA-A0A557E53065", generation: 0)
,# initial peer discovery
,2017-07-21 15:22:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:C1124706-3E29-4E98-AEEA-6AC836BBE397
[ThaliCore] Session.deinit peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 15:22:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 15:22:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 15:22:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 15:22:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:14 - DEBUG createNativeListener: 'listening 58689'
,ok 149 Should throw
,# teardown
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'listening 58691'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 15:22:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'listening 58694'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'listening 58698'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'listening 58703'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 15:22:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 15:22:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'listening 58707'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:17 - DEBUG createNativeListener: 'listening 58711'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'listening 58715'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 15:22:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:19 - DEBUG createNativeListener: 'listening 58719'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 15:22:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 15:22:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 15:22:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:20 - DEBUG createNativeListener: 'listening 58771'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 15:22:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'listening 58775'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 15:22:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 15:22:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:21 - DEBUG createNativeListener: 'listening 58778'
,ok 196 port must be in range
,# teardown
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 15:22:22 - DEBUG createNativeListener: 'listening 58779'
ok 197 second start should return same port
,# teardown
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'listening 58781'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 15:22:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 58783
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:22:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:22:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:22:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:390152AE-1CFD-4486-955C-D5418FB4972F
2017-07-21 1,5:22:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:22:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:22:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0AD041BE-FF06-4505-ADBA-DA2D5A02760B
[ThaliCore] Browser.startListening
2017-07-21 15:22:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 15:22:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:22:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
2017-07-21 15:22:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","generation":0}'
,2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21592C4B-4C4F-4572-B106-48B3883ACB80 (syncValue: pYILZhLHKzXYUFQs2i9lKB63VeEM2TkW)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA78C7AA-4E06-4DC5,-A977-A2F4BDFF7B20:0
2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20", generation: 0)
[ThaliCore] BrowserManager.conn,ectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883AC,B80", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20","generation":0}'
2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!',
2017-07-21 15:22:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
2017-07-21 15:22:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","generation":0}'
2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:390152AE-1CFD-4486-955C-D5418FB4972F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40621967-7A54-466D-8CBB-4245C86531C6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40621967-7A54-466D-8CBB-4245C86531C6","generation":0}'
,2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EA78C7AA-4E06-4DC5-A977-A2F4BDFF7B20", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9
[ThaliCore] Advertiser: session connected Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7875D863-3C23-4520-81CA-072A2B82D404
[ThaliCore] Advertiser: session connected Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7875D863-3C23-4520-81CA-072A2B82D404 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "21592C4B-4C4F-4572-B106-48B3883ACB80", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:21592C4B,-4C4F-4572-B106-48B3883ACB80 error: max retries exceeded
2017-07-21 15:22:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pYILZhLHKzXYUFQs2i9lKB63VeEM2TkW","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 15:22:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pYILZhLHKzXYUFQs2i9lKB63VeEM2TkW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 15:22:33 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"21592C4B-4C4F-4572-B106-48B3883ACB80","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 15:22:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 40457155-87AB-4CFC-92D7-0BAAB9373290 (syncValue: Fv38SHrzT0qv0SgDqaGWFTqyNwEv51QZ)'
,2017-07-21 15:22:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:22:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:21592C4B-4C4F-4572-B106-48B3883ACB80:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7875D863-3C23-4520-81CA-072A2B82D404
,[ThaliCore] Session.session(_:peer:didChange:) peer:7875D863-3C23-4520-81CA-072A2B82D404 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58797
,2017-07-21 15:22:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fv38SHrzT0qv0SgDqaGWFTqyNwEv51QZ","error":null,"portNumber":58797}'
,2017-07-21 15:22:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Fv38SHrzT0qv0SgDqaGWFTqyNwEv51QZ', error: 'null', listeningPort: '58797''
,ok 210 should be equal
,2017-07-21 15:22:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 40621967-7A54-466D-8CBB-4245C86531C6 (syncValue: 9yi2Io1hKLo3ONDW1tUKlVIPmyywSm7Q)'
,2017-07-21 15:22:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40621967-7A54-466D-8CBB-4245C86531C6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:22:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:40621967-7A54-466D-8CBB-4245C86531C6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40621967-7A54-466D-8CBB-4245C86531C6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:40621967-7A54-466D-8CBB-4245C86531C6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58800
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9yi2Io1hKLo3ONDW1tUKlVIPmyywSm7Q","error":null,"portNumber":58800}'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9yi2Io1hKLo3ONDW1tUKlVIPmyywSm7Q', error: 'null', listeningPort: '58800''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:22:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:390152AE-1CFD-4486-955C-D5418FB4972F
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:40457155-87AB-4CFC-92D7-0BAAB9373290
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58797
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:40621967-7A54-466D-8CBB-4245C86531C6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58800
,[ThaliCore] Session.disconnect() peer:40621967-7A54-466D-8CBB-4245C86531C6:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7875D863-3C23-4520-81CA-072A2B82D404 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7875D863-3C23-4520-81CA-072A2B82D404
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1E75C3C-DC4C-47DD-AB32-A516A3FEC5A9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "390152AE-1CFD-4486-955C-D5418FB4972F", generation: 0)
,[ThaliCore] Session.deinit peer:40621967-7A54-466D-8CBB-4245C86531C6:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 15:22:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fv38SHrzT0qv0SgDqaGWFTqyNwEv51QZ","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:22:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 58802
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] Session.deinit peer:7875D863-3C23-4520-81CA-072A2B82D404
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:22:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:22:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F61844C-075A-49BC-ACFA-4CF243EFC76D
,2017-07-21 15:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 15:22:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:22:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:13D1E1AC-66F1-4749-BFE1-2D82B6AC3D12
,[ThaliCore] Browser.startListening
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:22:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:22:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:40621967-7A54-466D-8CBB-4245C86531C6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","generation":0}'
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 40457155-87AB-4CFC-92D7-0BAAB9373290 (syncValue: nm6H70PkOKG972XnJUDF9duKQC75r30a)'
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"40621967-7A54-466D-8CBB-4245C86531C6","generation":0}'
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
2017-07-21 15:22:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:43 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F61844C-075A-49BC-ACFA-4CF243EFC76D:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 15:22:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:40621967-7A54-466D-8CBB-4245C86531C6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "40621967-7A54-466D-8CBB-4245C86531C6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:40,457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,0457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "40457155-87AB-4CFC-92D7-0BAAB9373290", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:22:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nm6H70PkOKG972XnJUDF9duKQC75r30a","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:22:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nm6H70PkOKG972XnJUDF9duKQC75r30a', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 15:22:51 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:22:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 15:22:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"40457155-87AB-4CFC-92D7-0BAAB9373290","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 15:22:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:22:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 15:22:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B884C051-2B35-4187-B508-14FE33F8367A (syncValue: MRDqyDulFYHl9o7qP2xQPiK,sGVcNOLjX)'
2017-07-21 15:22:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B884C051-2B35-4187-B508-14FE3,3F8367A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 15:22:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:40457155-87AB-4CFC-92D7-0BAAB9373290:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
[ThaliCore] Advertiser: session connected Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58818
2017-07-21 15:22:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MRDqyDulFYHl9o7qP2xQPiKsGVcNOLjX",,"error":null,"portNumber":58818}'
2017-07-21 15:22:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MRDqyDulFYHl9o7qP2xQPiKsGVcNOLjX', error: 'null', listeningPort: '58818''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-21 15:22:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5FC4BDB3-3269-4B54-85E8-376E58D2C986 (syncValue: O7u1JoE68T6VPWSNQz5k1cXTisreUV6b)'
2017-07-21 15:22:,53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377
[ThaliCore] Advertiser: session connected Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] Session.session(_:peer:,didChange:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58824
2017-07-21 15:22:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O7u1JoE68T6VPWSNQz5k1cXTisreUV6b","error":null,"portNumber":58824}'
,2017-07-21 15:22:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'O7u1JoE68T6VPWSNQz5k1cXTisreUV6b', error: 'null', listeningPort: '58824''
,ok 220 should be equal
ok 221 should be equal
ok 222 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,15:23:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4F61844C-075A-49BC-ACFA-4,CF243EFC76D
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:B884C051-2B35-4187-B508-14FE33F8367A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58818
[ThaliCore] Session.disconnect() p,eer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC0799A4-7E47-446E-BC6F-7D9DFC5701E5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F61844C-075A-49BC-ACFA-4CF243EFC76D", generation: 0)
,[ThaliCore] Session.deinit peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58824
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
,2017-07-21 15:23:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"O7u1JoE68T6VPWSNQz5k1cXTisreUV6b","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 15:23:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,[ThaliCore] Session.deinit peer:7266E187-C51E-4CA9-874C-AF6B3BA7F377
[ThaliCore] Session.deinit peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
[ThaliCore] BrowserRelay.deinit
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 15:23:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'listening 58828'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DD76A9F5-D5B3-4D4C-AE9D-21D07F3DD161
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:02 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:02 - DEBUG makeIntoCloseAllServer: 'closeAll called, on server'
ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'listening 58829'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4FEAF044-9B57-4551-978C-335DB7EA2BCE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4FEAF044-9B57-4551-978C-335DB7EA2BCE
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 231 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4FEAF044-9B57-4551-978C-335DB7EA2BCE", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:4FEAF044-9B57-4551-978C-335DB7EA2BCE
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4FEAF044-9B57-4551-978C-335DB7EA2BCE
,[ThaliCore] Advertiser.stopAdvertising() peerID:4FEAF044-9B57-4551-978C-335DB7EA2BCE
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 233 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'listening 58832'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 234 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActiv,e":false}'
2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 236 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 15:23:04 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 239 specific error expected
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'listening 58833'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D713E024-7074-4A1F-9825-A8E4AA91F03B
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1B99A4AA-FEB6-4337-9EE7-1F7098D91A03", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1B99A4AA-FEB6-4337-9EE7-1F7098D91A03
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,ok 241 all connection succeed
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}]'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1B99A4AA-FEB6-4337-9EE7-1F7098D91A03
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'listening 58836'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05A2CAE7-CE43-4F56-BA06-22FDA63D2134
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7864CBFC-44ED-4B24-849B-E24F345D6EF0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7864CBFC-44ED-4B24-849B-E24F345D6EF0
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7864CBFC-44ED-4B24-849B-E24F345D6EF0
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'listening 58838'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5A243FEE-D650-46E1-8C10-0E45D8C8ADE1
[ThaliCore] Browser.st,artListening
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C4C537E1-3D94-4A2B-96F5-CBB78436A78A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C4C537E1-3D94-4A2B-96F5-CBB78436A78A
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C4C537E1-3D94-4A2B-96F5-CBB78436A78A
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 15:23:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 15:23:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 15:23:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 15:23:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 15:23:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 15:23:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 15:23:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 58841'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CABF4521-62DD-4004-B624-DD97C7F39A88
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 266 discoveryActive matches
,ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 58842'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3094E816-21B8-43EA-B6D1-69F0ECBC4773", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3094E816-21B8-43EA-B6D1-69F0ECBC4773
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3094E816-21B8-43EA-B6D1-69F0ECBC4773
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 58844'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'listening 58845'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C7A966BA-0C5A-4D2B-A36D-71F88E2C5E64
[ThaliCore] Browser.st,artListening
2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA8A7B76-B267-42CD-A158-6F7EABA79077", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA8A7B76-B267-42CD-A158-6F7EABA79077
,2017-07-21 15:23:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 15:23:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B5,08-14FE33F8367A","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}]'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 275 portNumber equal null
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:320DCC94-FF97-4760-9C97-FD4AA1A8CD8E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "320DCC94-FF97-4760-9C97-FD4AA1A8CD8E", generation: 0)
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","generation":0}]'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","generation":0}'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA8A7B76-B267-42CD-A158-6F7EABA79077:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA8A7B76-B267-42CD-A158-6F7EABA79077", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EA8A7B76-B267-42CD-A158-6F7EABA79077
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 15:23:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 15:23:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 15:23:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:13 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 15:23:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 15:23:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'listening 58847'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:497660BB-B929-4100-87D1-04BE739F5BFB
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:186D2D79-0D19-4D5A-BBBA-6C8566980B6E
2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 15:23:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
2017-07-21 15:23:14 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}]'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B884C051-2B35-4187-B508-14FE33F8367A (syncValue: uvY4pOEu5kM8GIOwAhB9rnV0Dc4tGcgg)'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
2017-07-21 15:23:15 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:AB581EA5-29D9-4172-88A7-F007CDB0BF6E:0
2017-07-21 15:23:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"po,rtNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AB581EA5-29D9-4172-88A7-F007CDB0BF6E", generation: 0)
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","generation":0}]'
2017-07-21 15:23:15 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","generation":0}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:186D2D79-0D19-4D5A-BBBA-6C8566980B6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,84C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B884C051-2B35-4187-B508-14FE33F8367A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:5FC4BDB3-3269-4B54-85E8-376E58D2C986:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5FC4BDB3-3269-4B54-85E8-376E58D2C986", generation: 0)
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","generation":0}]'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B88,4C051-2B35-4187-B508-14FE33F8367A","generation":0}'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation,":0}]'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","generation":0}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 15:23:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 15:23:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5FC4BDB3-3269-4B54-85E8-376E58D2C986","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B884C051-2B35-4187-B508-14FE33F8367A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B8,84C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,884C051-2B35-4187-B508-14FE33F8367A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B884C051-2B35-4187-B508-14FE33F8367A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uvY4pOEu5kM8GIOwAhB9rnV0Dc4tGcgg","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uvY4pOEu5kM8GIOwAhB9rnV0Dc4tGcgg', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B884C051-2B35-4187-B508-14FE33F8367A","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:B884C051-2B35-4187-B508-14FE33F8367A
,2017-07-21 15:23:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C453656-3299-4A28-98BE-D7BAD2ED7E26 (syncValue: LunmrfdMe0Y6TMnNIGoO66VFsW2G2tUY)'
,2017-07-21 15:23:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B884C051-2B35-4187-B508-14FE33F8367A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4
[ThaliCore] Advertiser: session connected Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4 state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4
[ThaliCore] Session.startOutput,Stream(with:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 12, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0,
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58856
,2017-07-21 15:23:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LunmrfdMe0Y6TMnNIGoO66VFsW2G2tUY","error":null,"portNumber":58856}'
,2017-07-21 15:23:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LunmrfdMe0Y6TMnNIGoO66VFsW2G2tUY', error: 'null', listeningPort: '58856''
,2017-07-21 15:23:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 12, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:23:23 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:23:23 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
,ok 282 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D
[ThaliCore] Advertiser: session connected Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D
,[ThaliCore] Session.session(_:peer:didChange:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D
,[ThaliCore] Session.startOutputStream(with:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 12, 18, 19, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:186D2D79-0D19-4D5A-BBBA-6C8566980B6E
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 15:23:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [2, 12, 18, 20]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:20 [2, 12, 18]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:36823153-08F8-4C02-94E8-2C89D2C5349D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:36823153-08F8-4C02-94E8-2C89D2C5349D
,2017-07-21 15:23:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [2, 12]
,ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58856
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LunmrfdMe0Y6TMnNIGoO66VFsW2G2tUY","error":"Session disconnected","portNumber":null}'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier,":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AC8F16C-04DD-440E-9786-F1E296C3BFF4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "186D2D79-0D19-4D5A-BBBA-6C8566980B6E", generation: 0)
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 15:23:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 15:23:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.deinit peer:36823153-08F8-4C02-94E8-2C89D2C5349D
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 15:23:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 15:23:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 15:23:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-21 15:23:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"320DCC94-FF97-4760-9C97-FD4AA1A8CD8E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 15:23:30 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"AB581EA5-29D9-4172-88A7-F007CDB0BF6E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
,ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'listening 58859'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
,ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'listening 58860'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A2F608E-EF6A-4422-828B-C29EF27E3D98
[ThaliCore] Browser.st,artListening
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 304 error should be null
ok 305 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 306 error should be null
,ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-21 15:23:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'listening 58861'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52E11D1B-742E-46BE-829A-E390E2D1C214", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:52E11D1B-742E-46BE-829A-E390E2D1C214
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52E11D1B-742E-46BE-829A-E390E2D1C214", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:52E11D1B-742E-46BE-829A-E390E2D1C214
,2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 313 error should be null
,ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:52E11D1B-742E-46BE-829A-E390E2D1C214
[ThaliCore] Advertiser.stopAdvertising() peerID:52E11D1B-742E-46BE-829A-E390E2D1C214
2017-07-21 15:23:32 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-21 15:23:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-21 15:23:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'listening 58864'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:23:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
,ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 15:23:33 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
,ok 326 native router should be bad
,# teardown
,ok 327 error should be null
,ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'listening 58865'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 15:23:33 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 15:23:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 15:23:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8ec9a1f-71d3-40cd-9dea-df97331fd3bc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 342 should be called once
,ok 343 should not have been called more than once
,# teardown
,2017-07-21 15:23:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f8ec9a1f-71d3-40cd-9dea-df97331fd3bc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
,ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fc7ccfc-ea01-4d19-9209-a93e4533ac3f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 352 peer should be available
,ok 353 cache contains native peer
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fc7ccfc-ea01-4d19-9209-a93e4533ac3f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 354 peer should be unavailable
,ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
,ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e025b0e9-0007-4030-83ba-20578e070b5e","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 360 peer should be available
ok 361 cache contains wifi peer
2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e025b0e9-0007-4030-83ba-20578e070b5e","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 362 peer should be unavailable
,ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
,ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a38b8737-72b2-40b5-8c6f-31d8df44a0ce","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5d52452c-407d-4f21-aafb-b6b520ac4311","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 368 second peer is available
,ok 369 first and second peers are different
,# teardown
,2017-07-21 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a38b8737-72b2-40b5-8c6f-31d8df44a0ce","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5d52452c-407d-4f21-aafb-b6b520ac4311","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
,2017-07-21 15:23:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bfa97610-4b21-4a96-9f20-0ef3d6a2a4ad","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 peer is available
,# teardown
,2017-07-21 15:23:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bfa97610-4b21-4a96-9f20-0ef3d6a2a4ad","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 15:23:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
,ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 15:23:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2dfae40f-30f5-4bbf-844f-b215f38c217c","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 384 peer should be ,available
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2dfae40f-30f5-4bbf-844f-b215f38c217c","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2dfae40f-30f5-4bbf-844f-b215f38c217c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'listening 58866'
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"53990ebb-e6d1-48f1-9956-d12258aff989","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 discovered correct peer
,ok 391 got correct generation
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"53990ebb-e6d1-48f1-9956-d12258aff989","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,# teardown
,2017-07-21 15:23:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"53990ebb-e6d1-48f1-9956-d12258aff989","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'listening 58867'
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1141cb39-1bda-498b-b603-d67aafc3c0e9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 397 discovered available peer
,ok 398 peer is available
,# teardown
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1141cb39-1bda-498b-b603-d67aafc3c0e9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"df55f51c-2249-4301-9152-336ff26c086f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"df55f51c-2249-4301-9152-336ff26c086f","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 403 peer should be unavailable
,ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'listening 58868'
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1002c40b-36ad-4c20-8046-2011398cc810","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 first peer is expected to be available
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0419b3b3-3d5d-471c-ac57-4aaa172de48d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 409 second peer is expected to be available
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0419b3b3-3d5d-471c-ac57-4aaa172de48d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 peer became unavailable
,ok 411 it was wifi peer
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0419b3b3-3d5d-471c-ac57-4aaa172de48d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 we found peer again
,ok 413 it was wifi peer
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0419b3b3-3d5d-471c-ac57-4aaa172de48d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,# teardown
,2017-07-21 15:23:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1002c40b-36ad-4c20-8046-2011398cc810","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 416 error should be null
,ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 15:23:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
,ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'listening 58869'
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d2b6d02b-e148-4897-a5dc-02d10343facd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 422 first peer is expected to be available
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"743ce1bf-1bbf-456f-9846-0cde06c0a0a8","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 423 second peer is expected to be available
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d2b6d02b-e148-4897-a5dc-02d10343facd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 424 peer became unavailable
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"743ce1bf-1bbf-456f-9846-0cde06c0a0a8","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 15:23:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
,ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 15:23:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d876e6a4-4d0a-4d04-892b-c6f8bbf45095","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 435 peer discovered first time does not have new address
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d876e6a4-4d0a-4d04-892b-c6f8bbf45095","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 436 address has not been changed
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d876e6a4-4d0a-4d04-892b-c6f8bbf45095","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 437 new port handled correctly
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d876e6a4-4d0a-4d04-892b-c6f8bbf45095","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 438 new host handled correctly
,2017-07-21 15:23:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d876e6a4-4d0a-4d04-892b-c6f8bbf45095","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
,ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 15:23:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 15:23:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
,ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
,ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 15:23:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
,ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 460 contains expected properties
ok 461 the same hostAddress
ok 462 the same portNumber
,# teardown
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-21 15:23:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'listening 58870'
2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"de811a53-3022-4bbd-ae9a-5bf4610f96a3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 Got specific error message
,# teardown
,2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"de811a53-3022-4bbd-ae9a-5bf4610f96a3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'listening 58871'
,2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"592835a9-4228-48d8-922b-8c0be8a65d65","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:592835a9-4228-48d8-922b-8c0be8a65d65
,ok 476 native wrapper `disconnect` called once
,ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 15:23:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"592835a9-4228-48d8-922b-8c0be8a65d65","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 15:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 15:23:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
,ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 15:23:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
,ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
,ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 15:23:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
,ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 15:23:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'listening 58872'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CB2C77BF-B80E-46B9-BEC9-884BE0F32A27
,[ThaliCore] Browser.startListening
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c0e0ad63-780b-4a4e-a5bf-85c638f7399c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"524d8e29-a135-4f3a-b0a8-e4edbc92aa9d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c0e0ad63-780b-4a4e-a5bf-85c638f7399c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"524d8e29-a135-4f3a-b0a8-e4edbc92aa9d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:23:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 15:23:44 - DEBUG thaliMobileNativeWrapper: 'listening 58873'
2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a3c99f0c-1b2c-402e-b914-97adeb177ffd","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-07-21 15:23:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a1af801-4c44-488f-8b76-bbb958319b14","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a3c99f0c-1b2c-402e-b914-97adeb177ffd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 15:23:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a1af801-4c44-488f-8b76-bbb958319b14","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 15:23:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:23:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 15:23:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 15:23:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 15:23:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
,ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 15:23:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'listening 58874'
ok 518 error should be null
ok 519 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "044D28D1-9079-492D-8757-2C,17B15E076F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:044D28D1-9079-492D-8757-2C17B15E076F
2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 520 error should be null
ok 521 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9F0D619-4A48-4FF4-B8DB-5D8EE532AD34
[ThaliCore] Browser.startListening
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
2017-07-21 15:23:46 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5C453656-3299-4A28-98BE-D7BAD2ED7E26 (syncValue: 0)'
,2017-07-21 15:23:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
2017-07-21 15:23:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}]'
2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}'
,2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:044D28D1-9079-492D-8757-2C17B15E076F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
2017-07-21 15:23:47 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7288E5EA-A0B8-451F-BBDD-C515A1449811","generation":0}]'
2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"7288E5EA-A0B8-451F-BBDD-C515A1449811","generation":0}'
,2017-07-21 15:23:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7288E5EA-A0B8-451F-BBDD-C515A1449811","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 15:23:47 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7288E5EA-A0B8-451F-BBDD-C515A1449811","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
,2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
,2017-07-21 15:23:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 15:23:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] Advertiser: session connected Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 82D3C558-DEEF-4A44-BF81-75C7818BF561 (syncValue: 1)'
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-2,1 15:23:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7
[ThaliCore] Advertiser: session connected Peer(uuid: "044D28D1-9079-492D-8757-2C17B15E076F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}]'
,2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","generation":0}'
,2017-07-21 15:23:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:23:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] Session.startOutput,Stream(with:) peer:277C36C6-434A-4F0B-944D-ACB584A4C2BE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 12, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58882
,2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":58882}'
,2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 7288E5EA-A0B8-451F-BBDD-C515A1449811 (syncValue: 2)'
,2017-07-21 15:23:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 12, 21, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7 state: connecting -> connected
,2017-07-21 15:23:54 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:23:54 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7
[ThaliCore] Session.startOutputStream(with:) peer:BBACF90A-F04A-4A13-84BF-DBAA1E5BD1D7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 12, 21, 22, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7288E5EA-A0B8-451F-BBDD-C515A1449811", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58887
,2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":58887}'
,[ThaliCore] BrowserManager.disconnect peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26
,2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5C453656-3299-4A28-98BE-D7BAD2ED7E26 (syncValue: 3)'
,2017-07-21 15:23:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7288E5EA-A0B8-451F-BBDD-C515A1449811:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 12, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:23:57 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:23:57 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,2017-07-21 15:23:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7288E5EA-A0B8-451F-BBDD-C515A1449811","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 15:23:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 12, 21, 22, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted, socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [2, 12, 21, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58882
[ThaliCore] Session.disconnect() peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:82D3C558-DEEF-4A44-BF81-75C7818BF561:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "82D3C558-DEEF-4A44-BF81-75C7818BF561", generation: 0) relay removed
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}]'
,2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","generation":0}'
,2017-07-21 15:24:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"82D3C558-DEEF-4A44-BF81-75C7818BF561","peerAvailable":false,"generation":null,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5C,453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5C453656-3299-4A28-98BE-D7BAD2ED7E26", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5C453656,-3299-4A28-98BE-D7BAD2ED7E26 error: max retries exceeded
2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Connection could not be established","portNumber":null}'
2017-07-21 15:24:07 - DEBUG thaliMobi,leNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer avail,a,bility changed event with {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wit,h {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C453656-3299-4A2,8-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:044D28D1-9079-492D-8757-2C17B15E076F
2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 15:24:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-21 15:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 15:24:07 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 15:24:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 15:24:07 - DEBUG makeInto,CloseAllServer: 'closeAll called on server'
,2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeS,treams() vsID:21
[ThaliCore] Session.deinit peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [2, 12, 23]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [2, 12]
,2017-07-21 15:24:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C453656-3299-4A28-98BE-D7BAD2ED7E26","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:5C453656-3299-4A28-98BE-D7BAD2ED7E26
,ok 525 error should be null
,ok 526 error should be null
,# setup
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 15:24:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
,ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
,ok 531 getConnectionType
,ok 532 getActionType
,ok 533 getActionState
,ok 534 getPskIdentity
,ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
,ok 537 after start
,2017-07-21 15:24:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 15:24:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 540 clean kill
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
,ok 544 agent's destroy should be called
,ok 545 agent's destroy should not be called again
,ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
,ok 549 Size must be 1
,ok 550 Entry counter must be 2
,ok 551 Entry exists
,ok 552 Size must be 2
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 3
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 4
,ok 559 Entry 1_1 should not be found
,ok 560 Entry 1_1 does not exist
,ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
,ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
ok 575 Size should be MAXSIZE
,ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
,ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
,ok 593 good enqueue
,ok 594 Identity should match
,2017-07-21 15:24:14 - DEBUG testUtils: 'Got response data'
,2017-07-21 15:24:14 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-21 15:24:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
,ok 599 is an agent
,ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
,ok 602 start action is killed
,ok 603 killed action is still killed
,ok 604 enqueued action when stopped is killed
,ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
,ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
ok 610 wrong arg type
ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
,ok 615 2nd good enqueue
,ok 616 we are in the pool
,ok 617 We are out of the pool
,ok 618 Action was killed
,ok 619 The original kill was called too
,ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
,ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 15:24:17 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
ok 632 Start should not be called
ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 15:24:18 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got null
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 638 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-21 15:24:18 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
,ok 653 (unnamed assert)
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 654 is an agent
,ok 655 Null 3
,ok 656 Replication not yet called
,ok 657 Notification 2 not yet called
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 658 is an agent
,ok 659 Notification went first
,ok 660 Notification 2 not called yet
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 661 is an agent
,ok 662 Notification finished
,ok 663 Replication finished
,2017-07-21 15:24:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 664 is an agent
ok 665 First does, not throw
2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 15:24:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 15:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 15:24:21 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
,ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 15:24:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 15:24:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
ok 684 correct error message
,# teardown
,2017-07-21 15:24:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
ok 689 Start after killed
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-21 15:24:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-21 15:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-21 15:24:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 15:24:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
,ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-21 15:24:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
,ok 701 ecdh for local device cannot be null
,ok 702 milliseconds cannot be less than 0
,ok 703 milliseconds cannot be 0
,ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
,ok 708 (unnamed assert)
,ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 15:24:35 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
ok 720 good preAmble
,ok 721 good unencryptedKeyId
,ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
,ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
,ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
,ok 740 peerDictionalty contains 2 peers
ok 741 bluetooth peer's notification has correct connection type
ok 742 tcp peer's notification has correct connection type
,2017-07-21 15:24:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 15:24:38 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-07-21 15:24:39 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-21 15:24:39 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
ok 746 entry is resolved
,# teardown
,2017-07-21 15:24:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-21 15:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-21 15:24:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-21 15:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-21 15:24:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 15:24:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 15:24:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
ok 764 correct number of requests
ok 765 correct number of failures
ok 766 correct final peer state
,# teardown
,2017-07-21 15:24:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 15:24:45 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 15:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 peerDictionary should become empty
,# teardown
,2017-07-21 15:24:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 15:24:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
,ok 769 peer state should be RESOLVED
,# teardown
,2017-07-21 15:24:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 15:24:46 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
,# teardown
,2017-07-21 15:24:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-07-21 15:24:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-21 15:24:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 15:24:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 15:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 15:24:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-21 15:24:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 15:24:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 15:24:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-07-21 15:24:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-21 15:24:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-07-21 15:24:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 15:24:58 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
,2017-07-21 15:24:59 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
,ok 812 first action kill called
,ok 813 second action kill called
,ok 814 first cleared dictionary
,ok 815 first cleared pool
,ok 816 second cleared dictionary
,ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 15:24:59 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-07-21 15:24:59 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 15:25:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 15:25:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-21 15:25:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-21 15:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 15:25:02 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-21 15:25:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 15:25:03 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 15:25:03 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 15:25:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 15:25:05 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
,ok 851 All tests passed!
,# teardown
,2017-07-21 15:25:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 15:25:10 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:11 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
ok 853 All tests passed!
,# teardown
,2017-07-21 15:25:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 15:25:14 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 15:25:15 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 854 action should be killed
,ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-21 15:25:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 15:25:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 15:25:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-21 15:25:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 15:25:19 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
,ok 859 Error should be timed out
,# teardown
,2017-07-21 15:25:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-21 15:25:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
,ok 863 same localDbName
,ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 15:25:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'listening 59022'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB9C9F31-15F5-478D-946F-E24232546104
,[ThaliCore] Browser.startListening
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C8077C07-B78C-4B70-A159-5DD76B16A0C5
,2017-07-21 15:25:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Advertiser: session connected Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] Advertiser: session connected Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2","generation":0}]'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2","generation":0}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:25:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2 (syncValue: 4)'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF,C2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8077C07-B78C-4B70-A159-5DD76B16A0C5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8077C07-B78C-4B70-A159-5DD76B16A0C5", generation: 0)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","generation":0}]'
2017-07-21 15:25:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","generation":0}'
,2017-07-21 15:25:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 15:25:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"75F3DD46-7D76-46AE-8D28-4484695DBABB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0 state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] Browser: session connected to Peer(uuid: "CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59025
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":59025}'
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 75F3DD46-7D76-46AE-8D28-4484695DBABB (syncValue: 5)'
,2017-07-21 15:25:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "75,F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 12, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] Session.startOutputStream(with:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 12, 25, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 12, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 12, 25, 27]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:,) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] Session.startOutputStream(with:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 12, 25, 27, 28]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 15:25:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 12, 25, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 12, 25, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] Session.startOutputStream(with:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 12, 25, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [2, 12, 25, 27, 28, 29, 31]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Adv,ertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 12, 25, 27, 28, 29, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 12, 25, 27, 28, 29, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 12, 25, 27, 28, 29, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
[ThaliCore] Session.startOutputStream(with:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 12, 25, 27, 28, 29, 31, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 12, 25, 27, 29, 31, 32, 33, 34, 35]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [2, 12, 25, 27, 29, 32, 33, 34, 35]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.startOutputStream(with:) peer:90B0F54E-A9CF-4A42-8EB7-CF997B76E24E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 12, 25, 27, 29, 32, 33, 34, 35, 36]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [2, 12, 25, 27, 29, 32, 33, 34, 36]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFC2E601-CFC0-41DB-95DA-3DCDEE3E3CC2:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:25:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] Session.startOutputStream(with:) peer:2477A8C1-DDB3-4A71-A912-296BF0E07EAB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 39, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "75F3DD46-7D76-46AE-8D28-4484695DBABB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:59045
2017-07-21 15:25:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":59045,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 12, 25, 27, 29, 32, 33, 34, 36, 37, 39, 41, 42]
[ThaliCore] BrowserRelay.didOpe,nVirtualSocketStreamsHandler
,2017-07-21 15:25:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 15:25:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [2, 12, 25, 29, 32, 33, 34, 36, 37, 39, 41, 42]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [2, 12, 25, 32, 33, 34, 36, 37, 39, 41, 42]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [2, 12, 25, 32, 34, 36, 37, 39, 41, 42]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 12, 25, 32, 36, 37, 39, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [2, 12, 25, 32, 36, 37, 39, 41]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 12, 25, 32, 36, 37, 39, 41, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 15:25:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 12, 25, 32, 36, 37, 39, 41, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
,[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [2, 12, 25, 36, 37, 39, 41, 43, 44]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 12, 25, 36, 39, 41, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [2, 12, 25, 36, 41, 43, 44]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 12, 25, 36, 43, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 12, 25, 36, 43, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 12, 25, 36, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:75F3DD46-7D76-46AE-8D28-4484695DBABB:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 12, 25, 36, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [2, 12, 25, 36, 43, 44, 45, 47]
,2017-07-21 15:25:31 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 15:25:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 15:25:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [2, 12, 25, 36, 44, 45, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:44 [2, 12, 25, 36, 45, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [2, 12, 25, 36, 47]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [2, 12, 25, 36]
,2017-07-21 15:28:22 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 15:28:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:28:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:28:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:29:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:29:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:30:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:30:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:31:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:31:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:32:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:32:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:33:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:33:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:34:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:34:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 15:35:22 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07,-,21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGE,R result: passed - enqueue and run in order'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enq,ueueAtTop'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-21 15:35:22 - INFO CoordinatedC,lient: '***TEST_LOGGER result: passed - another'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failed,NativeConnection event when we get failedConnection from thaliTcpServersManager'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection',
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
2017-07-21 ,15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully ,receive and replay discoveryAdvertisingStateUpdate'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 15:35:22 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
2017-07-21 15:35:22 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 15:35:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:35:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:35:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:36:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:36:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:37:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:37:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:38:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:38:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-4,2D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 15:39:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D,1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 15:39:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B5455D0-D113-42D1-87CF-C8C576A2CC01/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
