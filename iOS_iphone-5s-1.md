#### Test 113351851f4ec514_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/E6D3C92E-549D-4DE9-A7A4-73F86AC379A6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E6D3C92E-549D-4DE9-A7A4-73F86AC379A6/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f4ec514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52347"
,(lldb)     command script import "/tmp/E6D3C92E-549D-4DE9-A7A4-73F86AC379A6/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:49:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC3C492A-AA57-4F17-8119-9F86E5B48C32", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DC3C492A-AA57-4F17-8119-9F86E5B48C32
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D2A563F1-EF69-4DA7-BA8B-CB34FC843BA9
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_liste,ningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:66AA6C5D-BFEE-4097-930B-76D8051CA526
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ABA213EA-D2DB-4687-A682-3606D156D3FA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:ABA213EA-D2DB-4687-A682-3606D156D3FA
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ABA213EA-D2DB-4687-A682-3606D156D3FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ABA213EA-D2DB-4687-A682-3606D156D3FA", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-20 12:49:22 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.696463942527771
,2017-07-20 12:49:22 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-20 12:49:22 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ABA213EA-D2DB-4687-A682-3606D156D3FA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ABA213EA-D2DB-4687-A682-3606D156D3FA", generation: 0)
,2017-07-20 12:49:26 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-20 12:49:26 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-20 12:49:27 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-20 12:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-20 12:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-20 12:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-20 12:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-20 12:49:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-20 12:49:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-20 12:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-20 12:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-20 12:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-20 12:49:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-20 12:49:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-20 12:49:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-20 12:49:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:49:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:49:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:50:07 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-20 12:50:07 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-20 12:50:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-20 12:50:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-20 12:50:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
2017-07-20 12:50:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in ,the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-20 12:50:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
,ok 10 should be equal
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
,# teardown
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
,# teardown
,# setup
,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
,# setup
,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
,ok 42 executors is called
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
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-20 12:50:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:50:40 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-20 12:50:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:188C85FD-3DB6-414F-87AA-B5CE3D40D099
,[ThaliCore] Browser.startListening
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:50:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:50:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:44 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ACD23CC0-7D4A-4309-82BD-75823C3C2654
[ThaliCore] Browser.startListening
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Received state ({"discoveryA,c,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:49 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6E787430-6ABB-412D-BDC0-83E214650B3C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6E787430-6ABB-412D-BDC0-83E214650B3C
2017-07-20 1,2:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6E787430-6ABB-412D-BDC0-83E214650B3C
,2017-07-20 12:50:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:50:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44816A62-DC81-4A16-BEE3-79803EC7B467", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:44816A62-DC81-4A16-BEE3-79803EC7B467
2017-07-20 1,2:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44816A62-DC81-4A16-BEE3-79803EC7B467", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:44816A62-DC81-4A16-BEE3-79803EC7B467
,2017-07-20 12:50:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:50:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:50:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:44816A62-DC81-4A16-BEE3-79803EC7B467
,[ThaliCore] Advertiser.stopAdvertising() peerID:44816A62-DC81-4A16-BEE3-79803EC7B467
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:50:58 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:50:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:50:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A9413A1C-B780-4B25-A928-D927B5CAD186
2017-07-20 1,2:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:00156A83-8347-4948-9417-5ECBB27DA7B8
[Thali,Core] Browser.startListening
,2017-07-20 12:51:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A9413A1C-B780-4B25-A928-D927B5CAD186:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A9413A1C-B780-4B25-A928-D927B5CAD186", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A9413A1C-B780-4B25-A928-D927B5CAD186
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33
2017-07-20 1,2:51:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EF15780A-A250-4691-84E5-A4F6B6AACD00
[Thali,Core] Browser.startListening
2017-07-20 12:51:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:04 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
2017-07-20 12:51:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17, (syncValue: 1qYYWRGEv1QGQNFgswOg0flvOB9jxteh)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E6,7", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0) creat,i,ng a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D66EBE1D-CA6F-45B5-A4CE-7104FDF54E67", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","generation":0}'
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33:0
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE,2C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1qYYWRGEv1QGQNFgswOg0flvOB9jxteh","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1qYYWRGEv1QGQNFgswOg0flvOB9jxteh', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5BA566D9-7014-4810-A0E9-90FB098310C8 (syncValue: TJiA1g0AGHwYrSMaWOybumP1Nh5qJW7Z)'
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 12:51:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C5CDF2F5-B94E-4A6B-8828-7A7D80CF7E17:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9
[ThaliCore] Advertiser: session connected Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7
[ThaliCore] Advertiser: session connected Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5D6E3E,74-BB3C-4DDE-AF68-B667D4F857E7 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9
,[ThaliCore] Session.session(_:peer:didChange:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54688
,2017-07-20 12:51:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TJiA1g0AGHwYrSMaWOybumP1Nh5qJW7Z","error":null,"portNumber":54688}'
,2017-07-20 12:51:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TJiA1g0AGHwYrSMaWOybumP1Nh5qJW7Z', error: 'null', listeningPort: '54688''
,2017-07-20 12:51:11 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-20 12:51:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33
2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:,51:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5BA566D9-7014-4810-A0E9-90FB098310C8
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54688
[ThaliCore] Session.disconnect() peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:1CAF6995-15F9-473F-94B7-657471EC61B9 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uu,id: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] S,ession.disconnect() peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4EE9DEDB-44E6-4B7C-ACD6-1CE24C5E8A33", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TJiA1g0AGHwYrSMaWOybumP1Nh5qJW7Z","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# Can shift data
,[ThaliCore] Session.deinit peer:5D6E3E74-BB3C-4DDE-AF68-B667D4F857E7
,[ThaliCore] Session.deinit peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2F0DF457-C0FF-4613-83CB-F1DB28937A4E
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FFD06073-BB6B-4837-8695-D51B15694648
[ThaliCore] Browser.startListening
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","generation":0}'
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D4BF8053-6BD4-4FAB-914E-B2038E74DE2C (syncValue: WEe11DPhmMl0SXNND7oVpcuLcoQlM8Ep)'
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5BA566D9-7014-4810-A0E9-90FB098310C8","generation":0}'
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2F0DF457-C0FF-4613-83CB-F1DB28937A4E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2F0DF457-C0FF-4613-83CB-F1DB28937A4E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:57067783-49B1-4C99-BF93-13609A1DCD30:0
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "57067783-49B1-4C99-BF93-13609A1DCD30", generation: 0)
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"57067783-49B1-4C99-BF93-13609A1DCD30","generation":0}'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5BA566D9-7014-4810-A0E9-90FB098310C8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5BA566D9-7014-4810-A0E9-90FB098310C8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D4,BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D4BF8053-6BD4-4FAB-914E-B2038E74DE2C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D4BF8053,-6BD4-4FAB-914E-B2038E74DE2C error: max retries exceeded
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WEe11DPhmMl0SXNND7oVpcuLcoQlM8Ep","error":"Connection could not be established","portNumber":null}'
2017-0,7-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WEe11DPhmMl0SXNND7oVpcuLcoQlM8Ep', error: 'Connection could not be established', listeningPort: '%s''
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D4BF8053-6BD4-4FAB-914E-B2038E74DE2C","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-20 12:51:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0 (syncValue: OHPiSK7,SbsxC5BbWnyNVylLY4zgHRSh8)'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D1D7EE2C-6B14,-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:51:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D4BF8053-6BD4-4FAB-914E-B2038E74DE2C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54704
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OHPiSK7SbsxC5BbWnyNVylLY4zgHRSh8","error":null,"portNumber":54704}'
,2017-07-20 12:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OHPiSK7SbsxC5BbWnyNVylLY4zgHRSh8', error: 'null', listeningPort: '54704''
,Connecting to the localhost:54704
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,Connected to the localhost:54704
,2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 12:51:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] T,CPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliC,ore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,2017-07-20 12:51:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2F0DF457-C0FF-4613-83CB-F1DB28937A4E
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54704
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OHPiSK7SbsxC5BbWnyNVylLY4zgHRSh8","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:51:32 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:25ACE2A0-0407-4C75-8F00-F7E349C427D2
2017-07-20 1,2:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:65FFF05D-C114-4238-ADA6-D566FCEE2C41
[Thali,Core] Browser.startListening
,2017-07-20 12:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:51:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
2017-07-20 12:51:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","generation":0}'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0, (syncValue: 9uycQU7n7f7XR1WtRRqVh3EJgTDwmbnQ)'
2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3C,D2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","generation":0}'
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:25ACE2A0-0407-4C75-8F00-F7E349C427D2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","generation":0}'
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:51:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D1,D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:51:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9uycQU7n7f7XR1WtRRqVh3EJgTDwmbnQ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:51:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9uycQU7n7f7XR1WtRRqVh3EJgTDwmbnQ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:51:39 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 12:51:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:51:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:51:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D3868CD6-0B33-4541-B250-1BD91D759404 (syncValue: 1yCCbx9g8VDID6KWCL9tfeL,lNtY4UiZA)'
2017-07-20 12:51:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D3868CD6-0B33-4541-B250-1BD91,D759404:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:51:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D1D7EE2C-6B14-4A31-A478-8001B3CD2DE0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54716
2017-07-20 12:51:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1yCCbx9g8VDID6KWCL9tfeLlNtY4UiZA",,"error":null,"portNumber":54716}'
2017-07-20 12:51:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1yCCbx9g8VDID6KWCL9tfeLlNtY4UiZA', error: 'null', listeningPort: '54716''
Connecting to the localhost:54716
Connecting to the localhost:54716
,Connecting to the localhost:54716
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,Connected to the localhost:54716
,Connected to the localhost:54716
,Connected to the localhost:54716
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-20 12:51:41 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 92 correct string length
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-20 12:51:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,ok 94 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:4 [3]
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] Advertiser: session connected Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] Session.startOutputStream(with:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [3, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] Session.startOutputStream(with:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 5, 6]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] Session.startOutputStream(with:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (12004 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:5 [3, 6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server received all data: gwZQhKwrcB9T2ejz19nIrcRxQWUQpFDuGWUacTpnd12PyK3DDSOm5Ph90f8w4KMnGwZaoAoHv3sinoMF82AGCxmny4fuNq8FhGyQFNhM8jzgxMBgNeC5qTsJ3wFJqf3UkOg7liIRi2b9hhI5yjhO9J2FNPZqYXbgkgAbKSiXhvdJxYTNsb,hUq5ghsGksNs57i697rxZ8tLl775YjPbzOkdtg3zwJhBmClJBh5OVptl3s24aTO5hNY5zl3PpFvPrSSjX9vEfweOq2rzYXeMKTlo3jtl2TEFw3ex1EQyWDJ3mL3uzEkwvQPZJNth0nHTD6fDzFLfOzNfQUjjUInLy9Da1U05EKJw4O1oHHNw79DHJ315xnjQtBOCrfVvqgy9RdIBVFLStfmB5yhJLYDkYnY7vsfDrOXD2CLqahvTFWLnBWshoqbp,0iMEewbZmqBqK4uUVY5ifr7NK65ZhuB6LVLSXucV2AbEdwTmig4kEE8vUxTLuGhYaGwWAdYXEqubW3T2kbyJAOAtOLmvswqo1F0ZbYJgbvs0x1M1Yje3tYvE6tJjoNHb0enzlNuoUyNMkjGzNYfo95PEliDfZtw4aOyMOtlWa7tCjcQsXOdSvdvxgbSi8N65B7loV995NxWCzOQ5zNUYqrOs1Igw2kH9G9riDcqpciZRaBcEy2mVC29xuTxGFGBV,2rGFOSb24NkWe7xCx2hdHhqr384zn5oyijT2RzKrl9Oof50oc729KXmTxBw5T1X696L8mDsnSx4M9ZrA7JvM47jnT3pYZXPgXzMwwdaomSOXcYNTV6m7EXPO2R5IiNnlmwPmoi8Y3rY09Ip87aEJfWDnaaG0fLi2LRMDs4Ku0zIa0iVkJpyri40T9Ui1XPjT0ai9uLQpWxMGOA1ZMOxNuKC9Cl5pwKCxZR9ULayk57L1b4EkYNUgccJZfhfs4tEV,g2gs7NTw4fbpaTSZ6HrVv6xGSVw62VrMhWvWZ0KoqVAKOdcEDcGka31QdPQYfkNKtn4dUJoHke0OTpXrZHOPzlMsTjJtKqLVN8ekOQrfpTSJjFd1QUrTJtr28rHFLSr1toqIrYXZInjyBvm92RgtJ3ftDa7E4T53NYnbNu4NJYncPp138b4WegDdfZlNBUe2GMriD1hUlR3f8O00I5p0Gm3kSjXDCPTEJAsKRbjPCpTQuRdbn25QubTgqKxcqNCP,alCb6ePKv4J2GfZgoZl2oR7UglmFuFS3bcV9gAPdkRLRUSf6XEkKFevZuv1utwXaxd3khownpuEAiwoqeed6E0L87Y9p17VQUT1QxPyZ6ntUhe8JOrAeMDU4W9vnJc7wL7X1ZUwPBU1fVEEaKxNazkNjdEKEieq1P9AIqkZ1Tp3iPHUa6dYZEMvnN1Q2ZuONL6MuFA0oWC61OuXaDwp89aYqqpDi8MBTSP4q6rlfHKJ1tvzHsOfpa0qXaAuMxNU5,GZTZSUfpxipRLx60rh1WIIXW8gtlUvaybANQxYIUQiO2x9UE4omly4kzmpXR62FBB0LTqn7JM3OoRYN192K7wjA7UW1oL9GCHsZxuDMTgwhKwkLrVpIZ8XBHw3ec6IXY1iGupO7b4GpIE12ZfJ8xDXPtngUy5Exj4WBWtn37y2inqvPqJrcSHevQde7Pu2OU3A2lvVHIR4hkc9gDc0vyybj0ZKIivMXCIlTKGFVwk7OYmUKlnzhNn7eInroaXmp3,GkzWjLR2WmINyv0Yl9Q4DgSu9fBNjhRfXwlvHciEc3T2MA3t0nzTm3dJaIxnuwm0hNCa7SGr8g473M4e9pjtnStseiOu3fFxXin1eYoRWJP5VClMQyIMXW69pyPo3TVSfDrZe9QIAwnTdEhJtpj9llEy3Jd3J4sChvrDYQlh93Ne56gBnixgyfL0kiYK4QooFkzRBauK0gVkduvTtFbLigxhMvvIlTq3P0sKdQC6D8UFd1jMTnk8Q7ktjpLBOzoD,3DNTsdtgmSKwgmb2YPQQGbdtEPABIfMFNBQA0HRmXZaUOXQsOlGUg5G0Zp5d1JiKW2KZnFNphXPwifKpuQ0XIhtqvbTYWBrThLDmyQqruBejQUVxNUYNqfQtTqTE1sRTEwH3aOzanQaPlJgQwBd5azOzPvqqLX5t7l6aqcZVs9q3guTi7hAV5DHordtFsiuPH2naSsVlHpQlLOuH9z0U2kvpOr4EHszpaJSzddfsAXW61aTIshjXp22BUNLdG0pc,gXZeD7JR8rKzhWj8CfUtARxSD2ZLqYNUdqWnpMeyQpghUZzS0dh9GsJfmAjeOUypBULMgVfkks4mv74XqVtphZF72ChVTyACzZWH0c1R4JqbQt1mtCUaCBDi1CBejL3wL2v8cGoA0iBpvdFoYxyUNWGw1oFk4OUbgKihuu5LaYb0bhzxb1LIAPKho0op2apGgzPcBoTJTPBzeMz67YsFGoQMeZbPZj765IAXdWARmpAPc1cfJUtcyVlVy1M7X5HG,Pv3MG3d8aRhaPHDvFJfx2TXcdvknhlPR35myT9gAh3sQp0RGtdER4aZhpcSaxCwscoSgDKVkudeOBgB7fiy5wOvi1x9fkYEQyywF0nEI3ZgIaXwXdzZ77E2qgQjNfpVRy4djImifMoEwXJtFFoEx1yNq30cTgRCJGbwApM9XXBNQApuo8hjBxExkSN3fdmAN4PI6MSB2hu2DbHVsc0GcV7j9mGbNr6lSHtXpknQAyV0z7aPzi8aUsFrxwVRqnVMa,ApYqsOEn7QjVcICP0asVhPfhARPtCZ7u848Ic2w400qPfAVYuW1jBPaYyw7CZmh8VFtVgIWGLRDhVNsdcoQ1PxVcbNnIWvjwgtTm7lvOKo4pXQPgc3IOn7gQEIKvrqf2FUjeCN3gDNVwt1yAPTKsjxmQooid00DqESPdxpgiizYSXiuqNhEN75okEhIuy8LvO4xBra4hItYuC8c9mxeqBNZZHQG2Rosf6EzAlqboX0hegDeOzNkgkUu3jexfuRds,IXGZaFIOoY3shPgWNT5SPLXkQuWFtFkUuDGKflqoqO6ISxhBWNEP4okhJLnT9eWNudXw39G5XXR9HRdmLFlFY5umBqpwqXsKuBks0QSGSorvIGSaQJjtJOeZw8stFelkdFI4ITqLdgsPHPGbqncKGZaREUVYHXsUFhpYNvJpnu6l5K5Hps8YXhj4IKnuSSWbhcG3jqiYdsEBIZqzBsmSH3n317QDQfWRfygeMq5BTlncjmjRcs6ECxsAGL5EM1vT,Av2qHqGXkGX3jZZX83ArIqd17iAlExYp2nNYMgb0NmQ4GQdsD7wwAe3iNgKmPs7ouv87oQxygqyZqE7zL84QoWBW3Y2uLttMGItPVT1pnecr364shscRo7uYG60cNtCkw9RxFZ3cMwHOjXbtJzuFr7rjaLYk0QjsNRTf9csipZpQgsvfAxKCpQHNw5H7mdQoP1xHUpNhlYw8tHREwpebFiSsdKZ6Un2Jp3F0o6LVKkzlIgx2GejFtg9mhFZg181l,bx77BVK5LFWcwwHarTGwwTJAwr44eOOgWBmxUreJk4ljYg0JmWPvO8VOAgrKnYxjFSroHKkrUoUwI7y3m15f1VKMh2HSo5snce2LCCwgoL1f7jxfBL1jHfaiBmxep8HuUMECtmd7GQ6cauVcIVZ9hqh37SdD14IsSmY4KXFJNAhRNvB8aMfkB5BFRs1g24p4NZ68Ev92exga5d44OxIl0W0aTVRN04inZvedjrACT1pBCnAKmSTF3kx172CmMRV4,LUGlDlCjuc6cWKpAA5ADohPT66IL8mmaYi3z4UVynyHIeliQgouiLZKtdwgCKiTlzs83bijSwKq9mjJ5VkcPKTbq537WoP2SgNIujjVI9tYMtnCXoeVB28NxbYXZcf00Tn0C53CPanDVtwgS3evkPb9COeayYVYvbQV2Ju5V3mze1PSkatwRvC12vanACiVlmcJN5O8UJYKEEsTT4L1yoEqhKGcnPp3Y4jrKeePCN6xPrMXQpznHWxCGH4kMVKoM,NCVUkGJDDxenv3bDc1GOMhyl4WQtixkFwW1an0TjIEeSENomqs9bzMDrfbKMhqFePYCCyIpxBd9y3nhHrtX3OmoBcVulvatbvbb2rNCwiKPj9AFTDlxjbpTFBs16ixoFRi5f01QLJm8nEQTvQLxmvwqVzmYyVB3SVnC3FMcSDhGSwwdk8qbB6lhrRghrCvJareudgwHKUQI1mgW0ZygeVLoHcUmOdWuIFV3SyegacIcWd162ECxopbBgrJbOm3LE,KmI77auT9FKV9tFMZB78zzZLVL4pyhwJZCRgJUTa3QyIU4mmLC1pxapq1PFqiDq7Q476xl5gpJqaOxXk4R9ZznuhLtUTccu5m6idfGKMyCxDmMz6cZ8B2DhiL8ESHnYu56s4qncgJ1MSqLW6dYVTHT0uX4IgL2U5kM1oVA7l0OerDO3K8P3JHg8ZAFStsPLKx0kA4grjKMvHkinaY90v9XeNv2EGrz1NBfXyCRKzjLi8uMCOvyieB05UNaV1HHC6,Afoim214wk7lHRRULiTWpdCjQakzYCPsPSCi0yAUBwOx2rVZ490zzpozVE6nogl09s3RaSBN61oa7EDn9v6IapivV3xx109q2POaKzs3pToQoyBtQtaq5U3QhfX4nPSz4JHSTLbBgVzIM8aUqAOp5tLowgMuHBoSxGOYRbs5n160dbRTYLnWK8GsbinEsjuyMFYWrVjS9fuZTc2PXrNWBCSip28p3CLKbbrHIUpNib2wRNm37ZWrh0QY7yuMI9xR,WyJdqgZ1XtnZbQhiMoqbP2j7WtGxp2lBOZDMT2fNtDWVu64vGgBAEgnWZKcknd4qtrfX3ZodCGqpAdNR7l03TjBzBKnpJEDmz1LUV11G7clOCBEGW0GNYF86TCNqHWmvtnHyus6cQNPVssH9dB3JyxZrBTsuUU0OlEBINrsDFVz8P0JxoWyNsBQwxGgcZbBVaf3jubDAJGzB0JXufp5Ng79VD5KDgukGdp2PAdr8rPFkwKRwgnt2Ix47tnyfmeC8,8hTJqhB3QcIq5QWAgTTMyIkoiZeuqiAGYXbu9zx18vbPDDEgJQo3RkHxtaaser9mDLgadtTP5f2VsSFKwLnEiRiFCll0oTCApgXhilG7kBUCXyypOenUvqUHSj1ixfYJlMTrVJmzswyu0rzZg2vdEupM5lwJXfSXSeSoroWRi5rfjZSjmaSCOb03q1ZR4BBPUMDGUUPAguXnpyubNVO2bNRlrlVoXNS584MCA6TY7Oc8kFXZohM3XQNF6KKfYwAx,Ob5LKyrm33Tby1Pnh8FFeafOpWWv9B6J6NplNUonapFqzdr0gYDYpjRBjWZ65NgfvffeAyFJJNF35JAXACNaBB6W13JTF4MszrSn7AbCr9Qpoy9cC4INLcZOjk9njXVgq7PHEkREJ7oD6cqV1LDcD8FSfwwUU7BVKa8tjaPG03yMbdJlsdxMH1IgGBB6n78D6MYAgxmrhNcCGz8htmsXbya3jp2vBKHtA6jP75dF8MUtRidPxb1Dq7UjdD8pJpmE,Hi9GaRF2qkT4xzXTippwdugkHh5kbfUwbtoUULafj9bNZsftmCFTUpkskFeaHTFlmZNX6Z4YVQLLFvctqBQHBhw8kktYEqhnV8oVhgbfpaRGxdTgnlMHZCLuCETe2GbtmdyYddtyax0tVCzMJhc0uMir9B18RnNkGc9KXpWaKcQKQ9YOpKeyHa0pYx5o4kTIfPZd6HhoysMIUgZPopzLQynwp7anvQSRAjLbgvHTkJZCuOKYHLEenrGNhRlLeBd3,3A5WUxzno5ioxL1YteyPqddrMOEMXfy3rA27TTgE77KlGp2AOJI4M4Ei1Agp6FkdZPeJyEK2q4wP6UcaGNxRNeAY8bavkAN1shceqLEa8HXE3OwsK26qGifnbEYW2UYo3s49NSthgfwzWKRCBC7WDiGpl1Ls8b5JYPh6vLNEzqSwm3ZJChoBkXE5uPZRqZtnP66yFMvyEvp2Lu8hDETlVtIXn1asVVgiXfT7w1SClxn4nFWkszObfyBtwLQFPnf2,LcpK688v04AXHWjJfrywBEKC0emfP91BvZi0knLpX8v2QMSOtH2CGj8NsKkVH7YZhtYMeuexPSzs5PE4CMg347sMRvCT8wAQgImQM2E5SAcqW8LSgWTE1ssYieeknokpK0itdf7KKQHUd1aPwIKPRPhcftzlUxflift8MVpZO3MDMjt6XlrAa4TGGwTRYYLuyPAripjDTU8JBzOGjr7lrcuS16QVgTmzhHbuOaXOiXCySOPqEnZ564Qiqrgt91ca,QIUkIRQEVsKyGvdYshuUbUnILZdofV9Zo2aCTJgz5WNeG9t04oRjHd0roxwM16LNiK6kHElwnjyBFOQGibH9b2BKVixaGTyxzgPedpKdiqOyOfOJQVFGlKb4lWTxPPI86zAhOBDiOJ5lfqCZGCkgbAtKwkKQNZc0arQkm7gp1QPOyWLsqhzbN1VtcKP4CGfYMUWvOMmRmUfST46EE9mKBiR9xC4PBvqJUr51w1ndJt3sGJcUXEIPY2jB6SFpn7qz,iKBKt0X7g1YqRNS18Ej7LCIpBBX3YM9DY7HdXEZvEZsh7UXsrEsden6CPMTdGKw1vvRD0XAck9riMMXmFryixJgYzi3arlUdGqbqybxL3OOnVgzAfhyL7S6990g5odmTod6I1eZKTkZHkI2Z8TE40kCGP64o8D5GOQIhz7sDqmF4fRxIkeabbqk7xyi5oPgJtJwrAeIjZOEOJhJB5GFiKBAnyqu8Iz4vS7DnJfKxE1gALsK9LScor1YqkTLr3r5a,aCnQgqeRrQuAruatmibiZsUmnlbArb4zK2d1vIfmttsCca9X4gThWZeRJK2TZGCIQgwPkONycG7fDevuexyhRSwP58b64gj75AqI9Tbil651T4ZYmvYIvD1og84zAjkwNfpuwqNdQghU3pJejVcRPc8JDODwSCVrf4GU72jsQVschdJkGKSiOmz6jBWMcxY8Ykinvf4gm6FOmgKvAs4wbvNGJYdEJ3iHDaoZAfc4Syqw49WSICCRVSeoD6Qdxb8j,4syI5hhaOe032905x45h3Wra0F4kVsb5HUhI6zLI50E9AXZHZgDWNx5p3XRw7FvFV6w4Krs5HZJLHWztHWyAkQrYS3Cw042P0erj1dhYiJgiX6IBPWvEr1vS2E0XdMDvmeOWmuS11V3iih8BS29ddtseRnZkIvEehxJFVLrVnv9oQAkno64xzghK3kS6nWsMG5ejxC39qbP2XkQ759cZCK6HtIiccVCftG7xKER1H2PNGNMmyiByo4dTjy625JMk,TeIbCx0Qk5OcNqlsmZNw7ndXqmJQlmfHxnU41sEnjiLo0RUGgc5S92GqshcYjk0ORmmfrbeyzOHZS4UpPLhwccxyX4dq0IaquHCL0hcrCFjhgd7jLkObdgyatDIubGVOIL8nCjinLsmUsD4DqriEtP1PtzNCm29uPZh8ZuqPbFMjtHDKGTdACg9XKOTSf7vCmWY8rtYDejZdxGy4ODa2zuwBEHXzQHueEdOElGY4tzisMd9bIY28ee6qx4IOr3MP,3T0vnKCMHAMDCyetVOqZsYv0UTqwwC6swX1iZic4itpWlc6Vu25OaRU4WasV91nIWnACVZovvozTDVbf5JHPb6DxmlBcO699rBLX16j0tEKaXbDyVO7JzJ3agrNNaycJTw6LayQ9Cjn9xAOfsEe1l4wc18Ym7ORYdJ8XbJE2E3fjGXybfNloFdvpmBzwyXJIgp193j0oE1UpYap7sc9GX9fIXqnk2o5uVarOHmAaSlJk12FjMIDrc3TLSxXm9yVR,Rv7GKdrCXe2RxcdstClSwW0bXRbxrnmM4RVB49Y0qH65cQ8EZjpuXS0bD9tKD57PJINAV0g239UVOcO00HaPgcPM7brUWmtc5hBAHGZD8Ibwf78Xd8e1SQjMI9egNAOKNjXdp2bleHtRtjj1SxUa9cfHCDYXwHmELcKJ8SzKcDmiYTLnKovl69PHfGGaDr4f3ZLB1OwwYnpv37VK081gu9X7LeAcBp4E1eLS1eNzpcV7Vmpqa8T8Xru4a0Abd6cn,y49gsKjZtNTWZfPocGfIC3R9ghfMOtx0aRI6tH88VDpSXviMs8dwugK7hHDffPoVhebxmSuNt2kUWZvYhnkambvSNeNjNbImWolI1rzmFXHWt4Lum1ZzJ2BO5hM8NLiBsTSwMeQqqDzwVs9kcgRv9bctmdr3oHCYFIQWqscySWSoHGsD36SFi6AHpR7UNexMawLTjbQFmH4EC5SHrmkHVReSJ0OOAdyR9yDnFqB5x9oXkVfYhBuogkIvNaLKZZ7b,GckgVYko87indBfrXNFzEZNMaPKgPe4vl0XBsB65ITQvl33ygPPFYJqhu6f8hDoBcyhlBCjgibMpO7tnDkqFTLEW1yKYKAr1DVqdt5t0bSBOWV9tELvJetXgFZTVgYgcRQQCtWv5hYaMB5na4mgL3wu80gmntrYQ5n0oRBwyMOn7QmA9S3acD1VqPPfjosPEgLroZBabmUmv3VcC5ZGQNBbcoRNAM2e6fjwH8OoBGV62kVaEji1AfrfMpmdVGP3P,HaRRwvbXxWnvG9VlulBI9B7DmnCRe2wgLlpWg3bnj2qL5VkcykdKRRZjZSaTQSBPuu5YHIMhjM9ZucGlUTGcace4D3qG2FnFNZEHt5M0IYoD6ktrl9o1waNTfIeBoGO3qFlVLEuRHK8SvV0Sml8HxGziihvLWPumEtyqJfxUFzIgSCDv9qr4SaxVQ5ANBiM2dYb1iAhj9vADBm8GUJee65WZEyxdAn8gGLSzM6SmXwCSYqDQfxbxlXYiMqEWtKMc,tAFOme5jhtoxo0XrrVu6a6Yw0LnrVU7i6UKuzpL5kp5bXCxjLR6ExPXW5TpXvJccxRGxB7jZuxagNboJsCz08LZdCuvhxuGwSeqDV9Xz0cSoWqwYimfQV9f9dmZvA8MRjNPhtSiUNiKNuE4RmN8VHl8qS5hU1OtLJvxqBSobMVcq6uYinjoIOAxKStII5DqGly6BfI9cKGbvJ7AnSxv96SCH2SuAmUFLC351iovmh9HViAw5YMsZArUYniuo4Tnq,wTPmWI8D2vuhhD5E7yMdRFNG4KGBhSpcmdNsjx7aFEEC2i0qgb5ZrFGouoFCTcHbvUyvp0bLh5dNtWqONjVhPIHKziAbAEe9Ym0JAeqLuYRA0XzVhnnWpQWvn4byBWirSsTVBQinhInHJcbK7mBGx2DeOj5LZJRV9J05fjFn83sohrK9xLyYqZxauQgnIFWL8Gj4YfKqm6kpq46r57E8WuxHm39zUh3LBQKUcMC1gXHpBz6GfeJi4dSWR2tbwLpc,LfZ5NDLxKYka05tqTKgaOplYI3ofAAOHbQkikGD5sq4JfGHCkWY1loaq0PDss9UgBqgdlZCuFJZCvLdOlWpmVIx5roC1r4NeUjAeeY2Y7qSucIb1DqaqlKm0yusOnUPxNWBrBhHPo1psZ7PrsC05kDQTJgq3clSzGuZVcyLwSYpFZlE7EeDF3imM4GOWml35LvmbfxVbkSve5PpR9iIiEGV1F023V3gYxyxAwFI4VI59dE3UaXqL0SnH9rRo8aub,n2KN89mMCGOYnv7uUQv832sFddYgaBO2Kk4gpW9Ztj4Zkot8ibg5iDMNUZAPDxYTPdhc6JjsSyuGyh9Xc7PIFqNXPRxdtfvMfOsFu4NZqdwxxcv2ScVyAxV6GNsITLRe04IZWa7i5eIDDj0nCpRgNayf0nRuDFRQ2Ec4Bh2hFB30SRQhpIQzJM7Fskr3aFACB2rpc0fRgwMtPROKYFHHMl2x8lnCNhf4eJte7Br7OC7FQFu0kCiiT0UdYeY8p1M6,ZEOlYuoj2r9MKjZQuRzAa6b1peF8geQBtkmO1maVLVngmyDLyFUSq8ppWq7K3v7gTdYcN0Vjw8ftC9b0GMyoEYdqPXYQY5jazzzXzskbqMdMq3fviJcnEKzYo4b0X6gOGgIuDf0t3N7UYzDFrvWWA8aoiA4ke5VZrXruz13ZtwytpOzE0J6HKoANivT5Z5guEJHP0tfmoFrwzUMUDPRVpMYrbP6JtfAqDy1bWGoXQwiViQyq9qlIvliVBpWmzyAd,N0hjOOgWVj6rqnImNPEAKiXNTurg6CJydL5QaXxfPufaNM2Vq1u2oqNhEl6VZlph3vxUagodQ3hMZUvD8daMayej4R8QpueHsGKBdUbre2EiC5lcXwNuYwuHs1Nt68DcHlbIu5LZOimADuZjOAMiU29cobxLaFrnlChwn3xHS1HiB0xQyFBhNAGkws4xZzyP2cW5jGRoGxwoojwqBzqFWfPRddlEOAnXLa9YXvtbqI2JzkDmAgwKdpYluBCcqdmP,IintiG7LMGe61mXP8KPQRbSJYJBLpmqBBWJx5VXHTPbqyZ2wAfQ2aa8KfFVC7SaFWAyfnvUoEQuFNFPbjj8uxisaqc9Mjpvlioe2DUPOfPy9PQkVVRTDKzZbMphTcYolAb8GWdcPdnz0JdGMWkaFTQupIrwY3A640IxJilIZWqYcRv3vEQrUQmPU6A3zEJuBnFBWeQLuz5J31Mc74Jvz6gjqduJqx3lOM5mxvwHDYl2DPo01x6gfNKqYNZrFNQDa,MtuanUgnQxjcv0MaD9ZqGmTo5DqpJqv9GCVs3WfRGZ2uS8MRLuZcuW18fMlEXdTl2bRxtBDYzOHbKHtucGV2zFVmnAJ4Q7S9F30Thw8WqiVcWEe3fqoij1jYdydeU7UKW22k5CLoiujeNW0CpOhBY07CLwgSlXjnNIN1Q9TsDRwf3dBgsrRdNqJz7xyjDKXfZEIta3nXqhFsDAYHStFgAWmVZsYk8VT3PYKNjUEbCXX1R66hVzwxCmPNBugEc6Rt,yIBlJnVaWCa8k0ILNsBxlaZQJSBNBOSEFX10UIGXDaJ3kWyAxkXRqWSlEO78RLth6lBsx1UvHnRTqRFdETCcFQMbE7oIRwzMJIUI1IexEYnh9QoLtzEHQ9DiZMqeSLUIEwxMmIGe7CVPTIpR1xqDZ6lx0Z9Pa31skMhXgeOkiqkwlr2uTKcGp6M5d9TMTlvV0ZKFhbneoOLcqCA1o1AyVMYSEg4U4rPyRJ9saU8kFnvfZIG2zS97VqtchMW2s5nM,f9lVCLZh8kBSPsyHkD1RSx96xh3h19ldfXddOVidfJYj5CDeqnUtrz4LAjFTKGw5bQJRs7OXzkTGxP4hJpvSryxtDgUlou0scPbAp28jAxKLzVymaoMI3SziEYjYSjEHacRLvhywxNkP7LGBQSb44im7nJB5JedVQE9iafb5p2Wm0jFgm70sAKbwqS35qf8w2UfkLN2aIulKWQMpeQ8ktC2c4SIWYqLkCenNKjraccVYGuhzsLW3VGqIGVY5005a,pExgdlLBExlSKksCdimhbHL5WCfwYjCaV8VfSkYok7sEfx0n9jNOc6dQNJkZstXutibE8D2e64XgP3EU5SEMcqJ2MNEclkC2DCk3cQH9Fmv8F5bo4ZB4cKn1eIeKMnZNzmN6dpxs2vHTVODE7WhqPNV5luXuiwxRhk8S3fsAZCBD3nlVEtfoGUWZ4iBlv0Yz2zsmHfpttt91uTjBlhP00Zytns6UKmX9C9ZxKxArKVRh0SXw7t5g7IKML6zZ7Bql,OuGcpcbqF1zP3B9vt2gQ5fTt1vfixqcgvHTmxogX3hAPwQbcIn01IYqNFTepO1HXnaBnWY0wcBKTv9vNHp7WEyzAWMCjhkYiY7ALkm2bS2Hoh5388VG5Ba9PLrmgLG3zOk5WI5en99mndFBlDNIIhqSCQIiYGJqW0ZwEaS4SpkX38vqtrWYnS6LHmoexwC4IZK5j8xX8oBAK3HbdHHrT6WEftDWiQAskIKIa2Bgax4x1GA9gR6a3Zu9jCALkMbDN,nwXmxtu4Jqd7a25b6EbTEhZ0OxvVLZdkh3L0cNCuNvw9Hnb69rUSJ5RMeSHjvbY1xr56mYU9JhIK1Qa3LAkNoeZ4QH0UnOubcBtdF3M7HpJ3lX1hPfOvEmInkEgt4JBn4KLYVEfUtUZuJETasFJUbfw655bAwMx7WP13U2n4XzX5HklEXl7tZaBK0czHRpasNcwKSL7CMaQ2GHpLbGF6ytLCkYaPrNAnS9bbxVDZxigXckjHCZtymnQEQwSGR2hV,GRzwr3MTGaQC4VUbYFNTAaXNgneZHaroEgP7UkFYGvYnTdKKfxSC4AgclnwHjxRlyd8uSA0acOu9oeX4i67NkRPwSjfiXe1VFJFkQv49SJKJEEYtwjY26l7fIIMK7Hh7WpGqYTLBzhQuXQbMZGYALvHgC8pmEBdZNQFdoED4a5wdidAU1al1P8GxDMOOOrVqDRdmco5N7xpAuzwRS5sUYimK5QKT1G2icSTFCTZCJIzby4GlupKOcdowEl4jMTYI,S1tDBi6TbmOprXdDbxhkikGahnUB3IYwR2vT4JQMMOXExTE7mvlaUSxhVLPiVRuBYhicEvbbrofXvbfuyLPLcKMZuFLtOa0rAYZ2qMaoj2ODiQIxw1fCVJMAQN1tDo5Qdqp9VhO6qmwGwAQxW2c96qLJhBma2XOU4bwQY5wdC41WzEOhkCxhhi8mGg2bOuZwK2XXF5H73fPIkmBcEFMOCMu9BHgFnqmU8n8UlulvuHdhY5qlxHyIF7kw3vVaCnrA,Li12hZQKMqQZHlus5pxhs9aPWs1iUgWt9nDG15jMN94cm4bUkvBFPcCews10PRUfcK4UIsoWT2WCTIU0gg7AwJy6Aew3NzvbDNE0D4TbUn4IXU24ocpwTD2WeCYD9MqldTJTCuFK0jLgX4ADflHyvUVUgYJWD3JSsLKolJhbYRaeawGsQ53Dj1Ds8pRTJsPJp6TVbPS4cYj4TUgjfJn9RCMBO72pqQNYuXpWqZHSrb9ehrFMWDTFd6BtVZ2L5OxO,MV2ySqOcVl5iXIjKv9iCqUCc30toKbvS0Cc3UMOhaRzFJQNtD7QNQrobAaewDpko97SzhZnDLVKvlqOxLo3OzfTz0ZBFjdfeFTqlAgnXF2VhgRJETmD62rxeuXQJqpZjNM52bqwSwKZuvcBaaRq1J1htX3qmawxPacLpjZm1cacO9vbMA0fAcOCL04R6Ts4V0VO5jcf84v8MmT2LNibJzOj2Lo3QxPa0XIVlagAsfUxWRSdW1pgN3vp9F38cu2xV,YnAGTf4bF3iP3S98ulTxufo7VYKnLKoFdvud65zZbGpkHldli24CM10JEHgd3VwwdCyPQoZpyaNJxRClFvciz6fNWnPFv9JbQYXdWLvt8mpntvj3vRCiqRGMpeo0vUfB5mVZCYhLZVmWLHWPZlntO80XLkkIAJRHO4cdE8fE8xt9WymRugM6FJCOg0HqruXCKEOJHceJrbX1hAxJDyMpsM29y4Ejp8jrrMHZ7kyyQJJIsVagZtw3216af4Imz8dE,0W3ZOcE5ljBnXo1dPwCgJ3sejHW0jjmSJKjLJIG1hiCCeDQORmQTSpsJSxaDIjdoEIPoKttWaBT5WTvtmK3dzLSaJNEjwIFtJV5uf71Ry9FUBpq4CiBWgvMpHIXKS6IIMPL0Fmlwq5L13BjuwND0sRBvB2BzaiX8TAhG1Nyakp1sXGSxFkCNc0Yfc1HZHaWvEyImT3z4SN76KjDl2IkNjBeE4mkmBsm09iVcvHteYZG0QmbtaqY28jXTVacJgNow,V6OXkvTyVWAaF33PuiSkNjQmQ6HTNPQGj6Sfyv7n9rQ4crn4oNFuCAgxer4WXC4vzGftagX8vIYjkl3VIurOSVhXB5z0bso0TPwYjkL8MgIBOADqAjiU6Tz28gBJpLHFxUhhinTcdB0NKvKQpGfMicVvBpU3gJFzV1MECy3G0bk1Wu4PKjOIRa8Tmcz1SG1ZqObrViTeVa94mKHbWiUveF9YdlTaKBpnkr7wyF5pMY326hdBE7R7bhhFrc1gq3kQ,jTUwNdEqu7VQA4bnmwsIDbculB27CN5CrLBzpjhSyGFTd4VulHcTrZGQDUj6kveQsKxmnTF7Slr4IDOflMsmiMAwtdTfZdyI2mzH60xt83ohQCybcuOVas8X1M3J5fwrFPERosTk5Q2W8AT8s6MhlT6xnayPoMYg7oHMZwGgIxVcGiL4ZARUxMePOWPSQO5sYyLFae5v2W7jhNlUxFwQkL5uvhK37gnrwlp2qvkmmoRYt6odrdKxvCaBhPXhkrHZ,6u5voEL2tPh5vf9rXWSe37Qi9BiJyCPtLS0PR8jtSFhnZpMZ8e9xs2STFUQCvIxjVKT6NeBER3FinZltgx5BTPLQgEbx3rwpqVnc0P5NP3N4ruw2LPwoiFfSCrzggVs5B7LEDeSOO6bDeHgsmsqOMvVK64UtxDYotO1Pn1ebUXerIoyMDGL6v2lpnRtky9itTeCpLcMBWCWjOV66rdtARmuKUhB062dTjMV3jghe8aoVnL0hw4cv2fMPBslsJClA,QgR7xeg7QvWS9DxfnS4sObm0HUEt24mNzotKkglFpN2zhz0L8OCKDdpXgOeZtrzseytqvJw9WNXQtbazhBj4ZMWRureHjFbvwV1tExNCCnnLgHGLXaA5UVq8aL6byMooz6xfFir5QxmcQaWmsgfpt0RNdNbmiyrWay1mRYMi1GZ3WWM2DtNWvHdv9O11Swvc48hzQQMcm43yC1c9aUQ3aG50Sg29LZ2qInv6VuKji0tUBFmafoiA0Nq0NKusAJ0O,931h5aPJHDUJNEo8yb1Ri9mRtr8iPcMFw4d61RfC25Qf6SXQ0Kapc4OiowW87e1BibEEyVgL4A3Bigo48uu5eYl7wGkQMx5BYKEBIZZdNr09S3tF9lElfKZINjjjhvZdaUwEW4CKxNnzlUoZp8rBUXsaUcmxY26yqtQw9FTmDejytWQBhvun6OIQOVFJS53Ffamw53ljRLE9dSeDW49cT6vJTjbPlkPGMS4qlN3D2CNI5SUn3fUbP4Qo99JvZiFL,H5nZpyEGKQjXTPMQewjSUOGYX6kSdIRAxNXnjYntsyQcXLitf0TX14PkZ1oKgxvmErJcxnjkPIY8pb8rztIA4Lur7YAonrznusiUXjMivAUmQWsB8G9UCQORCaImErs0tgqkrVDasQmLrG4VXUXWNH197JCrmHDo7VZpr1xLApR3LhudQkAE6AGs6bevS8SuLuTogTeHOZkou1MKcJwtzLUsCUYF0gtkq2vdRxBIxaUJnOR3WgcykkezeZTTPxn2,X4dQ3zWM5241h8F7rTgaVfAg6s4TXFoK9ro2ItUeiXAjFeg06hMYfvrYCx4sz99Z8Xm4mJ889LTkURPHLtnszTI7aAcd8Q5FrTPDAG2FuXxCZESyysSFM4ghCrlCD55AJfvu6jREJ9iJyodrTi6pnxIMFmhnIGaRdIguVkKEF8xz5KL2vW046j61OYplzZr8JyMFEqgnYFTXeD1BrYiZSRRAf0wTlhi1ix3b8ogbAmg5w9V4YVHqO4iRVCPeRGlE,Hqc7hkGY2ams7KAoibJZAxS9wR5ceGNTMuSjqHQiOw07OVdMRrRk7MgGVvpluBvfVr7ffE2HDchpPm0MbLLU973jvMSNbDQp26DVMUJ4syLudYZ8Qpc2DWdPj0plY4ZNB5hqE1BrzuKqhE8b6nYsKI1yuyjwtGVaOt7GSXeFDbvVflfPRtFWmXKVXzgSxvsCrgfdPAnhLP5UsXWLzsCrbe9kGs5znyMwwjR5mha9nGqBjr0HAHtoycOowoRM9TK9,efmuolCui6k3idLikbxHWhqw6H3XxRY08gF2uKhezjCwpUUOql9rZdMruzmGVsvOCuDForfWELr4Q61BXmk1No9RCSXFWyWhcmmm1qYaGoK0AJlpKcEBeUaMS2gsIVKt8rQsn9UUZuR21HEwAicJxnWYjeEkwFZxefqT6LfDmNA09vQUiUeaQPm2Q3T1ew4kMC55Ped8HoGcNQJACULiE857eUsk2FXrqPuUvaduotD7vF6rtpD03Tv7lDGxaaK5,mWQFUJTfySgWII1a9fSHnLJvBFitSLS8vQ2gZwkKnRLLqTwE454PeYoxnsx9iudysW48mXdybQrcDYYTE1uB06A0a63vHWrWTSH8KyOaU3f68UeNbc1LkNJKisevF40QOAa8L2n0W2nOBzxAEtgnCvdAK0BNSDfogpLvQvK8DsdI2y3488JKSVNVKMYx314r28989GZa8WEbjKJVRj6QwnSyVWcXjspUHWiB6IbDwqfFqmRGEYCJgAWVaHGm8Vax,yzqO4X1JzE9OvszI3oqZsF1oIYeSSO6aMLeTPqOUxTx6XmNfeVH4cpG7qFBA6lulBzuJJWyCwPaSZc'
2017-07-20 12:51:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-20 12:51:59 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-07-20 12:51:59 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-20 12:51:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-20 12:51:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6,
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [3, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:51:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:51:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:51:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:51:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:25ACE2A0-0407-4C75-8F00-F7E349C427D2
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:51:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D3868CD6-0B33-4541-B250-1BD91D759404
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54716
[ThaliCore] Session.disconnect() p,eer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:E3FE6AD3-98B4-40C0-B801-9397918AC770 state,: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "25ACE2A0-0407-4C75-8F00-F7E349C427D2", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:51:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:51:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:E3FE6AD3-98B4-40C0-B801-9397918AC770
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D60E8712-4E44-4465-9B4C-CFA9B5D222BF
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CD87EB12-FC20-4C30-9FFB-B5E6F77EFA53
,[ThaliCore] Browser.startListening
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
2017-07-20 12:52:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","generation":0}'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2, (syncValue: DfJpjR3Hq6hdbhLwiWZxHPtJ2JyUxke9)'
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retry,Count:completion:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0) creating a new relay
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] Browser.inviteToConne,ct(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D3868CD6-0B33-4541-B250-1BD91D759404","generation":0}'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D3868CD6-0B33-4541-B250-1BD91D759404:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D3868CD6-0B33-4541-B250-1BD91D759404", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","generation":0}'
2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D60E8712-4E44-4465-9B4C-CFA9B5D222BF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:E60180BF-4B26-4B3B-897C-EC3D67F3C1BD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E60180BF-4B26-4B3B-897C-EC3D67F3C1BD", generation: 0)
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E60180BF-4B26-4B3B-897C-EC3D67F3C1BD","generation":0}'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480
[ThaliCore] Advertiser: session connected Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480
,[ThaliCore] Session.session(_:peer:didChange:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480
[ThaliCore] Session.startOutputStream(with:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [3, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "4D1FBA3B-0C97-47A,F-A7A3-EE3B56892BA2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2 error: max retries exceeded
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
[ThaliCore] Advertiser: session connected Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[Thal,iCore] Session.session(_:peer:didChange:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369 state: notConnected -> connecting
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DfJpjR3Hq6hdbhLwiWZxHPtJ2JyUxke9","error":"Con,nection could not be established","portNumber":null}'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DfJpjR3Hq6hdbhLwiWZxHPtJ2JyUxke9', error: 'Connection could not be established', listeningPort: '%s''
201,7-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:12 - DEBUG thaliMobileNa,tiveWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8BCE56E3-D4A4-471D-B13E-1983A975CB39 (syncValue: MjoGcfQ,ksxb8BuXvCwhQrAMIWULkHcNC)'
2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8BCE56E3-D4A4,-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4D1FBA3B-0C97-47AF-A7A3-EE3B56892BA2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> connecting
,Server received psk id: psk-id
,2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-20 12:52:13 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54737
,2017-07-20 12:52:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MjoGcfQksxb8BuXvCwhQrAMIWULkHcNC","error":null,"portNumber":54737}'
,2017-07-20 12:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MjoGcfQksxb8BuXvCwhQrAMIWULkHcNC', error: 'null', listeningPort: '54737''
,Connecting to the localhost:54737
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:54737
,2017-07-20 12:52:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-20 12:52:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3]
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
[ThaliCore] Session.startOutputStream(with:) peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-20 12:52:16 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [3]
,2017-07-20 12:52:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:52:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D60E8712-4E44-4465-9B4C-C,FA9B5D222BF
2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54737
[ThaliCore] Session.disconnect() p,eer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:32FCF143-A63F-48EB-86FE-2E0BD5758480 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D60E8712-4E44-4465-9B4C-CFA9B5D222BF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,[ThaliCore] Session.deinit peer:C7DF29DD-99B1-49C2-8D4C-E66868816369
[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 12:52:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1FC588A3-45D2-4DE6-BDAE-579C029A9613", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1FC588A3-45D2-4DE6-BDAE-579C029A9613
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8D5C1303-1474-4214-AF8A-712DA3BB2B0D
,[ThaliCore] Browser.startListening
,2017-07-20 12:52:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-20 12:52:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
2017-07-20 12:52:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","generation":0}'
2017-07-20 12:52:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8BCE56E3-D4A4-471D-B13E-1983A975CB39, (syncValue: iePk1bbkL7MW22DtjVqx9nu8o4BWxyNR)'
2017-07-20 12:52:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A97,5CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
2017-07-20 12:52:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4121540-BB03-4856-A0E5-C0E220AE5A98","generation":0}'
2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
2017-07-20 12:52:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"7099301E-F445-486E-A603-9612A1AC58CE","generation":0}'
2017-07-20 12:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FC588A3-45D2-4DE6-BDAE-579C029A9613:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FC588A3-45D2-4DE6-BDAE-579C029A9613", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8B,CE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8BCE56E3-D4A4-471D-B13E-1983A975CB39", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:52:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iePk1bbkL7MW22DtjVqx9nu8o4BWxyNR","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:52:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iePk1bbkL7MW22DtjVqx9nu8o4BWxyNR', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:52:20 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:52:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8BCE56E3-D4A4-471D-B13E-1983A975CB39","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 12:52:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:52:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4121540-BB03-4856-A0E5-C0E220AE5A98 (syncValue: SBzJI1l9wvDvEvXkMSi6qZ3,os7Nt0IaW)'
2017-07-20 12:52:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4121540-BB03-4856-A0E5-C0E22,0AE5A98:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8BCE56E3-D4A4-471D-B13E-1983A975CB39:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B4121540-BB03-4856-A0E5-C0E220AE5A98", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54748
,2017-07-20 12:52:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SBzJI1l9wvDvEvXkMSi6qZ3os7Nt0IaW","error":null,"portNumber":54748}'
,2017-07-20 12:52:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SBzJI1l9wvDvEvXkMSi6qZ3os7Nt0IaW', error: 'null', listeningPort: '54748''
,Connecting to the localhost:54748
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
,Connected to the localhost:54748
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-20 12:52:24 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-20 12:52:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1FC588A3-45D2-4DE6-BDAE-579C029A9613
2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12,:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B4121540-BB03-4856-A0E5-C0E220AE5A98
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54748
[ThaliCore] Session.disconnect() p,eer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B4121540-BB03-4856-A0E5-C0E220AE5A98:0
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0FEFDFA8-CE33-40D1-9D8B-7234824C9653", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0FEFDFA8-CE33-40D1-9D8B-7234824C9653
2017-07-20 1,2:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B8B724DF-AC0B-4F96-A9E6-9E1119736790
[ThaliCore] Browser.startListening
2017-07,-20 12:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7114A0C4-6ABB-4EFC-9D9D-3A41FEDA2B71", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7099301E-F445-486E-A603-9612A1AC58CE:0
[ThaliCore] AdvertiserManager,.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0FEFDFA8-CE33-40D1-9D8B-7234824C9653
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7099301E-F445-486E-A603-9612A1AC58CE", generation: 0)
2017-07-20 12:52:35 - DEBUG thaliM,obileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:52:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B4A568CC-39FB-49FF-9BD8-93282E4322ED
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0E71E65A-DB20-42CC-BB57-06C8BCA3F6ED", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0E71E65A-DB20-42CC-BB57-06C8BCA3F6ED
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0E71E65A-DB20-42CC-BB57-06C8BCA3F6ED
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-20 12:52:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-20 12:52:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-20 12:52:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:42 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-20 12:52:42 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:73b084d2-3c54-4e01-a672-cd31067430f7 error: startListeningNotActive
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"64E0WSxbgv8CFfCDWTyTZbCxnlyKkuOc","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"73b084d2-3c54-4e01-a672-cd31067430f7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"73b084d2-3c54-4e01-a672-cd31067430f7","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:726E3F88-9F29-4AAD-87D1-087FF423014E
,[ThaliCore] Browser.startListening
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 No error on starting
,ok 134 Got null as expected
,2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cK7TAbLFYB7zJJvpO0FMdpr5WbzLu2yl","error":"Illegal peerID","portNumber":null}'
,ok 135 Should only get called after multiConnect returned
,ok 136 SyncValue matches
,ok 137 Got right error
,ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-20 12:52:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:75F7549A-79C5-429B-B219-C0F615168699
[ThaliCore] Browser.startListening
2017-07-20 12:52:44 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:52:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on star,ting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:db1fd271-cc2a-4c99-b0f9-4a138d639565
ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:52:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9749BEAA-3E3A-45D7-9075-645C99E7D51C
2017-07-20 1,2:52:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:52:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1136B49E-97B2-4E22-AC90-4A914404E861
[ThaliCore] Browser.startListening
2017-07-20 12:52:47 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:52:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:52:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"668195C4-AF2F-4CED-8392-5A206791E4AB","generation":0}'
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 668195C4-AF2F-4CED-8392-5A206791E4AB (syncValue: uhRNXQCLKbleHvZwjLrx67WJAqCmG8Pc)'
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752
[ThaliCore] Advertiser: session connected Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9749BEAA-3E3A-45D7-9075-645C99E7D51C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"69525797-BA3F-4E13-AF0F-E86172E8CB6E","generation":0}'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","generation":0}'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:52:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752
,[ThaliCore] Session.session(_:peer:didChange:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752
[ThaliCore] Session.startOutputStream(with:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [3, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,8195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,68195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
[ThaliCore] Advertiser: session connected Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,8195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,68195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
[ThaliCore] Session.startOutputStream(with:) peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 11, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:66,8195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "668195C4-AF2F-4CED-8392-5A206791E4AB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uhRNXQCLKbleHvZwjLrx67WJAqCmG8Pc","error":"Peer is unavailable","portNumber":null}'
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uhRNXQCLKbleHvZwjLrx67WJAqCmG8Pc', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"668195C4-AF2F-4CED-8392-5A206791E4AB","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:52:56 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-20 12:52:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"668195C4-AF2F-4CED-8392-5A206791E4A,B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:52:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 69525797-BA3F-4E13-AF0F-E86172E8CB6E (syncValue: EXXpU0mA1Wipx0wNrtCB4SURfiseoVkE)'
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] Session.deinit peer:668195C4-AF2F-4CED-8392-5A206791E4AB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:52:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54764
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EXXpU0mA1Wipx0wNrtCB4SURfiseoVkE","error":null,"portNumber":54764}'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EXXpU0mA1Wipx0wNrtCB4SURfiseoVkE', error: 'null', listeningPort: '54764''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
,ok 145 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0) found active relay
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ipVJ0Z61VaL8ST80eQSUsiEVLmQv0tx5","error":null,"portNumber":54764}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69525797-BA3F-4E13-AF0F-E86172E8CB6E", generation: 0) found active relay
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WYzSrXE8mO0wpDfroHoE9WFqrNcUpa7w","error":null,"portNumber":54764}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-07-20 12:52:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-07-20 12:52:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with ta,rget ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore,] VirtualSocket.closeStreams() vsID:12
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] Advertiser.stopAdvertising() peerID:9749BEAA-3E3A-45D7-9075-645C99E7D51C
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disco,nnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:12 [3, 11, 13]
,[ThaliCore] BrowserManager.disconnect peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54764
,[ThaliCore] Session.disconnect() peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [3, 11]
,[ThaliCore] Session.session(_:peer:didChange:) peer:62FE16BE-6755-4C3F-A02A-81A70E4E8752 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9749BEAA-3E3A-45D7-9075-645C99E7D51C", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
,[ThaliCore] Session.deinit peer:69525797-BA3F-4E13-AF0F-E86172E8CB6E:0
[ThaliCore] BrowserRelay.deinit
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:0E1F30A8-C3B2-42BD-9077-9FCEA13A0A19
[ThaliCore] AdvertiserRelay.deinit
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:52:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:52:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-20 12:52:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-20 12:53:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:01 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-20 12:53:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-20 12:53:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54767'
ok 151 Should throw
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54769'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'listening 54772'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:03 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 54776'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
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
2017-07-20 12:53:04 - DEBUG createNativeListener: 'listening 54781'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:04 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 12:53:04 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
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
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54785'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54789'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'listening 54793'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-20 12:53:05 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'listening 54797'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-20 12:53:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
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
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
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
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
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
,2017-07-20 12:53:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54849'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'listening 54853'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-20 12:53:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:08 - DEBUG createNativeListener: 'listening 54856'
ok 198 port must be in range
,# teardown
,2017-07-20 12:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:08 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54857'
ok 199 second start should return same port
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'listening 54859'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-20 12:53:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:09 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-20 12:53:09 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 54861
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:35100B8F-5608-4D74-85AC-379CF9FF5614
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:13134C84-C172-40B2-A179-A5442E4B59D5
[ThaliCore] Browser.startListening
,2017-07-20 12:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7EACCE85-5177-40E5-B094-99AE50B25DB4 (syncValue: 7JyMfKXojXoyCMVrHfVL57zSFs1FjMbN)'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E6222F0B-BC09-4C60-88EE-3F2C1C1244C7","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","generation":0}'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35100B8F-5608-4D74-85AC-379CF9FF5614:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,ACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7EACCE85-5177-40E5-B094-99AE50B25DB4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7JyMfKXojXoyCMVrHfVL57zSFs1FjMbN","error":"Peer is unavailable",,"portNumber":null}'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7JyMfKXojXoyCMVrHfVL57zSFs1FjMbN', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7EACCE85-5177-40E5-B094-99AE50B25DB4","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E6222F0B-BC09-4C60-88EE-3F2C1C1244C7 (syncValue: yjZIGsKBssaXn8LMJjfnNUA,OtEfFezRI)'
2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E6222F0B-BC09-4C60-88EE-3F2C1,C1244C7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-20 12:53:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7EACCE85-5177-40E5-B094-99AE50B25DB4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170
[ThaliCore] Advertiser: session connected Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E6222F0B-BC09-4C60-88EE-3F2C1C1244C7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54871
2017-07-20 12:53:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yjZIGsKBssaXn8LMJjfnNUAOtEfFezRI",,"error":null,"portNumber":54871}'
2017-07-20 12:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yjZIGsKBssaXn8LMJjfnNUAOtEfFezRI', error: 'null', listeningPort: '54871''
,ok 212 should be equal
,2017-07-20 12:53:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA32759D-73B0-4139-BC54-9CBBA9318A85 (syncValue: ZMTh7cxTRySiErshhh20xsOTz3mdYssE)'
,2017-07-20 12:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
[ThaliCore] Advertiser: session connected Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170
,[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54875
2017-07-20 12:53:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZMTh7cxTRySiErshhh20xsOTz3mdYssE",,"error":null,"portNumber":54875}'
2017-07-20 12:53:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZMTh7cxTRySiErshhh20xsOTz3mdYssE', error: 'null', listeningPort: '54875''
,ok 213 should be equal
# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 ,12:53:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:35100B8F-5608-4D74-85AC-3,79CF9FF5614
2017-07-20 12:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54871
[ThaliCore] Sessi,on.disconnect() peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:E6222F0B-BC09-4C60-88EE-3F2C1C1244C7:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:EA32759D-73B0-4139-BC54-9CBBA9318A85
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54875
,[ThaliCore] Session.disconnect() peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42EF0320-C77A-4BB7-BF53-E9CA3636A170 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "35100B8F-5608-4D74-85AC-379CF9FF5614", generation: 0)
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
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
,[ThaliCore] Session.deinit peer:DDC6342C-BEC8-4018-A009-92C5CCAD5617
,# Multiple local http requests
,listening on 54877
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:53:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Me,thod peerAvailabilityChanged registered to native'
2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2AD1575A-57BF-49EF-A14E-3BCF4FE28514
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C78FA2B1-F11B-457E-BD91-68723D2A2024
[ThaliCore] Browser.startListening
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","generation":0}'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EA32759D-73B0-4139-BC54-9CBBA9318A85 (syncValue: HtEG3BBrzdvzFAKUs7VckYi5b0dxfjpi)'
,2017-07-20 12:53:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88535592-00DC-406A-B6E1-682309662B75:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88535592-00DC-406A-B6E1-682309662B75","generation":0}'
2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-20 12:53:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2AD1575A-57BF-49EF-A14E-3BCF4FE28514:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6
[ThaliCore] Advertiser: session connected Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,A32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EA32759D-73B0-4139-BC54-9CBBA9318A85", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HtEG3BBrzdvzFAKUs7VckYi5b0dxfjpi","error":"Peer is unavailable","portNumber":null}'
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HtEG3BBrzdvzFAKUs7VckYi5b0dxfjpi', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EA32759D-73B0-4139-BC54-9CBBA9318A85","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D1F70EEB-FC68-4F13-8138-43E08E22C687 (syncValue: b6pmWPtvijZoiOkync4jL8IPb2DxqR1p)'
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EA32759D-73B0-4139-BC54-9CBBA9318A85:0
[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
[ThaliCore] Advertiser: session connected Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54894
,2017-07-20 12:53:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b6pmWPtvijZoiOkync4jL8IPb2DxqR1p","error":null,"portNumber":54894}'
,2017-07-20 12:53:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b6pmWPtvijZoiOkync4jL8IPb2DxqR1p', error: 'null', listeningPort: '54894''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-20 12:53:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88535592-00DC-406A-B6E1-682309662B75 (syncValue: DgSKlbMp84vRabcGP0H3U0w5fntYzJYr)'
,2017-07-20 12:53:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88535592-00DC-406A-B6E1-682309662B75:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88535592-00DC-406A-B6E1-682309662B75:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88535592-00DC-406A-B6E1-682309662B75:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88535592-00DC-406A-B6E1-682309662B75:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "88535592-00DC-406A-B6E1-682309662B75", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54899
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DgSKlbMp84vRabcGP0H3U0w5fntYzJYr","error":null,"portNumber":54899}'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DgSKlbMp84vRabcGP0H3U0w5fntYzJYr', error: 'null', listeningPort: '54899''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2AD1575A-57BF-,49EF-A14E-3BCF4FE28514
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D1F70EEB-FC68-4F13-8138-43E08E22C687
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54894
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:88535592-00DC-406A-B6E1-682309662B75
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54899
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:88535592-00DC-406A-B6E1-682309662B75:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0F9F4E1-39FE-4678-A72A-5F221C9E91B6 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "2AD1575A-57BF-49EF-A14E-3BCF4FE28514", generation: 0)
,[ThaliCore] Session.deinit peer:88535592-00DC-406A-B6E1-682309662B75:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:53:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b6pmWPtvijZoiOkync4jL8IPb2DxqR1p","error":"Session disconnected","portNumber":null}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-20 12:53:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,[ThaliCore] Session.deinit peer:C1F68FDC-CD8C-4E49-968F-CF634AF525BE
[ThaliCore] Session.deinit peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserRelay.deinit
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'listening 54903'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
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
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 54904'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:088B5C0E-FBDE-4C82-8443-F031A6719FEF
[ThaliCore] Browser.startListening
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
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
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'listening 54905'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE
,2017-07-20 12:53:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE
[ThaliCore] Advertiser.stopAdvertising() peerID:BF7BB9D8-D01C-43AF-B940-D85EDA6A6FBE
2017-07-20 12:53:48 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-20 12:53:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 237 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'listening 54908'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-20 12:53:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 243 specific error expected
,# teardown
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 54909'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8507ED3C-FA81-48BA-926A-76C765A68014
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59833A65-6B72-4C35-89E0-69C1A8C0D819", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:59833A65-6B72-4C35-89E0-69C1A8C0D819
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:59833A65-6B72-4C35-89E0-69C1A8C0D819
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
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'listening 54912'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73D03495-8B70-4055-8148-39A619F6084C
,[ThaliCore] Browser.startListening
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: ,0)
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CE716E4B-21CC-4A28-9A81-56E68637F450", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CE716E4B-21CC-4A28-9A81-56E68637F450
2017-07-20 1,2:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
,ok 247 TCP Servers Manager doesn't exists
,# teardown
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}]'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}'
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:53:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CE716E4B-21CC-4A28-9A81-56E68637F450
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 248 must be stopped
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
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'listening 54914'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D517DE0C-55DD-4876-9827-676F016810B1
[ThaliCore] Browser.startListening
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5B8BD19E-48BF-4999-8DE9-2B96D76BEDD6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5B8BD19E-48BF-4999-8DE9-2B96D76BEDD6
2017-07-20 12:53:52 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5B8BD19E-48BF-4999-8DE9-2B96D76BEDD6
,2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:53:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20, 12:53:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
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
,ok 252 must be stopped
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
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-20 12:53:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:54 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
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
,2017-07-20 12:53:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-20 12:53:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:55 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
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
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-20 12:53:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-20 12:53:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:53:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:53:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 268 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:53:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-20 12:53:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54917'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A2A8C674-3E55-467E-BE48-59BA7C52AC72
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54918'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C26FC5B4-EEA6-4A1C-928F-98F637D313A5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C26FC5B4-EEA6-4A1C-928F-98F637D313A5
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-20 12:53:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C26FC5B4-EEA6-4A1C-928F-98F637D313A5
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:53:58 - DEBUG thaliMobileNativeWrapper: 'listening 54920'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:53:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
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
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'listening 54921'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06DD18E4-4822-46C3-AF7C-9C71035F1623
[ThaliCore] Browser.st,artListening
2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7AADFB43-B853-44C0-98D2-245C652B2C04", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,7AADFB43-B853-44C0-98D2-245C652B2C04
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:53:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:53:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D1F70EEB-FC68-4F13-8138-43E08E22C687:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D1F70EEB-FC68-4F13-8138-43E08E22C687", generation: 0)
2017-07-20 12:53:59 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}]'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","generation":0}'
,2017-07-20 12:53:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 279 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:7AADFB43-B853-44C0-98D2-245C652B2C04
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-20 12:54:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-20 12:54:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 282 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:01 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-20 12:54:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:02 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'listening 54923'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7054CC02-4F35-4202-9635-D1C4F6D139FE
,[ThaliCore] Browser.startListening
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "236824DA-F1E1-4D80-B7AF-2C19AE7BC695", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:236824DA-F1E1-4D80-B7AF-2C19AE7BC695
,2017-07-20 12:54:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-20 12:54:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:54:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
2017-07-20 12:54:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADB21495-5A54-49DC-88F8-51FC343DC59F:0
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAE,A6FBCB","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADB21495-5A54-49DC-88F8-51FC343DC59F", generation: 0)
2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2248883,5-A637-4241-BF70-B8FAAEA6FBCB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 22488835-A637-4241-BF70-B8FAAEA6FBCB (syncValue: Wie5YwFH66EIShCgWLYTWLvKUSth95Mz)'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","generation":0}]'
2017-07-20 12:54:03 - DEBUG thaliMob,ileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","generation":0}'
,2017-07-20 12:54:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:54:03 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:54:03 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:236824DA-F1E1-4D80-B7AF-2C19AE7BC695:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "236824DA-F1E1-4D80-B7AF-2C19AE7BC695", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54926
,2017-07-20 12:54:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Wie5YwFH66EIShCgWLYTWLvKUSth95Mz","error":null,"portNumber":54926}'
,2017-07-20 12:54:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Wie5YwFH66EIShCgWLYTWLvKUSth95Mz', error: 'null', listeningPort: '54926''
,2017-07-20 12:54:06 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [3, 11, 14]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:07 - DEBUG testUtils: 'Got response data'
2017-07-20 12:54:07 - DEBUG testUtils: 'Got end'
,ok 285 response body should match testData
ok 286 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:236824DA-F1E1-4D80-B7AF-2C19AE7BC695
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-20 12:54:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:22488835-A637-4241-BF70-B8FAAEA6FBCB
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54926
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] Session.disconnect() peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:14 [3, 11]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-20 12:54:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-20 12:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:12 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-20 12:54:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-20 12:54:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-20 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D1F70EEB-FC68-4F13-8138-43E08E22C687","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20, 12:54:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-20 12:54:12 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ADB21495-5A54-49DC-88F8-51FC343DC59F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 294 error should be null
,ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 297 specific error should be returned
,# teardown
,ok 298 error should be null
,ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'listening 54928'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
,ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'listening 54929'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:14FF9748-1361-42B2-B408-1C2AD948F329
[ThaliCore] Browser.st,artListening
2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 308 error should be null
ok 309 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
,ok 311 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22488835-A637-4241-BF70-B8FAAEA6FBCB:0
# teardown
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22488835-A637-4241-BF70-B8FAAEA6FBCB", generation: 0)
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}]'
2017-07-20 12:54:13 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","generation":0}'
,2017-07-20 12:54:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:54:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"22488835-A637-4241-BF70-B8FAAEA6FBCB","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Received state ({"discoveryAc,tive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActi,v,e":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'listening 54930'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35ECF7D3-AA21-49E4-B893-842F33395157", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:35ECF7D3-AA21-49E4-B893-842F33395157
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
,ok 316 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35ECF7D3-AA21-49E4-B893-842F33395157", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:35ECF7D3-AA21-49E4-B893-842F33395157
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
,ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:35ECF7D3-AA21-49E4-B893-842F33395157
,[ThaliCore] Advertiser.stopAdvertising() peerID:35ECF7D3-AA21-49E4-B893-842F33395157
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:14 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'listening 54933'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-20 12:54:15 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
,ok 330 native router should be bad
,# teardown
,ok 331 error should be null
,ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'listening 54934'
,ok 334 first call should succeed
,ok 335 first call should succeed
,ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
,ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-20 12:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1df4657-7644-4d56-a1ff-92c9b9b9d9f5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 346 should be calle,d once
,ok 347 should not have been called more than once
,# teardown
,2017-07-20 12:54:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f1df4657-7644-4d56-a1ff-92c9b9b9d9f5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# can get the network status
,ok 351 network status should have certain non-empty properties
,# teardown
,ok 352 error should be null
ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 355 we have not added peer to the cache yet
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7c670178-be65-4667-b2f6-8b50bf536ce4","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 356 peer should be available
ok 357 cache contains native peer
2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7c670178-be65-4667-b2f6-8b50bf536ce4","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 358 peer should be unavailable
ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
,ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
,2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"686ee38d-5752-4f97-a3fc-42d49971e5b9","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 364 peer should be available
,ok 365 cache contains wifi peer
,2017-07-20 12:54:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"686ee38d-5752-4f97-a3fc-42d49971e5b9","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 366 peer should be unavailable
,ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
,ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7606dfdf-3dec-4957-b699-12e656693c8e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 371 first peer is available
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1b5cd3a6-39f4-47b3-840f-2787a756b064","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 372 second peer is available
,ok 373 first and second peers are different
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7606dfdf-3dec-4957-b699-12e656693c8e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1b5cd3a6-39f4-47b3-840f-2787a756b064","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
,ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b7aa8d8d-9490-4687-994a-7e4eda0229d8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 378 peer is available
,# teardown
,2017-07-20 12:54:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b7aa8d8d-9490-4687-994a-7e4eda0229d8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-20 12:54:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-20 12:54:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83b9be78-e63b-4138-9a8d-64fbc56db271","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 388 peer should be available
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83b9be78-e63b-4138-9a8d-64fbc56db271","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 389 peer should be available
,ok 390 should store correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83b9be78-e63b-4138-9a8d-64fbc56db271","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
,ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 54935'
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c52932ab-e2b9-47cc-aa8c-6fc004a52024","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c52932ab-e2b9-47cc-aa8c-6fc004a52024","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,# teardown
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c52932ab-e2b9-47cc-aa8c-6fc004a52024","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-20 12:54:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 398 error should be null
ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-20 12:54:19 - DEBUG thaliMobileNativeWrapper: 'listening 54936'
,2017-07-20 12:54:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"41f4b687-5129-41f2-85b2-af7e7477dec2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 401 discovered available peer
,ok 402 peer is available
,# teardown
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"41f4b687-5129-41f2-85b2-af7e7477dec2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
,ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ea81d06f-b213-4646-bd17-77327dcdfeaa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 406 peer should be ,available
2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ea81d06f-b213-4646-bd17-77327dcdfeaa","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 407 peer, should be unavailable
ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
,ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 54937'
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1a1cf507-18e1-495a-9dfd-d93c8b71a150","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 first peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6af41d83-f5c1-4579-9ff6-02d91f371cf5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 413 second peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6af41d83-f5c1-4579-9ff6-02d91f371cf5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6af41d83-f5c1-4579-9ff6-02d91f371cf5","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 we found peer again
,ok 417 it was wifi peer
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6af41d83-f5c1-4579-9ff6-02d91f371cf5","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 418 peer became unavailable
,ok 419 it was wifi peer
,# teardown
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1a1cf507-18e1-495a-9dfd-d93c8b71a150","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-20 12:54:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
,ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-20 12:54:20 - DEBUG thaliMobileNativeWrapper: 'listening 54938'
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c1a5c21a-a093-4ea3-8663-0cdd9ba5ad44","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 426 first peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7aed9b5d-52b0-4679-b080-6957fe6ea3ba","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 427 second peer is expected to be available
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c1a5c21a-a093-4ea3-8663-0cdd9ba5ad44","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 428 peer became unavailable
,2017-07-20 12:54:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7aed9b5d-52b0-4679-b080-6957fe6ea3ba","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-20 12:54:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-20 12:54:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
,ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-20 12:54:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
,ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f14b7a-6b2a-41de-9ad0-69b5d1d71283","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 439 peer discovered first time does not have new address
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f14b7a-6b2a-41de-9ad0-69b5d1d71283","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 440 address has not been changed
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f14b7a-6b2a-41de-9ad0-69b5d1d71283","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 441 new port handled correctly
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f14b7a-6b2a-41de-9ad0-69b5d1d71283","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 442 new host handled correctly
,2017-07-20 12:54:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a6f14b7a-6b2a-41de-9ad0-69b5d1d71283","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 443 newAddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 450 NOT IMPLEMENTED # SKIP
,# teardown
,ok 451 error should be null
ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-20 12:54:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
,ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-20 12:54:23 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
,ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 464 contains expected properties
,ok 465 the same hostAddress
,ok 466 the same portNumber
,# teardown
,2017-07-20 12:54:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 470 contains expected properties
ok 471 the same hos,tAddress
ok 472 the same portNumber
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 54939'
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3916eb5a-cbc9-405b-ace8-bb9ab69bdc3d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 476 Got specific error message
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3916eb5a-cbc9-405b-ace8-bb9ab69bdc3d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'listening 54940'
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d91cbe26-5db3-4afb-b28d-d66d433e19f5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:d91cbe26-5db3-4afb-b28d-d66d433e19f5
,ok 480 native wrapper `disconnect` called once
,ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-20 12:54:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d91cbe26-5db3-4afb-b28d-d66d433e19f5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
,ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-20 12:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
,ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-20 12:54:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'listening 54941'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA4DCDF2-58D7-4F35-BC8D-FFD9C94C4F6C
,[ThaliCore] Browser.startListening
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d1138f06-4975-4aeb-965f-bb74f5657676","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0e0e0d6a-f063-42e5-9197-572f5871ea8c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d1138f06-4975-4aeb-965f-bb74f5657676","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0e0e0d6a-f063-42e5-9197-572f5871ea8c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-20 12:54:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
,ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'listening 54942'
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"760de4c7-df9b-4f69-a6a7-3e2ca9b2f3fa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 1
,ok 515 2
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8b34a6d2-690b-4484-bc2a-ded2fd583ae0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"760de4c7-df9b-4f69-a6a7-3e2ca9b2f3fa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8b34a6d2-690b-4484-bc2a-ded2fd583ae0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-20 12:54:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-20 12:54:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
,ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-20 12:54:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
,ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'listening 54943'
ok 522 error should be null
ok 523 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90045F83-13E2-42E6-8B7E-91,38CCA74D8C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:90045F83-13E2-42E6-8B7E-9138CCA74D8C
2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 524 error should be null
ok 525 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1246A4ED-9F2C-4734-9B99-1004F24688F4
[ThaliCore] Browser.startListening
,2017-07-20 12:54:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 526 error should be null
ok 527 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}]'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0C355728-450D-4AE9-898C-AC65C78ACABC (syncValue: 0)'
,2017-07-20 12:54:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] Advertiser: session connected Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:90045F83-13E2-42E6-8B7E-9138CCA74D8C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
,2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","generation":0}]'
2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","generation":0}'
,2017-07-20 12:54:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:54:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54946
2017-07-20 12:54:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":54946}'
,2017-07-20 12:54:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 56CC6A57-6C82-4856-8C19-30E36C8EC7B7 (syncValue: 1)'
2017-07-20 12:54:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] Session.startOutputStream(with:) peer:B9F80EA8-9BA3-48E1-B243-F35074902EC5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [3, 11, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 11, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] Advertiser: session connected Peer(uuid: "90045F83-13E2-42E6-8B7E-9138CCA74D8C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2 state: notConnected -> connecting
2017-07-20 12:54:32 - DEBUG testUtils: 'Got response data'
2017-07-20 12:54:32 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "56CC6A57-6C82-4856-8C19-30E36C8EC7B7", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54951
2017-07-20 12:54:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":54951}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:56CC6A57-6C82-4856-8C19-30E36C8EC7B7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 11, 15, 16, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:54:34 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:34 - DEBUG testUtils: 'Got end'
,ok 528 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
,[ThaliCore] Session.session(_:peer:didChange:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] Session.startOutputStream(with:) peer:1BD4172D-D885-413A-A5F1-211C4F0B11F2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [3, 11, 15, 16, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [3, 11, 15, 16, 18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didS,ocketDisconnectHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54946
[ThaliCore] Session.disconnect() peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:0C355728-450D-4AE9-898C-AC65C78ACABC:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0C355728-450D-4AE9-898C-AC65C78ACABC", generation: 0) relay removed
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}]'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","generation":0}'
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-20 12:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0C355728-450D-4AE9-898C-AC65C78ACABC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-20 12:54:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"56CC6A57-6C82-4856-8C19-30E36C8EC7B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:90045F83-13E2-42E6-8B7E-9138CCA74D8C
2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingA,ctive":false}'
2017-07-20 12:54:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017,-07-20 12:54:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-20 12:54:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-20 12:54:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-20 12:54:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] V,i,ok 529 error should be null
ok 530 error should be null
,rtualSocket.closeStreams() vsID:18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,# setup
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [3, 11, 16, 18]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [3, 11, 16]
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-20 12:54:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 534 getPeerIdentifier
ok 535 getConnectionType
ok 536 getActionType
ok 537 getActionState
ok 538 getPskIdentity
ok 539 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 540 initial state
,ok 541 after start
,2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-20 12:54:39 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 544 clean kill
,ok 545 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 546 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 547 forever agent should have it's own destroy method
,ok 548 agent's destroy should be called
,ok 549 agent's destroy should not be called again
ok 550 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 551 Entry counter must be 1
,ok 552 Entry exists
ok 553 Size must be 1
,ok 554 Entry counter must be 2
,ok 555 Entry exists
,ok 556 Size must be 2
,ok 557 Entry counter must be 1
,ok 558 Entry exists
,ok 559 Size must be 3
,ok 560 Entry counter must be 2
,ok 561 Entry exists
,ok 562 Size must be 4
,ok 563 Entry 1_1 should not be found
ok 564 Entry 1_1 does not exist
,ok 565 Size must be 3
,ok 566 Entry 1_2 should not be found
,ok 567 Entry 1_2 does not exist
,ok 568 Size must be 2
,ok 569 should be equal
,ok 570 Entry 2_1 should not be found
,ok 571 Entry 2_2 should not be found
,ok 572 Entry 2_1 does not exist
,ok 573 Entry 2_2 does not exist
,ok 574 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 575 Size must be100
,ok 576 Entries between 20 and MAXSIZE + 20 should exist
,ok 577 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 578 Entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 581 WAITING state entry should not be removed
,ok 582 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 583 Size should be MAXSIZE
,ok 584 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 585 Kill should be called once
,ok 586 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 587 is an agent
ok 588 enqueue is fine
ok 589 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 590 is an agent
ok 591 first enqueue is fine
ok 592 is an agent
ok 593 second enqueue is fine
ok 594 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
,ok 597 good enqueue
,ok 598 Identity should match
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got response data'
,2017-07-20 12:54:44 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-20 12:54:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 601 is an agent
,ok 602 enqueue worked
,ok 603 is an agent
,ok 604 enqueue 2 worked
,ok 605 enqueue is not available when stopped
,ok 606 start action is killed
,ok 607 killed action is still killed
,ok 608 enqueued action when stopped is killed
,ok 609 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 610 good start
,ok 611 good enqueue
,ok 612 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 613 null arg
ok 614 wrong arg type
ok 615 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 616 good enqueue
ok 617 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 618 good enqueue
,ok 619 2nd good enqueue
,ok 620 we are in the pool
,ok 621 We are out of the pool
,ok 622 Action was killed
,ok 623 The original kill was called too
,ok 624 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 625 good enqueue
ok 626 first kill
ok 627 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 628 1st good enqueue
ok 629 2nd good enqueue
ok 630 1st action is in the pool
ok 631 2nd action is in the pool
ok 632 1st action is out of the pool
ok 633 2st action is out of the pool
,ok 634 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
,ok 636 Start should not be called
,ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-20 12:54:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 12:54:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 638 Got right error
,ok 639 Start should not be called
,ok 640 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 641 Got null
2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
,ok 642 is an agent
2017-07-20 12:54:48 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 644 Got Null
ok 645 Got another null
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 646 is an agent
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
,2017-07-20 12:54:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
,ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 651 should have gotten null
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 652 Should have stopped nicely
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 653 Still looking for null
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 654 Yup, another null
,ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 656 Null 1
,ok 657 (unnamed assert)
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 658 is an agent
,ok 659 Null 3
,ok 660 Replication not yet called
,ok 661 Notification 2 not yet called
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 662 is an agent
,ok 663 Notification went first
,ok 664 Notification 2 not called yet
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 665 is an agent
,ok 666 Notification finished
,ok 667 Replication finished
,2017-07-20 12:54:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 First does not throw
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 670 is an agent
,ok 671 Second does not throw
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-20 12:54:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 672 is an agent
,ok 673 first ok
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 674 is an agent
ok 675 second ok
ok 676 third ok
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned, successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-20 12:54:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
,# setup
,# Client to server request coordinated
,2017-07-20 12:54:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-20 12:54:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 677 peerIdentifier should match
,ok 678 generation should match
,ok 679 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 680 good beacon
,ok 681 good preAmble
,ok 682 public keys match!
,ok 683 must return null after successful call
,ok 684 Once start returns the action should be in KILLED state
,# teardown
,2017-07-20 12:54:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-20 12:54:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-20 12:54:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
,ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
ok 688 correct error message
,# teardown
,2017-07-20 12:54:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
,ok 693 Start after killed
,# teardown
,2017-07-20 12:54:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-20 12:54:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
ok 697 must return null after successful kill
,# teardown
,2017-07-20 12:54:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-20 12:55:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-20 12:55:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 700 Should be NETWORK_PROBLEM caused closing server socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-20 12:55:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 704 publicKeysToNotify cannot be null
,ok 705 ecdh for local device cannot be null
,ok 706 milliseconds cannot be less than 0
,ok 707 milliseconds cannot be 0
,ok 708 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 709 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 710 should be equal
ok 711 should be equal
,ok 712 (unnamed assert)
,ok 713 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 714 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 715 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 716 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 717 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 719 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-20 12:55:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 721 should be equal
ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 723 right number of calls to address book
ok 724 good preAmble
,ok 725 good unencryptedKeyId
,ok 726 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 727 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 728 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 729 Matching numbers
,ok 730 We have an entry!
,ok 731 keys match
,ok 732 secrets match
,ok 733 We have an entry!
,ok 734 keys match
,ok 735 secrets match
,ok 736 We have an entry!
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 739 Streams have same length
,ok 740 matching size
,ok 741 keys match
,ok 742 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 743 should be equal
,ok 744 peerDictionalty contains 2 peers
,ok 745 bluetooth peer's notification has correct connection type
,ok 746 tcp peer's notification has correct connection type
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
2017-07-20 12:55:15 - WARN thaliNotificationClient: 'peer is not available'
ok 748 notification peer dictionary does not contain any peers
,2017-07-20 12:55:15 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-20 12:55:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-20 12:55:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
,ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-20 12:55:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-20 12:55:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-20 12:55:20 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-20 12:55:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-20 12:55:23 - WARN thaliNotificationClient: 'peer is not available'
2017-07-20 12:55:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
,# teardown
,2017-07-20 12:55:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
ok 773 peer state should be RESOLVED
,# teardown
,2017-07-20 12:55:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-20 12:55:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 774 First action failed
,ok 775 second action killed
# teardown
,2017-07-20 12:55:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
,ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-20 12:55:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
,# teardown
,2017-07-20 12:55:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-20 12:55:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-20 12:55:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-20 12:55:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 799 no error
,ok 800 should be 200
,ok 801 should be equal
,ok 802 should be equal
,ok 803 (unnamed assert)
,ok 804 no error
ok 805 should be 204
,# teardown
,2017-07-20 12:55:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
ok 807 should be 204
,# teardown
,2017-07-20 12:55:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
,# teardown
,2017-07-20 12:55:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
,ok 810 not equal connection type
,ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-20 12:55:37 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 814 First start and on called correctly
,ok 815 First stop and removeListener called correctly
,ok 816 first action kill called
,ok 817 second action kill called
,ok 818 first cleared dictionary
,ok 819 first cleared pool
,ok 820 second cleared dictionary
,ok 821 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 822 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-20 12:55:38 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 823 listener has been set
,ok 824 peer dictionary has expected number of entries
,ok 825 Dictionary and pool have same action
,ok 826 ads match
,ok 827 PouchDB matches
,ok 828 DB Names match
,ok 829 public keys match
,ok 830 peer dictionary has expected number of entries
,ok 831 Dictionary and pool have same action
,ok 832 ads match
,ok 833 PouchDB matches
,ok 834 DB Names match
,ok 835 public keys match
,2017-07-20 12:55:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 836 start called once
,ok 837 One entry left
,ok 838 Dictionary and pool have same action
,ok 839 Start never called
,ok 840 Kill called once
,ok 841 no entries left
,ok 842 Third action is dead
,ok 843 peer dictionary has expected number of entries
,ok 844 Dictionary and pool have same action
,ok 845 ads match
,ok 846 PouchDB matches
,ok 847 DB Names match
,ok 848 public keys match
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
,ok 849 right error
,# teardown
,2017-07-20 12:55:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-20 12:55:40 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-20 12:55:41 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-20 12:55:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-20 12:55:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-20 12:55:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-20 12:55:45 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:46 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-20 12:55:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-20 12:55:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
,ok 857 All tests passed!
,# teardown
,2017-07-20 12:55:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-20 12:55:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:55:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-20 12:55:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-20 12:55:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-20 12:55:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-20 12:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 12:56:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 862 action should be killed
,ok 863 Error should be timed out
,# teardown
,2017-07-20 12:56:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-20 12:56:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
ok 866 Same pouchdB
ok 867 same localDbName
ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-20 12:56:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'listening 55079'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:46D52D8C-14C7-4A25-96A4-6F26A0FC8647
[ThaliCore] Browser.startListening
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:22BF9314-137A-449F-AF79-3F7901B86A34
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
2017-07-20 12:56:04 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","generation":0}]'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","generation":0}'
,2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-20 12:56:04 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"96241CD7-C019-4F98-A006-9D7C1BEFED19","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for 96241CD7-C019-4F98-A006-9D7C1BEFED19 (syncValue: 2)'
2017-07-20 12:56:04 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "96241CD7-C019-4F98,-A006-9D7C1BEFED19", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
[ThaliCore] Session.init(session:identifier:connected,:notConnected:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Advertiser: session connected Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0 state: notConnected -> connecting
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","generation":0}]'
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","generation":0}'
,2017-07-20 12:56:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-20 12:56:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39C4BF82-C564-4703-A987-5D9BD291B6A0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:22BF9314-137A-449F-AF79-3F7901B86A34:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "96241CD7-C019-4F98-A006-9D7C1BEFED19", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55082
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":55082}'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 39C4BF82-C564-4703-A987-5D9BD291B6A0 (syncValue: 3)'
,2017-07-20 12:56:07 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 11, 16, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[Thali,Core] Session.init(session:identifier:connected:notConnected:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Advertiser: session connected Peer(uuid: "22BF9314-137A-449F-AF79-3F7901B86A34", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:,)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 11, 16, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [3, 11, 16, 20]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 11, 16, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [3, 11, 16, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-20 12:56:08 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 11, 16, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [3, 11, 16, 20, 21, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [3, 11, 16, 20, 21, 22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,7 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
,[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 29]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
[ThaliCore] Session.startOutputStream(with:) peer:CF92028B-CA40-4A0C-8CE8-852F1C9D561E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
,[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 29, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:29 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96241CD7-C019-4F98-A006-9D7C1BEFED19:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:56:09 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39C4BF82-C564-4703-A987-5D9BD291B6A0", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55099
,2017-07-20 12:56:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":55099}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 33, 34]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 34]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [3, 11, 16, 20, 21, 22, 23, 24, 25, 26, 28, 31, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [3, 11, 16, 20, 21, 23, 24, 25, 26, 28, 31, 35, 36, 37, 38]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [3, 11, 16, 20, 21, 23, 25, 26, 28, 31, 35, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [3, 11, 16, 20, 21, 23, 25, 26, 31, 35, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [3, 11, 16, 20, 21, 23, 26, 31, 35, 36, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.,socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-20 12:56:11 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:21 [3, 11, 16, 20, 23, 26, 31, 35, 36, 37, 38]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:23 [3, 11, 16, 20, 26, 31, 35, 36, 37, 38]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [3, 11, 16, 20, 31, 35, 36, 37, 38]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [3, 11, 16, 20, 35, 36, 37, 38]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [3, 11, 16, 20, 35, 36, 37, 38, 39]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [3, 11, 16, 20, 35, 36, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] Session.startOutputStream(with:) peer:E7774671-D4C9-46DA-83D8-05DEB0050DF8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 11, 16, 20, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 11, 16, 20, 35, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39C4BF82-C564-4703-A987-5D9BD291B6A0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 11, 16, 20, 35, 36, 37, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [3, 11, 16, 20, 35, 36, 37, 38, 39, 40, 41, 43]
,2017-07-20 12:56:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,35
[ThaliCore] VirtualSocket.deinit vsID:35 [3, 11, 16, 20, 36, 37, 38, 39, 40, 41, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnec,ted
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [3, 11, 16, 20, 36, 38, 39, 40, 41, 43]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [3, 11, 16, 20, 36, 38, 39, 40, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [3, 11, 16, 20, 36, 38, 40, 43]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-20 12:56:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-20 12:56:14 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] TCPListener.socketDidDi,s,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:36 [3, 11, 16, 20, 38, 40, 43]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:38 [3,, 11, 16, 20, 40, 43]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.closeStreams() vsID:40
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [3, 11, 16, 20, 43]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [3, 11, 16, 20]
,2017-07-20 12:59:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-20 12:59:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 12:59:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 12:59:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:00:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:00:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:01:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:01:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:02:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:02:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:03:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:03:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:04:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:04:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:05:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:05:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-20 13:06:03 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
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
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-20 13:06:04 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
2017-07-20 13:06:04 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-20 13:06:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 869 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-20 13:06:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:06:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:06:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:07:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:07:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:08:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:08:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-4,14E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-20 13:09:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414,E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-20 13:09:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/445C75A7-CCF3-414E-8D5D-1CB8B153C0C5/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
