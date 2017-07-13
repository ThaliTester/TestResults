#### Test 113351851e5b8da0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/98BD0547-5683-4D17-850F-7B86B7079CAF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/98BD0547-5683-4D17-850F-7B86B7079CAF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50594"
,(lldb)     command script import "/tmp/98BD0547-5683-4D17-850F-7B86B7079CAF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
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
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:28:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7194DA5E-EC68-461F-A5FB-1FA3C18AED7E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7194DA5E-EC68-461F-A5FB-1FA3C18AED7E
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A4C722E-707A-4FEF-B910-FC0B6D29E6D9
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:81CE4455-E151-4AAC-8CCF-3B0375F5F8CB
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "349DDD9D-73AB-4A4D-8DE0-7936432B3253", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:349DDD9D-73AB-4A4D-8DE0-7936432B3253
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:349DDD9D-73AB-4A4D-8DE0-7936432B3253:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "349DDD9D-73AB-4A4D-8DE0-7936432B3253", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 09:28:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.518325984477997
,2017-07-13 09:28:36 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-13 09:28:36 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:349DDD9D-73AB-4A4D-8DE0-7936432B3253:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "349DDD9D-73AB-4A4D-8DE0-7936432B3253", generation: 0)
,2017-07-13 09:28:39 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 09:28:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 09:28:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 09:28:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 09:28:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 09:28:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 09:28:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 09:28:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 09:28:44 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 09:28:44 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 09:28:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:24 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 09:29:24 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 09:29:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-13 09:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 09:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
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
,ok 5 should be equal
,ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
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
,ok 51 participant data matches
,ok 52 test participant has uuid
,ok 53 participant data matches
,ok 54 test participant has uuid
,ok 55 participant data matches
,ok 56 own UUID is found from the participants list
,# teardown
,# setup
,# Correctly parses/stringifies USN
,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-13 09:29:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 09:29:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4956EEE5-18E6-438A-9DE0-32BB7ADDEA1A
,[ThaliCore] Browser.startListening
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F82CDD98-FDEE-4420-8D3E-50C963268FC1
[ThaliCore] Browser.startListening
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
,2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C4B0DF17-9C64-46A3-B086-B37ADC315CCF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C4B0DF17-9C64-46A3-B086-B37ADC315CCF
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUp,date (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FC51F34D-03CB-45A7-A874-5D0CCAADC7C4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FC51F34D-03CB-45A7-A874-5D0CCAADC7C4
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FC51F34D-03CB-45A7-A874-5D0CCAADC7C4", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:FC51F34D-03CB-45A7-A874-5D0CCAADC7C4
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:,29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Sho,u,ld be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "70431CAA-E8FA-425D-A5B4-088C35618AEB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:70431CAA-E8FA-425D-A5B4-088C35618AEB
2017-07-13 09:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:47, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:98560089-3FF9-4C80-8779-800CEC9E0023
[ThaliCore] Browser.startListening
2017-07-13 09:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-13 09:29:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8CA63532-F679-4683-AE6B-8D8E453DB975:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8CA63532-F679-4683-AE6B-8D8E453DB975", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:70431CAA-E8FA-425D-A5B4-088C35618AEB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "70431CAA-E8FA-425D-A5B4-088C35618AEB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3893778D-A108-4402-9972-01688608596C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3893778D-A108-4402-9972-01688608596C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:29:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:29:48 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndList,e,ning in teardown
,# setup
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BCA5C49A-1B68-480D-9939-27D9A9088049", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BCA5C49A-1B68-480D-9939-27D9A9088049
,2017-07-13 09:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1976180A-C610-46F2-A8BD-B82D54205B98
[ThaliCore] Browser.startListening
,2017-07-13 09:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
2017-07-13 09:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","generation":0}'
,2017-07-13 09:30:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 001FF42C-B081-4001-A9F2-6BB3561908F9 (syncValue: PbmceiKbN6o8MiFz0r7YijwnFFcISwmH)'
,2017-07-13 09:30:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DEB213F8-7240-427B-A28E-AEECE8ABFAF9","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCA5C49A-1B68-480D-9939-27D9A9088049:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCA5C49A-1B68-480D-9939-27D9A9088049", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49917
2017-07-13 09:30:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PbmceiKbN6o8MiFz0r7YijwnFFcISwmH","error":null,"portN,umber":49917}'
,2017-07-13 09:30:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PbmceiKbN6o8MiFz0r7YijwnFFcISwmH', error: 'null', listeningPort: '49917''
,2017-07-13 09:30:05 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-13 09:30:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,09:30:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 09:30:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:30:05 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:001FF42C-B081-4001-A9F2-6BB3561908F9
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49917
[ThaliCore] Session.disconnect() peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,# setup
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F
2017-07-13 0,9:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:465A0370-AD89-4A3C-B687-7E28BDF9142D
[Tha,liCore] Browser.startListening
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
2017-07-13 09:30:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","generation":0}'
2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 001FF42C-B081-4001-A9F2-6BB3561908F9, (syncValue: 8eEXlt5qT9RdHqxR1Z1FjT39yAiOQLrk)'
2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
2017-07-13 09:30:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", genera,tion: 0)
2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8eEXlt5qT9RdHqxR1Z1FjT39yAiOQLrk","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '8eEXlt5qT9RdHqxR1Z1FjT39yAiOQLrk', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7013A18A-B3A3-429C-A561-7CE2E3F66643 (syncValue: Tl5ejk1qDCyph7nSyaCxEMMie8Myrjsq)'
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49922
,2017-07-13 09:30:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Tl5ejk1qDCyph7nSyaCxEMMie8Myrjsq","error":null,"portNumber":49922}'
,2017-07-13 09:30:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Tl5ejk1qDCyph7nSyaCxEMMie8Myrjsq', error: 'null', listeningPort: '49922''
,Connecting to the localhost:49922
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
Connected to the localhost:49922
,2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 09:30:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
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
[ThaliCore] BrowserManager.disconnect peer:7013A18A-B3A3-,429C-A561-7CE2E3F66643
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49922
[ThaliCore] Session.disconnect() peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: ",7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,# setup
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] Browser.startListening
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","generation":0}'
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7013A18A-B3A3-429C-A561-7CE2E3F66643, (syncValue: U7MGEZrHbdAPxOYcppHFQi3kf9eLA90I)'
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
2017-07-13 09:30:19, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] Session.disconnect() peer:7013A18A-B3A,3-429C-A561-7CE2E3F66643:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", genera,tion: 0)
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U7MGEZrHbdAPxOYcppHFQi3kf9eLA90I","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'U7MGEZrHbdAPxOYcppHFQi3kf9eLA90I', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C (syncValue: bjLyGmK,wsDeCLA8Kf2QvGzFGQgK5XAqL)'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Session.disconnect() peer:59CCC3C4-7D7,7-4AA0-85BA-EAC4EC5EC63C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", genera,tion: 0)
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bjLyGmKwsDeCLA8Kf2QvGzFGQgK5XAqL","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'bjLyGmKwsDeCLA8Kf2QvGzFGQgK5XAqL', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0F6381F-42C6-44BA-8B84-8E89DDF7C407 (syncValue: s77KQV4,D18nwm3RuMub3ZKFPMq14x7bS)'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C40,7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[ThaliCore] Advertiser: session connected Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[ThaliCore] Session.startOutputStream(with:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
,[ThaliCore] Session.startOutputStream(with:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[ThaliCore] Session.startOutputStream(with:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received all data: 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[T,haliCore] VirtualSocket exited RunLoop vsID:2
LVhvPdyJwWgHTi6Oz9wpQiCtSxPTjdG5YnU7qUK2FBofUXHsMeg0bxkAQSNOqAKuKH2KdRdL1PoHQgh9'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 09:30:33 - DE,BUG testThaliMobileNative: 'Server data flushed'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.deinit vsID:4 [3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49933
,2017-07-13 09:30:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"s77KQV4D18nwm3RuMub3ZKFPMq14x7bS","error":null,"portNumber":49933}'
,2017-07-13 09:30:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 's77KQV4D18nwm3RuMub3ZKFPMq14x7bS', error: 'null', listeningPort: '49933''
,Connecting to the localhost:49933
,Connecting to the localhost:49933
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
Connecting to the local,host:49933
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,Connected to the localhost:49933
Connected to the localhost:49933
Connected to the localhost:49933
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [5]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, cou,nt:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:6 [5,, 7]
[ThaliCore] VirtualSocket.deinit vsID:5 [7]
,ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 []
,ok 114 got the same data back
,# teardown
,2017-07-13 09:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49933
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:4EBE9E91-311E-4A5C-B78C-30B0C6FA47BD
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:750CF6A3-B1D5-4221-85F0-7689E1747463
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:56E84AF2-239B-4D22-A375-8C1DE6A,B0579
[ThaliCore] Browser.startListening
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
2017-07-13 09:30:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","generation":0}'
2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 272EFB28-A62E-4CC9-815C-88B09C2FD833, (syncValue: izdSb2LayQSY4ey04mxaNEFJ4CwniPBy)'
2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", gen,eration: 0) new relay
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
2017-07-13 09:30:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] Session.disconnect() peer:272EFB28-A62,E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0),
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generati,on: 0)
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"izdSb2LayQSY4ey04mxaNEFJ4CwniPBy","error":"Connection could not be established","portNumber":null}'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'izdSb2LayQSY4ey04mxaNEFJ4CwniPBy', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D0F6381F-42C6-44BA-8B84-8E89DDF7C407 (syncValue: PfEGEXxRwoFmXuQZnGr6UM5T108Tc8Lh)'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Session.disconnect() peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", genera,tion: 0)
2017-07-13 09:30:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PfEGEXxRwoFmXuQZnGr6UM5T108Tc8Lh","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:47 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'PfEGEXxRwoFmXuQZnGr6UM5T108Tc8Lh', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D0F6381F-42C6-44BA-8B84-8E89DDF7C407","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:47 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF (syncValue: UyhbFWzayiesafbGIFJe09A5VIQrXpjh)'
,2017-07-13 09:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49945
2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UyhbFWzayiesafbGIFJe09A5VIQrXpjh",,"error":null,"portNumber":49945}'
2017-07-13 09:30:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UyhbFWzayiesafbGIFJe09A5VIQrXpjh', error: 'null', listeningPort: '49945''
,Connecting to the localhost:49945
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49945
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 09:30:51 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualS,ocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 []
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# teardown
,2017-07-13 09:30:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49945
[ThaliCore] Session.disconnect,() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,# setup
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:731C2C5E-0539-486A-B543-8DB415F54546
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browse,r.init(serviceType:foundPeer:lostPeer:) peer:C984A9A4-86BD-4385-8C66-BA0B6E50204F
[ThaliCore] Browser.startListening
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","generation":0}'
2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF, (syncValue: kwrEXU3kkqdrtCgjMCIVaUQ9S5hRvhQ7)'
2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", gen,eration: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68,E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,2017-07-13 09:30:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0B6584A-55E2-4F22-9640-4ABB1B359C49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", genera,tion: 0)
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kwrEXU3kkqdrtCgjMCIVaUQ9S5hRvhQ7","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'kwrEXU3kkqdrtCgjMCIVaUQ9S5hRvhQ7', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
ifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","pee,rAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:58 - DEBUG thaliMobile,NativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0193AF29-BB70-49A6-9678-9B2D28BC8830 (syncValue: 9iN2Y2JPNtkOG55VZ1g7jWLCUW3U3G3B)'
,2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
[ThaliCore] Advertiser: session connected Peer(uuid: "731,C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3 state: notConne,cted -> connecting
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0193,AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore], TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
,[ThaliCore] Session.session(_:peer:didChange:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3 state: connecting -> connected
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49954
,2017-07-13 09:31:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9iN2Y2JPNtkOG55VZ1g7jWLCUW3U3G3B","error":null,"portNumber":49954}'
,2017-07-13 09:31:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9iN2Y2JPNtkOG55VZ1g7jWLCUW3U3G3B', error: 'null', listeningPort: '49954''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
[ThaliCore] Session.startOutputStream(with:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
Connecting to the localhost:49954
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Connected to the localhost:49954
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [9, 10]
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received (55681 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server received all data: Gh5ikLJfFuNaCqGv8RQilZCercsW5B0RqdfpGwhewNVWafRLaxu2OXcGdq41mkvnaRVF6j7bxzZxVxMEl0uSQhbl8PaM1z1JucBzwDu4T5C1SQP3GpCclKfXPMgg9H4eag9RTE7IhDcQslo3k7r10Rsf24rWpUjSEMAK0JQZanos7J9v0F,ZDhd0SILKicYJQah6Qia5JgpNIiaqQOVXhxV9S3mKEnImCFH4weM5aejCT1Fb81p6OY5hx0F6JPuPNcWW9GDlqmkyRNingvQVZ1049MveIIQ3LsN9fClsZj7UcLRnVnOPFeMzklGhMglNx5yD5OZxreGYpLZ30EYXU3BKP0UUS8fzbilthby5VCcCp5YcmqS2xIEleSt9n3umlPDZlMLUQoElQD2Z7sQ7yLizSu3fcYMDB5VWNt5assDYuhxJfyh,nGgGeOvjVbCg6CAPRqn2GvnTe5Y376lLlNodVxkOPwl3mTUTYlXYvCn4ZnYrvNv7tS1Lri879zVwpNHivnxT9RRUqXyTxvx3kWMDuoo804MGHLO26m1IDPVc2RmYhCmhXJpNlx1A8X3q0q0s8TKTNoyiwOA4kXT7iIflAUjL6n9TgIkCCzF1veUZ48XqDUBlboeYyXjKbySJSWHd9ksnUFvrEv43sma2S0byZLgEJYTV4ZKyi5r3x9iSNFjSdtn2,LeUmBqROYtkXmHGJcSXQQlpo6rJA1IQ27I7x8ig0V6a5WAS6toZ7ghJhpx5FrAJIkagRVfQO8JGAWWKqyVap1M2KdkLM4WOWmnfyLUTAgW6xZfJn44auzX2blfag32OrERt2ocM67GAB7fTa9H581rtrXT1GGBqz3KObye419Sb9xaeeT44EVDfo5U6MLJdbC2kWAL77775Xnn3mKeA641KAW6S2DT5TaLsMihzTfwfEsZmGGZfKNXkLZzJRiBl8,IgXy557PxFqQM9dVYC7hRzDnbyIMnbcGVXDH3XLEbQ7IYKI03uuv2lOQjozzJ0rfD4QFLU7Crs0ow9jy6sN4sZN9oKSGZ0ODn0zIRS57xILDYKj7cH3hWkcJEEDbJ30aGZNIdFHyALKTVyOVuzJTbEzLmFI6FjXjM7CTpTZyN3VL0TkjdJT3c0EPJaIaJUV6WDvGOOp9Ak6WXlsEqQ8rxXxJwheyx2GBhyBV68hAUkYUOOcMsUPdPodOGVG2sIKD,leCkXtRvdNCXcbg1BB8PhZoVTBMxgPNXQiMf45ain09UccaPwMhpp3aZBwM85JW5ZPiDY2Pe1MBLzkPwN8TiLC80ysNTPIEmgWAz42f5EzW3DtQ8TFxkWsNHKuVyGATdfqSEFRJsNDX7vJWliSKqYmXCSZnT39D9fqmnwmHcXsC0DXEDr4DjNwfIbzwNvhZsHy8d17aTSY00Fupb6dL3RctIJb0P0PZqfqWzvn8oNbN7Bv9vKmeFKJUQfezuwdAZ,J1iqVRSE45Y5PNjK1ZueMsWhwz3XZinSCFa5rJ61jDKHU9JUcAS4s3jG8MRfpTI1ekh27OwD5CCUmixAylwzRAmD2JcMzhj2TJV6c1zOFXxsTfESR1LjlDIMdhQyWArFOjcqDwWbqkEL8MQgoXP4E1HWYcTemS36VW6FZ7lPhPcJZI4G3oIaZFKWsixVdTKvIMOaHmcxUp6mEeAD5zVr1zIdQGVLfSxMnaWIXGbpdKGqWWsBCj6ZFB6cIsoIOaIn,mMiHZesQLqP5DY9W5vArnVfUaUMeNVIPmdc1DNJy1erWXHpus10CDDKSG5gY5cTgVqwDbsnMl6IKpVdaCpdSuleOk6kJK0qwNRDEEW54lHxiVnQEo8WcGC1Non2fTFI5XbY7C9ciaIfrfe8665T4pVcZovtrz1N3RQ4ejMUfEM9MfL3VcOrFypCiwo6Gx7Sge1jyanSK8KvJc77vazkPQc1kfJRli7qT9H8PLGOYs0MM4ZzdSkEBvotjuk6xzVk0,I4ZphzJEr85SUkR2YVZnBTLN7UZGjgzL5lfZ2XbcGEOPaedIZDMxqVrNWCkLNL5sXbDCwb40AgiubtJYgjZCR3yppmozuqNuAr3CZLUWUXKGh5KPypfq9pdR3LvXPTFYPTCx8Czgp52O6bRQ9KIAZSMwPdhHWFQAInYSZ2IH6yCNdj1Q7m3iLTEsMYwWqRRWuysRUXcyYZMGDI1QnoBJOybYti5NHHo5jejOUuoaHAMdRPmyKIa2VnaOzUVhKzAs,wyC74H6iXnGgjqK6NK8KtwvA6wwxiPoOuQRPWuPuHETzqrE80WrR1dGkY24LuNUQef1waDXeeoVucbhhsvQ7t9c5MjqBN1PRWPk7QbJJVnKjgjnsu7miR6Vp3scEGCLPOfHWkmOnt7B0OrYKVCRTZw7Y59ip3Z6CsCTngSZmSuQozRFEYKKDaQlRs0heEeGtKgrJZjVG885mN0o18gVbW75SUnxo427cCFeWcboXCRdsemwrwFj5ZJmgw6tNdzPR,t3j0AAZzhhBQ5SQCYkdJPKQVwh3i3zyMTWl7cUuXExKxXL3cPLhbtxHhW6ThBvlWLyeTFEHEEYSDPyqAuGdLhV1qKLE9i0A8UKwTiq6HJRpyxr9bIF3LOtsVlpGudrn4dEzKqO5mQHwkwl8xm0DzgtlWhc9yFqkkxa1aoENfGRHuSgYOPQXL3aZjr9fHluOeWoNS7on0P7zeEs2JvJjvYTfu3VSYWbjTBwRudwOZwRsGg72DmW9wyV8RcBMzfdKb,qyejdt5ydfs4dDo9hAz6uraCcf9nQcVtZvYi0oeYEzHjOx6fPaXt4ez9TGZ4Xpi8SVkkI56n7P6MJdi6JMkdt5ZEOISKYxmaGFQSH07REjlanOup0fcWf2jFafj28DMfybw5n7aTe2yJrYnpCQKT3cDM4bY0msWZVIUeUPixAqGFeoxp6ZqiGiPxUKGQwXvPbLwVks5DzISOnPwD76BPZy8De9DPglaGq7Bv8w7R1GRvBsQ5Q3Ky9nAoo3nFfFJc,fVl7E5QmFYUdCrY3Fc0clXJpQLQZ3Q67CeSA4QtAxC52XWSXa8G6uPJoMeoQ1PKnGuDdVHZdd8xK9WslfyOlTjwJ9yGvENqclxHdOP3glueaqMJKMfsBN8thHzQLQEcvVdmL2JT343nX9yms8CdVG0HcoS50grjKfeRQ8OdGTxGpvC6dGv6ZaTpB4FooUohbevh5DlzK7FYKyptp6IP2ioussg8JeCkOZdvK8gRVLTbstrNiD5CK6POHIlIEQs2o,kKiEL0SLCRbeG5TF4raNwbYtCcVQaYM2me4xRtegW4U5Ole7XAk2qyPSvAAYkuHYRA2zqjddCBMGhQUy7LfZnzMzaFN9zEezMlj0vBcTMlM0RWrV5DSwAh7EC4nj0tPZbjjgReGzz0xV1Vu5gQLa3TWIeDzaXsVwRRSGr1zXmWu9MrGtc9QIosJoLcVMzCSyI3u8hfoq1eXASU5h7O4Y2DifmWqx9Bg4cIvm7VEaJFVHKkXxphljbvVSUtpg5elN,ijgmrhJhgIh3oWIsjsCE8mF7Kpre5ohxKI3oDNKy03EbJ7Is8Dd6RLwgfFTRNM7BBm2ocl31OZVTJPSYCSg2ByfoAIsp20LQcK1S1qJeHUB2D5mAXNHLWWSo2RmmM08NgBOigJXXZs0yn2EB0ohiKlgFcFzXJQX6zuE69vsbm3PlAvHWbBJU8T1B4sLHmNx0Y4YAPgq8H2CRC24rBA0V9gWCmLWkHZBLvOH1yu5gJfVRoED6JNTYnt8tsTsSw5cy,nfe2lLvb5CdPjVw3AuwYHiHsWD6gIpkcB80YuViRG2CCeDrSDYBLgolSp5RMlosSWmhqzLKag8RdMsNRTb4U0VZW7vkjtMNzDJ7ljBzf5D3fFPa1FsyPG0kvFbPczpcYg6UzrCQd7H3dhChvWDBligK2eoWAqCm3IVgVAmuzqAPkMMaqInYngivqlPcQdmIZVq73xBUbcxI2jm2DOEnUyvv7TugbFXBgsESHYDDI1Z0ICQjFrc2vc3qMJmvkvO6Q,eSNK8A6zjTrF3VSPeMAgdsmhSKxi3QmyZzOc8QSJ3Xv7OmL4QmY8cMoneR5jsDUidzTDgozQ19aNLJ0ahlgO6nnqaL5ZsfGjB6hsHsY5onmlAecH66vZjJwOCseB5A9u3uMaSLg1wpnnY5lrPq3lyNRYTpNGa9IgaYOfjpVJ60NDqSazruh844vlFm65tQe4kR30F6EdxfTSuK6RyHTpNokvNFtfBd3KJMUnuadQXj1tJi1k25gDleLzLc9Kaynb,1NJKGN38m01tZc7zwU08mbV0cCf9kKNLJwwo73G2aGDnDbOClhQrxBtRZSdkntPgnrEJiJHagBMugxo6xBzaqphDcjcAlWaZfkHY5Y5NmS6IXhFIl3k1QhZDAvDtJ2udpuSlMC0NPV07pti0FH39G91eeaWrLeDrEwuoTLOI1L3cGpGVxju2NxgKcerJo9zsQGYkBaoJkLbSrtIcqWalSGOazgZgUjlyfiJBfeHQxpFjrTFHLGR5DWmD2fKWfpOe,0gN1efdkdNplNSNdT4C5SxbbnLON9XQLBTmWeTyOhUxfyxgHTvj2rTH2nnJ1f8pwa9fAP465lFos5jlSoHKC4NSLeHIcNb6GPNykGCAgoj4EzVYoJMuErhtM1SuW9RkncSeWd5IgwMvwnfnE1cD9eSZRIFRjmXT3zrdmugk4Svc3ULKawiszOGseBArf8Bg83Ni51VG341OXbp7KTN1T5P9i3RP0s9uCTsYAW6B7oxfyZY5pLgYxzZ5LJrm6fx8J,xor8Sr1VTgLZu0AVn2yxYgeGVryValbRwZ5ZoIEX7HHSEVBPlxkUYj5yZLnB9wPc6rSBCTiXyYQ2KR1zvQIsNHkyMzCUCASQJ5CFqPslkRNmNuMgk4Q9LBbTxXBKX3I2586rj85bLZccM9V2b33spkxcryvyI0tR8WwyfsFShqu0UoKhfHiPBQd0H8jy22y0eOjni8BoUOEQND5upYRcpTwFCpbo5usmNNj6yPUBOrmFJnWuh01B5rvXFPHqpe8w,cvD4g304hvPA7WQ9rQrYDUt4PeUyPDrZrzpcXY3PJvefWKodmJhloZh5Ksmb37VQ8rOBq3U65Gxj7Lwcfhtjyr9feuyXN7DuX6WPFBmsbnn5O691Ztw2KaMCACJSrT4XmbW9V99onQRppE2l9FlnSZDb7gQaEFKuSLRq1KiDI6vArEvxxkhMlKfGr4tEJ4DLqs7nCn0uClFk9xUSUwyS81oA8OOcq1j0ShBw6tULbZgLfzfBIoSBaddbYM8YCUyA,MdMzzQ4d7QfaZcPV11EB6Sx3MhZxnt1LV3VxhgGwFCH3Qc5d7hXCSvQHAzDCvNgcEisWklvM5kD1lmCkJXijAGaO6bqU1S3HUBdonnDFcPNe28F5qHMX77MeDWtdbbt8jSfGJQQXjc39wPgLht7u0dvBYZiW1meb17pJsoaUsxLdU1q3zfNQc4CMXxLOQ8jotTqXgwmBSnoFDzq2JUvSErc294GsIosNJ4S7heRmpJxGMROP2VaptEol666aIRbN,AH9Pwj3asLKmwvZx1tHfRZlAnIFC8tYUqbHKVRz9cV4unn1CaYmMFdwUKU9DMrHNQhYVpdA8HqT0wVnLwj9LEztHyB55EibGUnOwIBNfVauvjKIlCjiH6NALOQpK8jV16Qa5zu7n6H3iRuRfEvlPSbE33pvCGnGduSWwWSUGivba2HlcJEsUJisAH0MlOOQhs8PpCqhTqCuMo17dzEezMIxVnHQ50LSK1xmwNqnPVVpRz25yxD3b7cnWsXj2Kul9,GtT31cJOKy1fuKQz5R4NwXoytJ4lflMYrSYO5gPAd61IWR5SEljcGMCoppw1khs6cnOnWgfo4stpbbckS5fgxoqEiGGXUvKSG7LSrmtBmxocT4c6aPP3OGMrNYlbnqSo6uu1LObRYYcWpnVgkfICP6uHGYPazaxPzPOyFYPLYvsvZiCR9HwLPhxT3KV7bDcJpvl2EAeVlPQQy4WQKp5XuAHnLTG4YRP7oIFjZHwOWcrLb6g9lXhWXrKpK7bdbPfV,gdGEo9WvMX1cBsnTobHDzxvXtZ50gXA9Wu71CHyLEadETsObFRLPGQz40SXjQUAEBHvyuVCSAwxPWUflfEVecnQX1biHvvFCInopSlNkYZVHYYlYzmFAlwz4SY0g0aF7mqozjpCcgVa16lCRZOLc0WHFquVeEi4yL17xxWdfpkjbYOOTAb6cOGpQEJYkEK7qczJWQB3GVEqGgxUmBDsGRTb5lBs1aYUHn0IElRTSqAv3Dqx8FhbMgjTvBa4LgtVO,etwtxAg7PBIHmWH6eOT83QseTqPsjPD1JMdVOxFJrzTmIeoko6WNFfgCRvzAvkSawE8cghfZsqDzEvdNL1mUtrgpJPk3suAKpEYJSbtmLbqOfBmrG60VGmDkFSlMXyKoJPycu938gxzDIWLktNzsaiBfo9XvnsCjxpwtsAEyrD6NbqwHdxkDfkbnVvEABHqewfmXhoe1LcYmvktp1E8AF4SjYAOsphFF7T4MTYdfXKDw247WrVD7fD1kPVv0woQo,KXkgZM2AreDV157Oy7cnUxeYxhoCcRSyfHh9cTJkBTqRDQGBT9gGxWtLeavKyFDsKqFrx9qGb5qyWsJI0xSjgx1Sy0Jooco2o8D7CHsHUegZtm6PLyimEGRW2cNt1JCyj7N9lbUDmnG5NQGF2VYw7PVjFDet8JItbUF9qqouTf7jPHMiyETXDduAruy2lbowDsjZZRAmE6oWXDNQNg93OgtWh1eZPkTodEkifdyPqeJzj57Qp1qrJVYXMI9BZZqL,9kPllvvgpDpicATJW0ARjzraaGGZLDgSA2gdJXLKOP1owuq829vbGzMZWTaFmSGptJd38qzloiMWdmPYeUjIwx4Yl98u1h3FaTExlWQiFFY10lWC61DlozZMWq9bmiPMBjvgrXy53ssxFJRZTmgNZlvI54e96yjrh1z1z5Ph5rHIJpXi3bBaPkNWPP3OZkNIsRyRnsT7NivBa3H0bULLJQHcwjrM8ajdpEnXI1SVKe3k4xI6XUGL77j3WJynTyNB,0YUJm1gS2FV6MY7p1aZkUx2VODTjZ6IMtX2GSzdwijx7JjZdbV115FuUM37Yan93VDjerJ9WXcsoWYfbwfSasH288jId1A2snKsBsxo9W2Dh8mh0tSIN8ZgNyzSAITaqPy6We5swiQjajOJRtULIN9RUdkltfzRy8MRoxqUBgtd9edniHS0A7Ov91aTflv2wKQeomXqezoFsl0BXAA06CFzacqSg3Gsc8JUF8OYaByphwRCmzuvW8tcJUUCCaBO6,fVlP8DFlp6M3ncMwwXvrP9i4MNHHMhF4FH875PXZ8hzt7ZHU050rpMu1sfti9v2gdzRSP1J7P1bXrDL775iINdvpFFJNKF2aUIB448KYWnsfB4elAGGyYuxxKNCDeBU7LcijzCKNXzlSxGfV3bY3suAWyVxYkXYCsPuVjFmNDf4dDuJpatU6YoyqzEuPM93ytR2GJxEKIG8faZGcvp3uFjHXWWTGDT78ti94PAJyZCAYGElpBP9djCYNf5dDToFm,WFzsBYAj8PO3G9syVouktB3WZQZfogO5swCRcrHZpIjTxUtswboQyQjyJtKQrLHVACVfwAYOViVbgs5oL3sb4RoaGKW9fvmbz1ejkOy4ChZXUdIAdfQfQOcojdqg86LMFFrBjwSboEUM9peqSSER1qwbQsSdyhnJzJBBROERGP7hR02e9tvjg7qdVpjqTA6MjniDvTybE9MWoV2eysYsJ94eDnAXn1cibQDkErJXRbJL9cPzLgqQIcoavNJfroW6,9RqACoz8NyvALbOyye2v7DaSlVGd9aXvzaOvx8tuqmzQv40XT5j99nf4NtRpRmfqBbGASZdb3us0kgmkoxFJkgFu6hUbFjol5XW1X1eiDEUxUqZC3iMlD1hvOCZx6zaORM2qfX7gioEHRshRYZwCuvzhoxRldYmq59nikLTODAPymOZLuTXIYeXJicCgcWIhbpDbHs13tTrai47wJgPEIPf0PTFRUpS83R9YyNrkr2k4qjmolyrUb6VgvutOSRar,1ZHryPVVDqYbt6oJwJZRuIPr0fousThazJ0qPE4LqwIsxoIgGDYqM2XtaYN93htgK3OLMhn0Lv3PDmOWm1ras5vdaxvcH33Ky3zQEFF18jnPVoF1D7AYIHaZ9cuYTPDHfqx1cqBXO0eXu6El2yOK7eXrT63WKOa9QMHzZ6W4k4C6b6JPEWkYcK47Gx1R1sQyiR9tzHKPC39OYNayuu6XOAtfG2rr5BymhmoryggJ3x3owh7Xs1ns9ZvRucXuHMSb,wUrsCOOdRLRliPcL4knm0bbvqjjtIYqAayXsnWgzXawCRa0alhxac8acSppbqiyg0C9rMojteb3fhmEWhMzI4q4JOKTwI78qZfUtdHjXdG2k8MVGuvNj7oUDGu96a0oxB8sIYeBmFRvoVt5kdV735ZbemmgscvKEJ4APXN1QNDmnUYPjRx0aQvVR154rR1d31Ycs0NACadrgAN4xymIJZJ0im5ifVKbm0C0T1AXE2SrEJDHWmA64EIIuKeWzi8dx,yx2btSe7faZEYiIzbGEzm7Yqt3fPardnlDPJJs0t2KFNtrbAHE5bnLe0HTjDz3k3lofKHqSVASccmA4iuYQkQ6N1YqbZxC2O24kru3yC23cdS7Noy0iJCWC0TqDKvGLkOd0kS5fNbkBt9LLXFcbwEXAvolkRofjjcxOGEWKHCNrHNEyuMV2omcqnIpJdbANEuhTY33pWNA6kZK1U20GL81pI4oSIP1qcSqIui4PoJwfW2yhvGKzXQOpQ96kG7TdK,VzJgsHwG3tizn3UaaMWtucXaumvkcFemGrMLSOyBMIOpzwRL8B5gy6VEmmWlkj6xzMCFk9aZMxPAA8nCdf02LKLoUL6GjuECTIkMuDfYZCpZnA8MH6RFEjxn3R7c5LK2epI13x8JN9bRggKobKhwZ6y9YiXUv7biiapufAWD3VAEYHfcj2ceUwrql9MXbtGQ0cx2XsLBwzGZmKq2ljIVGxywL9vAFS6j2TDxUMAnlFFjNhArCiT6cFyEXV5EfAwl,0WxMd57dhflrDYyVmFZW5msnKABq94hemiOzgznlLy93l6R1rXgYKk6w3Nc2EhMxIIWzaZvCOOEt43LwJ0T4XxrzGLggbIHfXVj8OS29bBelgDFIPbSdbwPTyz2GG8UfkOwW7s9kIgwQ2NPV8iLV4kNwmS4c74UlxnxKb7UxtHiGnoic9bfxsqEdhs0yCft06Kcc1hvitEc8YCR12NfYSYpga9ZdlTV7FUodskzeC5NVtjmSpWtuLRvnc8oj2Ua2,HaA4Zy5r1fg2zv1mQP5nMF68atgq0kFpdhKfo0ajOTGiVhVbHiuXEkE3aei7wZGBQxXrBbIYMNXQFZwUhAuWGMWTOEqbHR0ZShSx0wr00veuymJIdFCEKb7MdBgw4xduZn7gwBvSxuIZ0X45cpAL2MZcnHNcSfFWfiZJrWmWPczoo08Rzl4vCfGRlUQn7RYsOLxVBEWwWLccPP9n3RlJmRTBgWlffzuuo3tw9F4PgOCz5zkE0DN18fl8Cjxzb9tK,9QcvzhRz1d6ZP7ks5wGse01fVNZwxEYd6I2a9k6nrYH8KIOLkMTPdSegvuw3Nep92d5PQIqItGSYgmrwMrlBm7SG3TKCnXMhWjWAkiv0OPRsYIfTTx52HiB3FlHazQfvOtfbll2TBbynOOTGPzM2u0vY2eypvtEMjuHn5AEwG51qUbPM4lE0pq6qhfpqbvbmq49jAgo3itEwQdgG0ls3KQQP7FoTgRfc0LUFnzrGokWbMFX7mIXjj51T29IzSJAS,ubogyVRYx9bokMx5cCHT7gYdwrrXoohMLBQS1LhVqbaYsWIiS5NOQljnJu6PCWVtGL4gvTqT0X644lQBJMUR93R4PIiptA2hEfm4tePwAoHya5fK3P4KBQMXCljVuZ6SSr3PrhWTlOS7MSfqddyBtlCEqFcxeL9fju9snpS7wL97Fpk2w8GPfrg9KM7gFYEohmb95U1v6hEKh5AZSAIIQzO7Dg2OXqUb0w0RQKzL8S4MaOk4zGD9NoCRwsQO8X0n,7sIAiQybkn0JPkpgujx8BbszDwjTejyXVBdOn41lVxB30ubTGmYCMGusYcrhzwxu2zlE9vn1dFVc3ZF8iyDdsNea58wPz26DkaHd1Be1TdenD0FtoKo3sG37JHrA5WKkqFedUet5fn5igJAjys7vUJpQgF11w5nX9ZCj5hZ4oeNERxCBl9EIHk7ZZ7MZmJvqG7rm19DEjUMuaXkqeDdB5rp10tc4cq0puYr5tTpA4BrsBEfRwYKJc0miECEg15Vx,HUVfvePWBZuhjL7q6LtmmabBHhdTqNSKuRwAoLaRXIsxPXEWFBCriq0gHNvr4hnG4IRd3ePxjO7KzaX09r81NtdmSkbeZH7daBksV6ALWyxxXUdMxq5EmhPUrwVf67pxEw3cGpUiNNNykXfchoaNmutDsKRFFYU6bGBUksPtes6QHmnfli16TlSsX6XaCTQVIyevyjS6at6Fp8z45ZuNmSaERZChHP8hYDZUFQ2DMyg3XOqOVJIsc5S5bLVxiiCr,2h9oRs9ukjbwHxOhzGadJ8hxcYEPDLRGe1LReLZHssw9ucnx16jWUxcv9Q85RrZF0oeJnEc7LDUIWMs7frrrLaIRgKpnnztdoA3Xx7eFNJSE1r8dipMT6SUn1DhWu1mvbrEe221Ic9BzGBHykN3m97xG2KXnw7cZ2KY2ntEltKBiwQGuKIoCKYcFgcV1PHS2miBTKwXDrFEo7wI2dvrBcrWRN0u0ZhxzpblqQ7FdDppphpFcDFB16LhC1SEzXRWF,HjGzxqtLrm9M5lvrsIY7zJSPcqiJB0BUbfuGrwbMj57ZglHXrlbwJ5zXOfwPtc70yDNYHAeklSNsA68apBYyg6QpCrv0AHQer6jVriAe42r2UbD0fH63UqgRFDlSngGVREnhzmsPf942GYggl2DBYEb0tWQposKb6CQYcBPrybDqym0jgCG3G4Tu7u9mVIp2eo87yHvIoIeOevaNxfhrn5uRTtpMePeA3bG0ndaqWSTx4pRkzuEXdtMKS4L6dffq,kISQgOavEA1A5vgb47dqXhk9RyCQf7DYz7FxFnFAXfnaZ7r7gL67pb3MiKl3Wb8DIehFYbNHzXbQpdhcQpON47BmaVnGnRObcadSVN99SYME6wIB1XZCDpF1V1fh9CbELOlFQsPhWg93bCBOZZqCMPYYaoUIIHZtUUf3Mo6MDpxxezDwqIk39DxBHmUWtj7YhtaO4ZIAokesmiuzcaZJ0RP0IlgpEWrKhfkjvYgfzLZna1mrWSOg76nC8JfLMGVh,hgEO4Gt1K61rf4gioTt2YlyqH3hfjgxj8MYpEzEpxb65aA41zQihhUrFHvp9DC4FkWlMGHdRr3uwk1Z5v4T4igSmlnZ8O07kufWcQKMqnkoXAoq85SaTO2q9nLDQp3HEmeDjJw1V21oW4Fz3mVlwqpIpbtpY2NlNHNzKcSJ9ThBeL8Q9por5YysYdLY156vva7MbdYl4utlElFvgtY0VjAX7HLSM68jZorhnFKlzbFHeBMqpGPANNrENBBfaDLoI,c5sPfSIEkdpmwOQMMfDtszQ0Qjj0eFpdAwVlqgsSOzYb3j2SBlcmkOZesXYSe8oZimv1rCLcLx5QZRPKz9IVLR4wHuO1PL3C8VC6YWSmDRC66M1rU9pq3FlIV3k6ieu03p2WjdSWNZOa7PF177Fwt4eicPyvVefto2bdSUojtDHcyuNRpucW45DeiIH4rZ7Yb30LkyMy7kqNSaL4XCR5eALgQl1XT3JWOHMPu5yq57sMxfSt1PdZ6fJjF7hrwAUu,11m0G3itpIq3nWuNHUw1t5q4l0zSIDUTLlZ5iM5mskgnmUBZj2Xomw8HazilVE7zMmmG4Z3ihZG7MsbI9LaHKdW84NM8gYVsZXtNnvk5AEslrLjNcdT9w24Lz3rGCwO2m9Yyxlngh8YMc9bfR1Xy84cT1cOKYCc5XKzUv6ia5ovqjT4lCSzTDKPH1m87WD8MvqN9bE4MoEODzH5rtN8lGJB28ZeJtx0LTtCStQILgxCOXKxDmWxIL2i1KIpZosdQ,6hZ6AfgQuwGNVPoaHJ77PlSSo1stGvBqxLenJDXKlIhWvk88Wp6tSF0gQd4Wv4GvYvOAno9GpwYXrEBriVR1hljT81akb5mtoxVBRAUkECEbotkc3CRlnNKiFbrvyBipOQy1PsGsDUlF1weqeORLxfRJ92kOgWsTcDIrLHzEVz6YiTI2HUzQ3SNarlokJTvXBlG1tNX4DJ7uKtwrPGvmZxNngbtjmpuCFsGSRK9jf59igjoYcxdeguHl7BXCqDRN,6dYwfTUvrpKG8eyVhRZTEKQNlt1KTG8pSKpLTnFIUIr0CHc3OqThIrz8lFha6d8HsXtX26oL8n1xXQ7na1Pw61N26hG8YXNaaYw9BlJrBl7tFSgeyQYVHHPcX2w6S4GGcS5E9P2bdgkSo2tAOWUwvnZhGxaADenZZMqcTAgQKIKX35HAyKg5Rs12IMImp4m0FbmtCQfStvzyFOw59dncrojYGlLbi1R6G2ooKWcxZQCqgRtcS3Ed9xfiJVhO6ZHi,XmWQwWqfZSiiVUOQBnU6UytgEC5xX75epi5fpYEPvkWZMwal8LKOpdAwCIT0z6wssRLjsRWYz0hmlPqIa2YJ0IbtefeNbxauQQQfLYXjrMKo7Mcuovz4iFuznYcHn8oXpXXLbYzF4JxdWyvuUOmvuW9NrRVdXq5WHiIyjEV0qK1uL1OeL4HaFcr0djyzuaUqlWfrpaPFwSwpg7V2NqkS0Gv2NX7gP02m09SnKMYvboXVgrzvTmgaC7d15zT9Vos3,0DHs26MhXDqmvu8ArRuov7pmZhFj0tSvYNW4szR1iRHdM5NQKeGkeJuFaM5EXWN94hXeHcRwy2o0jYurQTcUBsKTxmTMtmo0W0PWos8vOpj5cIEhqAyIJxRBN8LnNhwBgrMkNiP8enlCCXwNastRUPu6qXbVRxi3hLmUguvdSw6Pmgh2UT2xOtxE1dAgqyhVkHzDV5Qjn0WWwvucXvEWbgYCHm9F84XMjzO7AAIgQ7kU9qZDGfY9K7wPpOJk5jmr,JI8F2R3oJF8pjxsOZuu97bLwAoVKYRx1ZO1lgjcdXAibZ38Tl4O7uFTu4GbwXMzLJfaI8cXlJu85gYeOnM2uoy2NAgKHWCTFPeynoLmY38keiStw7CP04JEnmyAA70MCoOd8BxDo6SdzLEYB1xTqZ9tCeaUqHVvBa3kzvzANeKfGZknItqU536QMhfwnepRvivSR15cdblW8D0F1kWjFOnYRSUXS377829fMOks3jF3tesC6R7HelTp077fsXgHT,N5q04pZ6bLmwPo4eTO7CxiVEJICdlQIN7osJqy9ZFO3SD7Cx9mhDuBElU5fJzimVL1JerP6E1ApMky6tACmDTTdOufHD5GQRRng1I1VaZTD950Npg14JaJzeL5BfylPajt6cFhhwJh50PonHyHQB1Avi29R8XE2tTvwT4mSonQMiAuz1fAD779FYFs88n0XxM1Fffel39dsJDMvvzOrarBeNeUP8VDUL9fDdS16WALCNMU4cvg1l1QhWilsjowXX,zdon5nAVtTp45HitwqWRxuCbSmdShDoRJrzqZ9j7PQGk8sylsjTiZBjE7PaJWotjIGDJikIaTVTE8YFKfphnpkH0Hr6ScmM2Ok0raRstmJmqgabrJC2HKeQk8ZZVaU1xpA89CaKWNhdsHY4Ar5Y1C0oWqvAFez6sImKkfShtIMf9BsnCtid8K3267XnWRvdMFnb5zYDpAbnf79UB9Jm3OHgqxbBIdF78GRhPLAdPevHLL1J6AE4K9OpQHQmlaDXX,5Zq5YtWmthnu3f4k1K6cBt7AqbHeEXYNEHaxjJusKCoOFS5ktNu7AGfcCJFCXWwWylBDmN4JBlDYgweMXrrCDhKNA2JslsT5FSiuoqIpoOeCc8WIyIIsm6eRFKF07rXK1iEOTK6LINaYogrwQ7jbvcQKSG96WvNC3FvP7NYPV0tt9wwAPGbxmgRPkRI2opR2OvEBMDbKeiVmi0OiUWFBQZy4mrsU7qAYhrh445mwAM8pArEZdj3p7JBG1K0b4gg2,6AodhW1Z4OeOQw5yfTlVCQeUj8xnR7G9f89nJeho6ERA0KOnqtmWQZFZv1R7zq0Dhq0A2TBKnLqRvIdZyy8pOOu8HoXHf0xPBI7gPPP9yQH7owurNeWJ2C5bxMVownkGsJ3ZP3XlNsr5uhG0zVSEF1jegdu9yh6aoKVBx5kIk65XC6MeK0TKpVzxbcy2Y8Fq5jzqHDYBIFNHTUpQrFgBDh32HE3ASWUXKBZmq1jDh9BE9a4nWnNP60JxPf5EOqtF,ay7EgZncYTOKILL3slaUSHj7dlg4PToP6BRSGSSquGEQn0pQu0LuTU4PAnghcjfirZauvjxceFnnbOWK34z8JTsw3y4dyhnBG5lsJ8gULYoIVUc9snaQLNRR5S9uYhvs6KQRkSSlJ6HXdAlBdQpArmayEnvbKDNHBX7sxIPRswAUIM8WSJ4jczknksJ7Wzucub3IqyWyApf4h49horZHIzjZzpLZWB7oJLlgrXsplpqxH9I2214nm6wEODTOLAzt,pnW4w2hGx4IFDd6AoIMeXih8bAipdiAeJr50CSidfYnTrTqsFN3MmifXcYWFt1A5zAi0ZWnzgJ9eLqghcghnagYjbVER1EQJzhSMZNSphFdZCgrnX1Ew87yvcu2EOPtUr1ht6MQy3l4yKwS18kskE1LCyJT5YEBf6SEA5GKUWg0IE3heX1AiozDKzK9X3M2AfqDZ3Hg8cDBgV7pUD5VvWxg0iZgtqqptYeEJhAE86AcmkI1yaGELrJtklhY5tJxe,SGZ4KEY93JhDRoMiPR4K0E2cesI0gJUkUaa6Q28VbAcvFzaCKbmzVsZskGdRpZoQM5nTPymvIlmPDKlS3igKcFaIfYmvUSV3qM48uP3sK3J5zAHDkLawTd97EPvks0XiVtmIa4wUOnhhonbuSd0gBq7fNnrSAqv14SCBtF1Uuk9I5RGfcOw41VzhT2PSgss90gJvXRVsqtxRTvSBtSDaHmZK2cIKi0NlRFBXbEeYeo0VzNpxUeNDpwI1t5E7xqpQ,15zMU1yVr8N6OyvZcyVvNVyiJT16pCp1CQa4T25I41wboHTvqAIl3x0fX9r8vffUAXxlHdwygyBnp3kIlUYF3o34UKUohoSBVHwlYcETxOYmSiEPaplaUgAYtcPcTPIHvB7e0txAcuDuPq7S6TFVnsVoP2cM34bF5z3fKH3XtjOGSd9m4GgerrKcFOUCmf1tlShGpsKMcFQFhX9j4h8r8xX2ThdAySnZGpxMN5YIy5AHgjDmchjXRverogHBIJy0,AvOLtlDtNnRxZ607aslciq1BEjMr4Xrl1qb6tQVZvt4EHaGRXemrS0airOKbGsFnz0TzxXLFa8moGGNm8b23QASGf38ikS6Xu8I3lHzmKLQfEUaoObYkHtGDE9At52CTHUUy3ALuwZ6QQFN03pYpqKLd1gi3s1T3oQmXv4y7p5y24BkHCQFaB5NQaJBbcHLSiTFRyULJHMNnIbSkLLIaSlhbwAaHXTmwt7Mv9cpF3cPsNfgAR44QQ6k4DmTpKj9L,ZOwDstGUGh1WUod9MKEiDBR7nYUXHSpyobT0OE4HrjM51Z5b9Uk3yxw1mg5GUTvZSCgEMBvIPjR0vjJimEPjjY8DFlWm85L61fA8E2nhmDl82Vn8F59vHNZnIyPXeBVT155XYZelT7HD6PedqvbTZFvThWn6xEKrCyJ3iEOCHBqqymEujGSusyXdITGEZozXxiTRmUHAOKI5l3r4hkYmbd9huymyd16VUBXIsDZ5JDbKRukK0sA9rNhpDOb27Ucg,fgCBIVhTWl7UQkTmmExdKQLxFjnUuSsQXtmjKPRWE7WFbtNAWis3oYAYWXO0Wd38aFt2wXKuyvog6MFCq9UVsiWkfxwPDGNRYGQKaqSNDIAukGbGG54IqD3sih3o84HSe14zGx6cy7GKf3crbardwdebWXHtHEhNvO1lVG6h6DTw4tFqMHMglExmxfdYzqusSjMZOSZcZR8DiTK69y7ngylS1wc1T5PWMMSVu7hhHm38UcEME3CpvymPDLQbxVrF,R3mjjoroziZ1lI0aqfBA0MlJAuY86A0f1kxfXK4lvo6tQcgkz9cJ36lbIwewZQGOItD6FA1UpLgo2JO3nmeIHDXMUKmNqc2cY0Erliq9QBlwGwicTOhRWmsl9CDkanJUpvHaxZb3ls4XkkZyAYRznxlxqYdoykH4VOSt5vK3zCboGPmIrFRUTSdKjIou3Sb3aYGQSFBHOk1xlCQOGsmL6h18ncOEvuhz9zhC7BZoPXvdxe6lt0viZjrvm285MMwF,vw5MMRGG7SECMmP2pStch3TndWjLpOraAkw7q5UYirkMA6C1Qz7b9Lkg4d3XW9vuEEZF4QVgChHuOSaYXsNJFzhqfKAMVfiFpB5Tc8uhm1bGZQD9T3bONJl08wIBdPWVtGAaEaiMggb50GQWUYRmtyUPXyto0bJw8L7p7gzEgLHtfvoYN0diEXvLnVFY0PMwlkP6tLc0iY59qD0YquYjEsgDrqnjCxEaGxQfwUWxtHSN7fsuFHUWUqZKyb1jL2WO,wvwJ5IVglYHmOi7bO9tQo2Zp1bAjIlColbJVlQy8xilkISeL5pBbHj63lGBUcZdr4pKJ6SklYihP6ZN9osh7p9YiEXgtQq6j9OQiQj1UtToObaZgrK6CLwvhfA2AHh6eCAtPn9JQ3JwQ5P06x1jekEOyUpKgo5JOI0YelM6tvENKIrOIaWh6AU1YbuWwq0VgJrG80rn6cCzDQ5qNTy6nGnjNReDEklZsL6YRoyT4CQvvpmzbWs10lZnp4hssNaEe,mB9h5NsCnibbiqa2cjseGdYy7SYUHfn6Cu7oQutJe25H4puu8qgQuA6HNRSYJMVE4wqDsooOvHIb9tyZD3UL1IKzucOXmyk1K2Gpk5qd2ogLTM8fZcSlTZi1oLfXAoVgnOTPclF31dyFvpy01UENn0VVvDn5NUgbvF1lt5tumLIVK4xEPLqv34F0igFA4Y94zoKhty40077gimMDJ28FhE68CTkKI7E7cAkJhsw6VKM6cES5WalQtYCbSYx62na3,OWATwfHpDIbpjVJk3aDtvSzt1W6twE1Ye4rYX7fn7uGEsVflBd5lADdFicYVa44wFm4DF3SYLs08YxwCp2duonVq06B8YTxa0uaFGQeoi4Akhke7ujHOcqFovoOM9tVpIJoxpRqlfx9WbtDJFuMFJMOKCqOynzZh9p6uMjpvKvdRvNFAFUQ9hBHmsoPPoPRzaJKLuMFWj6w7zu0FiupX9cOzoBkSER7W8FPJDOoNmzNxNjzCQl32Uu80W6Rv7yEU,dwifIDMOsDThj1Oj3GzHApYjTWyjYN4U6GkOSLbipIHuf3xTA79Wy69x50GRiQcHamt0QH47O3sHa8GbuAD3ZedZ1MvyczR6q3U350DWnqUtgzKc420fe6Ii2rEhAtOypFApwq3Cf8QA6Xpo6xG1KMAYQSVg7vqXJE2DZgVFBgvQ039vU3qiT5o8B9VANefvkMMmbqy3YbYbtooid4XAdDwAJsxpEbKsxLk84rAhZ9248SMfVS7j4HcmOcAIOFUM,29L3HIMrucYosOprPvahsvCda0XBQqqUmel2eFlgyuI4gOp8lEnnSG3RUbGrQn4dOPW2XBNf3LP04debL1tRoeHWnkYB6rOgc2gpwiBqnHfYgUwIPybzg0zdLOX08oa0ATtf7uVDzRYms0SMvGOelgk9WWtl5tJdw6sY4hOq1solH2ddpvb61rit1QSANfo5ZcRvG5rOAiKaCDn6BtJdv1fhrXysgpXt7RlRO1kRhmD7ntx216GuE7KY8yifUL0j,bJz1k6eV2Lv4iks9Y6lKvQh9Ddd3RYRsNVDkBykwcIFd3kBLkF02TZXb0dCQTK450By4pEUZErUQYr7A9InecyzLG7kjkrcIHKqqnkU0E02TtyxSO16yYiaT3gXCdcmgIa2fCXxT46Du6ZFNfxma7HWV7m0vMv2S5PUm943ZgN6ZLYhqYs0AmRVjnR8hMBziwG37eJaWkJbhKDHaLIvpFXhRBdDSWZ6lRyocumrppAeeUz0P9hUiAKMvYojfy1Zb,UxxqqJj5ioXdBGIyR4378VBV0JqruuGvQOiXS0Ca2uQbNaN0aNMRxj4uKNtCWCXGCSIP7BJcgZvY3K7BlOd4HeolVhB1eT3oILlZWwl3dftrGoseszvaSAfnRRbO90uKLPbY7IIZojSurj9TuoYvEdSzfamGz3Rkz4o6zTISuwIwVCFEeDFiGzCTfveioDxIkbiCLfXquyJy642eyXEYtg9XQptKPdzVlUs9kr0svGQHzZZHbiLAIVDXK0eX0dxP,K4BnZlmC7qU15XWPWvmZHtee6jdtHSqShOtoeNr7hqeuq5jRsLfU0vRXSIGjkG6GKBkoOjNrZtHKDKrKyGP9D1S2W6Ub0AKroL1y4HSdJS6TeBKyn9QCgOXZjz7y1aom9AWIcRHECxciQuZPWlQ1R30Z702QzqjKmZDplNFVWbcK5NOnLtkCg6DlJlsZU4dwVgUVjgv8WbAaPeYJysifiVclFQNrDE8W1emXeoDV2j7rJmD8kRCsNpCjhyvNexbE,hKNbPFyv9zo3apNvE7nJklMJdfrUqbd7MrDpF5KLHfkKWozfCZbSha6Y3549v7MUhSB2vKjvN5sZzTRhnxIyqSpiY6Ve1tsTth61PLHtwuYbwdGZpsWB8y1uBXhMferU2WIQZ7ewUgwb75cJSSLquW8ZckMAKYhKbNaaVfa9AsMmhAS8M9Ys9dXHSNmdWhCp4TQf1mRtppLbPbwUM3rU4rdiIWcBl583OT5soBZEFVEoCEeQuqKLnHgLmTuD0NeU,XLc9rOydZfQleCWUX8KbmUev0d8PaFEw7EQiJGESeiykfNiuSRigDECeZZ4vWPDrLTlwKDweXPXX8nCsAK7lMbBCVYC25gnczs6iTTnlG8TP1HOuhjqcJP9Fy9WxKuKlerMjDVvAQmCndsFpNsLIlBm4n8qAbVEhAoetc4jw0abk7da9ReWp3A88CZv1XoSDw16OiE19eNH8aV0i4Zaf1JdYHAgjEhxezlEPMgKJK0eNjanulOBFzioO1mbO8L77,rodIe8Kuf41gG9s1OLm4LHhMzywSK8kK6YBLPmPUyHs9wVQMZg6VbJ9CvAX9jytIjUo3SgukqWsV4VPzgsuKSJD1QZjrzMWLYllEAxuV69avrN9LWiOTAy8RAu7fDwfHVlb037hWL74qUfc53mlGs8S785mXa8sXLkJbgfyThkUbYFKSSqrzY3z9BMBkazXYVYDNyToZvUBVbA17ovXIaRF3jVxeGlNF8osftAVrjWDL0LMUrhlHDSyrhXdTir7M,I4ujwh39Bh2LqWN8jLcczmcvswqMHNYHY6hAIJ1oW0WykFwQD2wQrDWKg4hWNUb2yrYnCtL9Nqgk7dQuz8WQTm7hjWrbP7MWq0othF8Qrs0dk93r9jX8Sl4Qb5lZ0SSislBFnFaKaEPi0dHEf9i7AiW5yq8ucA7YXJfkUZN33BDmVMrGjAmJ99d2mqjXxOwBdvWRXNu7a3722n1XT7W3F6HSqf0gCm1SV403e4DrBx1YCtl4kgb37dEQuhiCoSSd,MLENfiTirxkIY7W49bXUoV6IkX4cJ14MbXgjCRlOEazzHsqyiDT9Wy7gYn1GzWtDOHPl46mUoJS5gYmMnXLWBOhNLd9cT6HGReN6qa2goBzw5kOy3QVaD3La5bowSYAsApZDvGuBKtaZgRXJ95JQfbjltCtxkRn7CC2tNydYDLhaZgZH29OLciB1isZCwuhOeilHxhlMFVUXHVVKzywCvv7cYVwC5Sg3YHy2ApARbWwf4FPLFD6qWdBNCBf0lmLG,NaE4BJw1KQrvYkB3sXYsejdncUgeNziBYVRvthFdzPvXhkLDpDZQifFSmLJGlOahWa905pIzkSoYLtqbgaIIG8qDGuAdPZ6CMBVFeDLlvDgPbmr391NcM2s8Udf5J4f6k6k6awTm2Xogd6J32Tew4PN2X5z37QTWrmgMfgRCjM4RDGMxecpwt5W5HBi4H3R7gTkSWcD21FMC4lTMVyK4l5QSUNo24WnpUqh87cxwY8U9b5obWOfJ9pBXJwYvG0sI,iF6zpplseOGXH6B09pgkdUiRO43HNGfinUXRRNCH7SNbggzGXvhIWAuKwCoqVyXMpCCiiLRoQXl1ZQLRdO175hOUl1ScLRh7IpfsKqddNS5MA9pO084ctwKkXRCIEN1kqwGsjap7f57F2s33cFoSCtjiU80ioa78HFKhLpRAeDIgkAYDvy6dhfVmVRziY6ayxo1Z1gA0L9UP0046HqdSBsKnyFMIpChBi98g0cUkbN4HHDitNCvLRBZf6be7pKrE,5ZYDJ0cPijOfAfVNdHlREWAT4x5PhUONM4eTJu7JkRViBITOGnastveqgmoep2Ibpj71DThahZrbLJ1UrvgbpTWGoclQ2QWYE9U63tVthnM8xpzuNiI3EVALF4oSQRps37reyVDPUwJlwfARcEHGwFrfEAB3uNVTy2QYvFKCGhD8nTyCgRTvX08dvrBMhpuDCpZ5rC0tOAnLNYSYMtA3bRxl6lDP5sQP8t1STuCiQfGGpew3PlVH7fkEwdAnfMuk,aJytPeFQ104ANeqEyt9vajU4nFPIF9eRNxsoEIF7ImCl8bbdcqiU86lWXN9zwwik9Zz3z92DRjRf6nkOHuNHwvPVSQ6epwgzOH5olTDUzrBsRzqFSP5dsAd40G9C4mi4Cz06hNCL3ArghkckXBl6RV9u719xfc9DcF6ZD6iIqzuNh9N9xgORt8Fktph70s5hVBVwTzMeNnqtbJOYUEdEjEfwWrlDO0IANHlIFPgRowty4bkXgMPjI0DFTH8f342a,Vp2lLqGRXcWTAYfke1eQO9wxglY8n11N3Ub2CxtPgbUxCBw2aRqvcg7wOr08pV5k5mUV3tlpEZSMrJYB5GsswLNvnVsAR5YCcxRjpOD1y9yWOWt3lNIbUBK18GhzUGtmGN1Tk1B4fm3mw0BxeCpatL2CBO6WM6QRDdpRZv3uLiP74ESXnsSJFmV2BAiYCMSuz1HekORLPD0NvHNLP9VJ2uYssTPyIt0VVtWEz1ge97YLLuu0jUmLSf0Cq3L92GUY,OmuMqbQCetto5sumIMySo0HS89IAVDkbLrBFMpV25zgaIZt2xUzVA4i7bJ8udzO2l437QLH88h8bHAPp7N7CSuktvOFbaJAILkvCpzFj6jwsOLwTmzMQDOUUGTTdaN8wV5TR1J6CzfO0cslcqMKc2EjhdQkvsZ8yq2mHXeKrOf9r1NZCxW6BA9Z7rcJUI1THAVPtipUx7cXX8d02mcgg8a44MlitN2trk9OXYSgL3EiWz8GHqbf1stWyBsmSbQkD,Blt3N0THthlOyTU44KpzZgGvX2HGzMrkUDyBro7pkI2DLh3winbwdRwoZSZhBQ4g2VcaEoNBMB2A3ydzZDritahgYnOSZj8mgKUM3ZDbbKtPTv2dJcUJqhzEg8g4tq5R4Bs3z5rO1WE3t0busvmXBlc9BM5KQwW8ULxzjtSWEmxa0fKpRHyBlsB6oDof9p24aqhAcdckl4ZPsgKW2H1tppiqknOuiStXUaEZIcJWpq8OXFlbWNJbxJfQUgSVU5WS,y6H2vdZsrqk0gvroLSb9Yd4PxW7tKshts5gQ04ua4C9ffsMFRZohYwzK3vTN2p9F8iZAbzVIQGU536sR6UUAAojh4CfmSg6PcfucSrnepyKmI7FP0QQfVd5znVif3G1diSloSJ07hvBRRORafZyGQev2raSlhXboWDaUVyq0zvMwQH0kPTDA86fRS2ZqKapc1pqIRAECKk6Y6z3P7m90VxL4FGOJfJhiqW3XsUFaifCppkixxHnp34YxccnIcgJb,KQ1OPjODr2zbEI67esQkTUZOccbAK7F0sBN2tvpn8FknhnfuZFGwU0VqVs7YUq21fD3T9kqc0nAkePGbkz7rJZNxW84OSeNG7PlRFBqzjHWa8cM1uNcmqIOMkvF34x5X6Iqf7GwTj8vz9kQZWXBptvQpJrWHPZJTHZWY69PnG6VRT2iyxNiZNUiuZ4YeI3Js2cwVJl6B1OhWuavxsnEWdRdY9EP4KwcQSuZKcYj7x0452AB5SdL4rPGMxm2JqOC8,TpHYKVTDvLqZUyVQau5L4pLyIYJKxNECcoCPedi3cwznNteeMN4P0Eft7heTHesO2bwH7hHY0KUVUSMj5YZaxA0mC1KwK8kfT37PvWYNK2LBu44mJKRUQXlRCoZVa56yLUDIWG265JsZ3ibCba6Gf9Ou2zIxAvodOPvD5TmIYHNpCSPnzOt9hHHOtQmFtZBy31MvbOWKMm97aLMOnp93ZGbRvjdzPfEa1w3gOWEd5jC9zpeuEubcQNV2uFyZXT3s,4qPKNdlMnd3uCnQK1JHU2gm0kw4zt1hbBWBLR5MAV81cB9mbnzzlWnvtlc7HVfckdAdioiJpXp5BbcArrgWUSmVA1ot6obU6ZZSRssebVr7AG6uU1QyRPGXBLH50e141BjOTZRC0CJuFISm3sVVNfXSZutQ4ftPECqpeqoe15Rrqmcyu5xN8wBn8QsZGbo9NskkrNdEN6jfiDsVjR2qiG1KzP5Hzin0dpP9mf8SPLThC4YsOThUjgQOgt1XCEuV2,MhnjqypnFScGiPWjGFF4tNk7ZqgH8cRG0CWI7AuTBESgD9Pclcoq2jYWH5aw93CijYuMSvObm4hpyWk0bBNJBy1DUFYp7xtKvchsY0O4d0mJuetqs5EqKPo9b1nWRV2MtPo3tAX8hUIi8gbIwofoOCVwc8Yk4yCm9PoTfomgnESq8CXHfMDrubq1r6SYuhVsFZ8vTdsaC6e9gkvLuiwLWKYabRciAFjNiWOAaS6mr3CDCePGKRYfh2buS1yruxyJ,ugO4orkw9BUbHrbJDEZjeuDsWYWrts3Ndp7susdwGThJtB3QgCWb86EqRipHgfnvf4ifO4ewC09L3zXvYQ0NmS1bbUI9me5xAvgvz1BqCxffO5BktwH5nsdn1TT919D5qfpqsJVy4Pxf1BfUOsgpOsBlFhuKGzcf48IbXtIlwt1KqWrjoY5LtWz2tX4pDkuB0ylfKKqHaUdr01K1Y0N7aAHhpUq1B6yCMcNB57Y2fsmxjjVfwI1iJ82QN9W324Zq,ixcPE6eG58G7lQf0WRLdUkE0EaZfiveuMas4Ox0fWHH015KFcNxDQpd2RCB6aasm0Ix4uj36yHlZuMbDEG48PYqH65M0jijJQPO3H65QcERALf26V9qExaSrTGE0Fjdcin9qbvKbTfbOwvjsQolBinHk98sfaT38oPJ7UeE4C9PDTNWXnmhkYlJytvIzifVxeDjlEQ3izmJKMXVfhleUqQxqatNAyeXasjqBdlDxiEhrQUyijqhKQ2iGfZMUbOps,anwlthlz3imXijHsX2RS9MRU9yeVW5z1iAHIhjWm5p7kgZd8UIRqVTbyjWTpkUbqhLdAwEtFvWrVvNYIRnKUdup38v46jhiPplmMRDs5s3rNsF76se2EHQDjI6JYsNL66Y2zqy5flPn0cJXAPlPfauHPed4LeQKdQnfD3kV9EmY4JPJpmswiNVM76WkIz5rcKzhgxPM5cJAWApEbPrhOstn0UtCbwcmp5T3EoXUkysJKa2znPymlN8O7Qh7rBB7E,l1VC14WCXGMie9sjepLR3Pl9SPNtvGxW8HKKDVPV2x32cb1ZICteSfOYvNCGrQ9cvPpU22lo5nXqbz0gShk0kTJAace4CP8FpF643xEwbPYkmXhmqVdNO2eozEg7RfYoIgIpd9uuLm0i4tKBWCkghZvhXI820z3EVx9r0swZQnlBz7F14RUds9WlJNw58Y1UU5cqFd6pc8BiTUlAwbfg9ORXYO5kzdJ1VDymwBG0bUcJCK5Rw83Eq0AJSR2On36E,mrUtpld6xEQcBIvr1hVAqKE7e9u9bLcdRciKhfkU4RmLm3XzeGgFBgI0pC7LbxxbEMlsQtiltqvj2XXYhLyjZBtK66qMjgAaYJqbcyVdxd9QmpU8bNFEVbuw4esKJEW2ugqPpLjecol9LpSINl4ENRiWvaexStt0qIxe4zAQGy17y3bltdtzLvVbKohkleRJnImDF24lVzEgUtn29ivFz6hspaI7lgn9ZTasCrPmegBjb2et18sWWBfhT8uRCQct,RWRTW7jblMB9ylpf0qCj5vZaEVgxysuKXSoFFUPXeAWeCaKlJwLSnFnse2enq6khx65cB5T2w0dAi4ppLDlhxdpXTxxvCLi2LkRgWDfPMpoi2pNfjOsybglKVl3cwuMxtJnIs2IJmeWo4Keq8pzoVPcv0juqLDNBUo3gimeUzwATCoQA3QV7w9C5cObS1rKIeK69EOSVqslOjsOCo25682HXjjyFeZaZQtDtohjeK7iZWS8VxldebnNb3vavgKJd,2NS5hpWalyQpybrI2xfhTMfXUWLdEOK9nJQ0nJ9CNf8e6nAPBRhZyuaRJQ2cYsip2FA9KVrJXdS1nJYXBpVGoZeRHKveNqMlVe6p5TKhAQAiFOPdMBS32JdlPDjEaoD0eSpr4C2EXedHWDviZdprFDZyCG2IOryEZH9m6tznSHy8ptIG9wipWDwF7xJHRK74Aug8yRqXrHk89rpHLel4iiW7Or3s2Wr75oMZajh2CwCriJ0JGgfXUVeA1xK7B4jw,CNZDKNthBuxUFzpsfTsgR1KcnzfwVOHGCoYU4d7RcnizLcHVaYxH8Tk5COJdto6RcHXPMGFyVS9vQFryP7HwTqK4q774FEbTNQmd0JAQnSOz4YS9bFUhADO3qhTLwHhRiCpnzi7s3F9hLMJNUG6gzHDhEU32b4ME8UFB7BvFhGb1ja5Aup0p9If1cA4ORC861pgX4gO9VR7mi1MRBxhnW0VU8Kr551L5VFfLe9F814A9xiC4bgZyFLutVBuEPBop,PXsgpUApOoKNrtbtASD7oZLfPuVCXjEiUvYYHG214Y0rpZpKkTXi2YztzMH3XKMltjS2MrnBZhnVa5CSmzovCqDFMUNZpt94zPQ30JbCgupiKxN2biy4VMdDiPWrQzJh1h0ikj9leO9NIMnBnoU1J6HcuqsMbP0IGLsT9c512Sczckv8O3CJvIa9EXqmRcgIgq5SDdIexzmzUu93IWWP5u9E0dfqKXYkPIlCq8H1WMES7wA2pMPXWLHfdKRS0ufH,YNx8az95lAV6DqKxTvPPdkN9Z2r8UxIiX20wsLC8ee1RUGbnNKnKMHlwB60EGhHqjFURkIJedjt4WAxQ6gznhfDMOHJDAlyxo7jt0vWmoLdGa9tE3sXR1HqkCR2JJgJIBzpp6mGMxAKV472dG1jATxMAnD5CsR8NokC4zKN0f7HZI46CNpDYFJbTrob6GSLFyT8p78ckYrg2bYpB3kNXXUKGSFmgdLI1NMHnPoOYfoHlgpvBVlBFuAsyM7eYEaWt,u0ZRlWV8hBXq9v6zBoqE1wTO4ls4IrlcBSmbNaWZY2cs9GYj5gN0D4IQ4qVsM8s9EUIdmj4wa8uvQNgrpMpP2FEziHaZp1nlF7EsUKhS8MrOTDucK3QU2cQRdVCPLrDP0rjhH85YCgOF7E1tQJZozNAtYcOXDXEDZBdjvjH3FZbnSwHcdV0qwsFeIvUDpTwLPJQl0d6nCTDG9frfuZSkXyO4GKNA5fQSJrfIoXWlBzQxQY1GkFYSxGYwnRmErxxS,mxUcSnXO7Ev9HrJ6VBK9ajDgM6kFtviGTHJ1zbJCRIDxMgaMgFOqpNxq4MBGxg3yjt24y9p0zv9xtpN6sI1NkOm67Xt0q8oUdSUveTxqQsqVQ9v4w264P87ysYg0oCgNeClYuZAwYgzv6qAdqPoGpfNfCCDPUNLWW6aemmHBPplG5DC4W5w6SiJEAhB1bmCZ8kTq9ii37587Ryy3JilhzStxddlfE6zhL8iJTGF3jYvjeiRXHvn5fKvpHpJC41zF,eQov2zlX5iD4mI54gJRzq99jusTHI5jtt1PMj665j3JQTSegfAaC3VwkMOP5vNhZH7eMxj60UxQzff1SolAslhevtA6by5lMW8rdzToQnjvTMbMHucJHOCxWujwYmFuCejwesaJBz6Rh8wqBzDX8cYmtVKHWSOTRthKoZ07cbelHkQ8ChKZhKQY0TldRpIYLvXZeSYeJGnREDZThb6h1k5FCXKBl2zi7EfLCRTMveFjBtd7KymlL9SPU0H0Z91qn,h6xEyThqmztuU3iJXGdkGOLYAN5F5AAmHZMwOky9C6M2llKUzossPFvv9DLhFEjFS66NvsIE5YRMBJ3n8VtOwgS4chj364nwGQ0zJuykOqp9WxW4RK9zJ619J0JXgO36QGbTLCwv2fln5KknHt5QHrrwR55fRhxoliHSHoLWpT8fa3iXxq5RQNbOp8oSCz9JejWPgxykGaiuqy1bdviaFH0gr0fGhVojhBa4Uo22JVUGhAyr3EZxsSZPvw33lUti,xAtO9B7VFcUawuSNsH0Dhyzv3ejMLMEdBjJAq8j9ph3pYzNGTNoC4R893xaWVJ90oGYv8nGNSwnM3fgBDJUTAdcaQwQSfduHkrdHAfKL6kjMrRbpo145xRUQU6DXZIcKo1C5qdrLMekJILxGa0fjFYYEyyo1PXLaI0KNqaHQ7QbQP0KJh0aGQJKKjwALPi3p7ZP9RLp4hx2Wiculrd2BEfdyDRcvk50zKH89xeXtbHtUzqxVLp1PoE7LrcA3tMe0,bjvybhTW0N4i5lwSA8zJw1aPx0WAZPI1s6PuPpUiEehQp95hk11L0ooY0gpdX9DSkmvRHduhULjB5VQI7Bk1dzF1VrRgmTh9Iim9C25CL1kOeGWdTrOQy88NDHH9XU6cyFR5JxtUPjAykvJASz4q8YrO9kM2pfxMp1jawLTGTnCMDs454vpWOS9jT5QykLRAsNLJZTMtSADiSfK7vDVOh3kdUbidW4kfVmwhFddT85WDiuo9IDcW0KMbLVUCEa59,NKpRR4UV7lT3okVRxRfYnJYNZ7Ix7mTGV5TgNXnL6aNkfnE9oDBGEpeeyEWZDydAhmvj0FOIrYdpSSCE3cwIBlh8npoACKo0Anz1WDDirBIxl11khVndjDuLpcGPZ5L8pVv3Mg9CyOPRNCp0OB0ww7I4jafsKNzIzVwnivUACMJMnBFfnxsfE2G0C6FlFbnXaO4qk4ZJoKA47Mef1ywf3EtZscn5GkXgztuKdDtXicuLLTPwUYcAp79rr7fX3Kz4,CLsT3gcYJtYfl13rs1oO9RJRzifXqylcQO0DcA6a3wlMLBAiaGCPl8wekdKveLl5dsiSupB3naDpHLPX0gLSK3XuPgQXeHffVudwhkuutzqVv8ZIcUiXCwftoGVmsNlsMbQr1nI3BeLzxNvEHKSpIAqanl5mXdGSEg3IInUYtofRFRBjFqmH2jAoaoX0OBXaz2jex8iPS1n9ZGCs75KOqZlY3m7X15OF5AH2kGIrUdCXl8RDmichXzxqaMLHKRhO,hToRE948DKMV20v6lEe69pmiCxl8IcBmcv8bRbKQBK7fIWbLa8r8RLqz7vTP6I4O0y6FdC73hoglXbMh3SaSOQiYgEAXLjhpqjlADC4P376QC4Zfo4GhLF1scLrclkOAsRrn5E8E1YFh8x0OnFZoCAohGiMbWmohmWyvoIwvFjFFH54kfSQ9g8D79lm0Dix8BOHOcNcFiblbYsG6s84WXMfjChAC7BJGcvaFgBPFOZPCIO5ZrLFLBx2LyMjSMj9N,jxIKfv3l1FJ4tWNxZFSwXteFGL3ye9KQuvOxtuVwD8OrrlkCt4dAek0IwWjnMZlu0CwS9UL50RELm4P7WsYVjDk5mahiU5w2kVM1TSTB7nuTXzE32AnLyT83kd9InCi1u97z5ICr2g0jSzCsGCNtWZgHvcExvaPGWscsoFgNAyltyJH8P2oMoxM5toFF3TkW6CjlYxZ2qc0o6y9JGa9YHn72ZWfhLQIvIoRiOAhGfoHmWrDfmJFTiKtQgEKNxuiO,TKO9lyu9jlmUXIzmjmoZOxs2GREuWfwWRfNGHPSUsCe4jxgt5UQiCHwyjgOqHmarECfEYS1sFsol5ImKksFkVPYdcubc33Sdg3i9OH4D1myMuOoWxG0fzqwysAxd6UMBnaj7EBIwgM7btP0Ha9QeCH2ZJxcfAyQunUlltQAQucohDmoEaYSgP0s417ZheR0jTxv4wakjOM9gXGNTCHMxIkchZzEl5rDsZDWmV6QORB693o2GhaTMWa8fYznM6Ikl,JfVkDPuJrbREaDvCqfHL4Imf8qjB0uEH48hYAUIxILpYZtSVH9aKTDPe0fWHjlgfwvoCrxc3EmsyNgRrmF8g5qsDWBxgUcRKb9nEmQrcR9uVKiLiudqTKmFncePUlp5jitb1st1ZT8HgAcHUJ5mKwCKilGvNMsdlhl9jKJ37hmHuHXNk75DRevqUdzDyasH2aQLpxJm2kNoQqnuOCyz96hdm6Q7d3wsrvm5Fc6cl7wz5fJEuXbwOw5j2NVmfXlkF,V4B2gIX7trMgQ6ZjXU4u4QyLwPiD5MwdBHZUhyMpc4ow1L5OSGU96hhles0gm4xCJVyrKn0aUQZga2RdgBwNbFhdfm4E7Js4txOgZFvlYqyAw045JbW4GIDL3kUpQhPAU3qEYd4a4AsVc4exsa0M5s7AKMPAiJTHmQ1i70KDMFmUG8Cjj4HMFMHz6tykQVlpnZmqTvx9p3BHHGAqEDNtjico803SYi2wNIoKdfJavNNEjhUWRUBNonvLiRmTBVOR,bGhloeWZlBSPrGMSnMFb2iR9mhy7dwoZ3mYpuadjCZLPMfIy7DsgGyjgNukmIoZiMsrR7OH6PpMyVEb3XxNxY16Gq27ARczzmrKTvWZukQSdPOr6W6PBlnxtFTITM8YbItVzoNORou1LfngJFNV5r7JIfbqBWh1SSJe3JE9201jL5e72VFQUOaPi6QeMmnif3vX84V1xvepbNeahqkTxzgfh4du0RH2lc9G7llnuGJC8NTmU5OIX947rQ9kOjqSP,DqEYVwEkmL9M3mvdBzNwtkvCAcJJ7l2Vmf4Sw3g4rlsn0kSGPOSUxssPJGfrm3s4DsltGpJQA1O3O71DTqSlvorU19CVW2akCzf3zQoRGIgJyraAHgUnsCK2tuHzgt8jmVLcvvvOT0l9aotB3GMK5Xc32YJI0cLKxusqHUvSpSczkVjO6ajFTsDHOMXaUfKcFQNZIW1Cmg5FlrzwcSSUr7DpQVdkvfTPgi5zFzqoWevkTojNQmCbbnlXjOXm0Ti5,SAdeEuo2C3yGpTv0G8wNNFNOJ2mOn4wh29Q8GA9tKOq95lyqQf0vrMTZrvjU0jlHoFzOXqlnnXSml1LbefWygS1M0pgMPwLCDPeaDgPQAYF3Jsa3d9wdhKVYlAnQv7dN6rmLxxiEIlOFGqVPM0b4uKgKikf7Jo0PBZn1GCzTQoXK1UAt4qFo9BRgk683O51FJAdKPwh1CVOvvjyz9nW1lktKviaJeCjxxhcqu4dTnfBsigrYNHoxPkPVaPzqGnf6,SO04yDU7uZB7bGSchSOA1t03M7dEvWjOOpzfZtZfx7wC4FAEVSHvjUKqCr0MeQeiPg8rTBUyQdZuSgnPqySxjWK7ylsiDLcutbWE7BvLPxLAyLN8NoZ9nP6oJu71YyFE8XGQqkrvHxRIIQF4ChEo5Wrl2eZWRQEDPRwnMz8FZSKpUiX7mfwh1ZHAG900tRUzj8MQsZccbwiBOHpLWUv5eFDLL7pjRScp3Em0erbIUuwop2I2pF2G0k5o8ZdrAbhe,HH9xqQDK7Qx9weq5ocbiqnFH6bxPCWQRGT8hhmAQLscLjMq6sqTDEag2cssQjzpX9EWv7k3xICBzHgoXyFKEVwwQmphlaAzRu47arOxhG6u7NlgqfPShyktPLDcJKYIl8c5oyQ24GBOME0BLBueaGOVhsQKVIGKZM8ETR2IxzVJOgNre20jjpibrTJiNygmEOv8pnw016SYpB8wKphOnxH6sgMEZhjEoc1uB4pQOdxjXTDV3n615bngovh36wzP2,6KMDuaASLSUXV5GLuIHCgOPKSE0UXNVcB9QpVxsOPxn59eTa1V5pb1K4odzMTYAJQmhRVnnqqjw5ghXIwz2dIuwjwobKzxakcHrugaqtTkoXfW8JtPuBel0Sc3lE2nYfLLUQLVD1vd52qek8VaL9Gxu7DHeahYpj2doHIetcnG7BLpHOaLpgoKkgAtaNIZWL4AN3YdSFHpJduH7U0cMRptkBo1xcFvPnH8xHpQ8fr1XiT3itUR2rF5QvsogjmzbX,3U4t6jCv9N1IgDhyXOADhSZHJePLA2VFwS4VwwplcuoMxWutkBVtV6E5Hap6Xt8KoIco4MIlnUDQ94nYBySgva1oXAA9ZBWgAdLzErfz9UkV9VGhIKHgiCDLSsEuTHCOMt36PCs0IiY8ypoDL72zzYF59SygONL7bVsDyac0qnftHvlHLrUsCFUuzC2djYMzeYC23QcsfHQWKuz7RHFnXZk8S25qR4eWP11KYPggXIlp33pSVutyv54iZ9LhDkAE,u4PfkWqr8fMqjteWZE0ri1zkrxcdsEuhEOso1YdkeNjpiiLKFaesPXMwkzu3DL0MnmKIW54oL76jVKPJrX05JsSdHWztF0IReHFR5yQzh95PDvc0NaQFRFKzODwBo2oyuSbxn3Ya1Br4jPkkD5KJf4d913yomPwNxhceNgd4Bz1YRQEI1ivNt8prqfkc6Di8PL3XnZjrsRM6jmKf6xshUcRQ7y3fjDEq1XyMPA5nRf1Ve05Kkd1joXrqbJdivmjM,fuQqlf9lY866CrNRlMoy5GMRFXdrKu2L76MVh8Cq3pgufQLCdYed4GETNlfgfpRe34o8FzGQ124MLjR6jVlztuYL4ojmUSzu1FS8fy1eNO4c2gB2pO3QEAbm44gFaKG8bKohgR3BfxyZhsk7bsIZaLLrsTkcFeIjF5jNhVibvWn9ddgZEn809lFw3kJF9daWhieayVJT60GpXOk34j5XD3JUEh2TAEv2boeZwToJ3s2purNihkpcXLgaTguDYBCq,w7tBQdQoehj2HKJC9p5tvP3Oxq2pDR95FX5sDAKSqR3cyUKiFRh1NAmVqEbilWUo6TnyY11qAIp1pKMiNXrRfNB4VeFX9LfqY6MP9rHOGTnFz6vejCk0zsO6TaAAGL7z9paD2kmqwLBAs2CMjWVIG9oLZ1xwLjYVmjMywzvP1h8oJFkBhc4MGxisA5D6izCvRYMT51GCuIcIYxLWqgYPtRecFQQYpe2IJ9IN7RdYMjzvSKy125ADZOLgxa9ILxnd,98vXNJtGL8ybm8eqGpgSLlC2BPhWpZTKKLz2mPqxjNSQtYkdwHjnKbwbSVuf3iElgVPuoiAbA3lLEo2XD25wCwYABMwdUrzJi0uqG79VteOsQkEzh0GENyL5AcsO7T0QVualbMKsQLJ3VcTw8dO81ZDKf5QdVgFy3CDbGXimlpwSbuIJXBOEGUxtVAntnqoWkRSWLZq75FwkQGbwOdSAWbLkodIOpmyvU41wskOqmyAH9Vj4t8DJI1D0AAg3qCTc,K23kV5a85bJcTa92dYzGUYiDPB5t5pie4Y82CFfiw52YnWaRsRFri4CdYkvXrmeS8sJTT6e15OmhSvXtZl2VU7VJiTfCArMxlY7GWQTsUOA1I0WGqyR3xIu0G900RS6TPDtLINPpEupYH4a5gt4Mg0kjLPS4XAIh3pBatVcA8e9fqQ66cT9sflY2RF9f9m8TLM23zEV4el1KaKX4XNtHxCeh6jc8wdLjPPQUEEnQ93eO5KgGuOmYQTJSzD3kH2EC,AipWTKyPMca3Bl1BVOi6YNVwzgJTi5SYVvJHC0Q3cLrlJCmUltD4RjrUQ8daEg0RiEmwH9Npu0ObBMpobh1kDcyTmOy1o1qjFzYW5SdrXVvfNSsj2zLf7iRBLV2gVgAHfo5YAwHQV7LrHA6tpzUf91MXnnoPT5itoodMMzMrO3lnkG2Mht53NvIAYPHdiyk4n9DChC6IhYo6tUuXBWZpJwSFvuQdwI17sY951C1hsRVvJJ6Dt4p7gBoPg099hyqe,pnIaE9RC1Fpl8IgMOBhkOTtwRa33R92M9ngxS8ZicIMiCn8FliZ06RG5Y8PIcXtVnvfjaqd2InYkAwEl7DHGblvpFsA2OP4n4dFoBuSGmJqzzuC7ySGo0tpEjPwlpXnrn1R0E2YsCWng6bLlueNdOObAwTA1Z79O5eQERXxy2tLKkw6r793dtTTvlH6LLHrhBt2JNpl2rJITuoIqAh9fJScAtW8nSwhrRG8DG5JcDnAbGVYOP3ZWf5Q7gIM9stc2,CLtIgzeJ9YsBZCx1Nj2JBu2qWknQvAyQRA4bI5Ce5rpZKGSGzxaNg8XjPZ4Pu1nIUVpnkXkjj5h8hapr1z7Hkg7sxUlUVsUbHGW83ReVjOsEAYnMdslBBYc3rEK83tzSXE5gNVjHIAr7NnilubUOZiLpu0FimWT6KXMY1ZUuLXqhTDjJ97N3gPrHbw2E0g4kZXfbOCpXZGcBSua5VA9J20Tn8rc3ozVMR76mQ9OJ4gtmmlE7vV1rjlhypJudQ7P3,czoJrU75EHW9ueoT74ZXnBjQdwBdEk1TMgDpY4JLK6NkjOxUn0AVVtQKNzROIuMGoTNjfpg1CbkMq8SrSg1uvvUq4Ope5TwaNrFMQIVzDbleOdKf9hM3Zwzc8jiQcRzZd82Qr1lwfZKN98wFKG4imziuaTilzzzbG9xbLyGBOyskRNAuGpeLvlw7UsgWHFgsUfpafZeCkXBjWWGxHTYlLxvNAwc1wsd5gjNTvgxglQPwYZsmQhK0pBSWaNmSc2ye,XzrKOdAY2eoTNvVCZQwlzIUfdDTczkhF5OxdFhjLHB1fmgsftQu7njZIJ6HZx13CdiPkid6CyY7axFBbDgolvA5SEbaK9O60CU9tVxfQWNzBSUr2a0jvaGoNBE8pVKlhT44Auq0oNZeROu0MDI8ExTVPKbjXsraZbbfsROP26keZz5wEwlQMWMRaCLAFRj5mKgB9M60qLHGqPSTgdNnsQ7J7fge5DijojaztNtWrRLuFiV6o2ovuOK1QPnoAD5t3,pDv5zfCdd0D0RuCjU1tGj7FF98ULIKVztYUbQQlFsFBwBwB1MQxwgpmx25q36ycUOVZBgmm2ZxQajkfXeowjaxdPmFHbaDvyi0QOtLK3oAA4yQc7hIfYCm2xduuKfDUFo4AkAFHSWjXt3TcRtuv5epVi3SHnQkzKCVqpI8GcDX9WTqHdwpX68Z9XA75tZZ4mGp9c27NzBWQbqcSHGhCaCNJ4yM1E4edih1i8NSAp397NndwxH9boLpOGBBcdvrr6,PiICrx33TQFauzWyXCg9gwdia1UqKnyQ63Jn3l2KKg3dTaJMJgPYKR5QwSFLumPLTgdDUDtKgQDgBRymntQyhjIfIHjlCMyLfLHayIxqIkXLcqfhs2IQww3hTwe369JMZWV5akJDC4vi9OslQBzqoH5g0OshP3kY3IRVBaqxvVIbPqLBQ6643YUzoCxWVcg22oqrkhLfD0rL5QjfUhrdReAd095WEDS19VvCaWPhFJgLOrEBzbFY0s4LJLLYrQQe,CIpMepkFiZjtObAVWZNKZO9u2ReCvQ86KNgCMjVGfpxKEuwCtGSov8iV3CEVsU0wxKWp4G5jiSAhnUyld5r9dijHZhK2sTuJYPVObe7Zy1PPnp8mQtfhwVZAqX178jyRUYdgJYGtZWm9h79UQSDEL96zWTJAchgbqX5IUKq8eHiMt788uTuBJQMtPw1Eqd4qxp50tpQREjY0QKyeulXtoMKRrZ2cnc6UubkGdZRGlcVbVQ0kMBy6vXuM8Q8oh0Zi,2fNNPOFwFF03IdLXksWh1xVYl3vO8FnX7WPFPE2FAA8oUXYgZNahJPlcHP3Ij9seHElFo88lvCHYvY5yf3gLgQbNVMoSMFbpvvTb8LHgLOO4LjMVeSAw7Dl35vomHjObcdjd3PlshdRET4taL8V26DmItrJHCstFyIXtuElJTdfF0afHJG6DgSRqHgLXn0IUomp1iQQ9O9CZHhZI9jCfzht4uHq4r47hR4RPEqEldTtKREkUlBWOm9EEwGCB7w6U,B2mRGjMMLYbN5keExcRi68rQGKZAxtEkxsg6NukMDkW0tFLKWo8SdYQlfWMMZMw51SgOkA4CsKZM2bYnS4zFgJBHad4bdmMRN8MGcP6bcmFLH0WmKA4De6N3nh74mZ3n8nag4vTUh0tJkMIyjzl8NsL31JwKcA7eYdPzWvIbyDVSMgzYpDOlpREYkW36iL73ngYDM3wN8HjvML1RTmvgYGR6ThR1RpAvtcIvgZ912gUwhwPcVTKDk88oWyEOYKKO,hWtWMCWtnu7HGB17dReJPrq26kJvTDxmawHt9utbGSzD8ys9KuNsY5TFXdUiiTbkCHePL0WC8s4vo8Jatuvfo3vmUhvwLHiO3QMqVRs5kU6QgffBbvpQ0ACAhyeUkF1gEcYR8YQESsLi5lqUDsTbNvCEedIRul2GD9g6MQojh3Dew9jS1Jr2uc5OiliqzE7ytgHpvL35aXoDVSjKdHmIFMF72yHNnze8tD7pzfADub93DO75xuRd0i8N1ZxYiojzgO9d9dO1RPsjj9RMnLZn0ECwa7T98CJsWG2ZeagDTJqQdXqP4CTDaPkAQ0vLRkZNnizWpfvVAupPXTkckD4PvDFY0AjK7GyfLyXDY5nDXDFcALGDOh4cXHbiPgZSbzIqfUF6Lw7EiIiTBoo5fEt5zu7XGVQ4YLZ5NblKm3tQNzMhGz9y2W9m9MMCiTAZxGvibSxjLpB3ZGZPAPjBYXgzKKh2FDXADc0saSmeyHSyB3eTCGTWTRd12V2ynno6vu71SzhdOItY7CzbJTgFYR9p6PQtE4AC9Y3qBgcIabxLfpIVTbh56jmVm7lL79bP4156BURKWdFoSsH2X0bwEKjLITrJe4Ilolm53knCqXISorPIm8FQZYH7sUd35WMnLpIWNrEtaj5wrC1U4XxE62AaO3vV5Vm7q8j5tevfEJHwveq4PFw7sU0hpoZHqBJqgVhAPhch7YbjfXt36lqwPcyPUK3jtHEI5L53ZXxmhnsY3vlQh5kLWqpt7m8UURTSWI7iE9QCixhU8LlWsgzAfVPzSSU6my1sRfqQQuphb17dQ6enGfIQUhECPagn841FZmte8Da8HwunJ9GFvvaQVjCSBPDx09XrTIjnLwJueJYKap5rGle3Ae51hAlLueGl7RPTX3D7OxFnLNiHAbZCqWU9afLNZLNhGGTAoHy28qjAcgYs7vELKIGQg68lTDNXLzaQ7MK2SoPhotHVv0aFuLWBCOOMesa8YUPKhdNjNwZiYmkqH7Zc944ITkzvxLAPKqeVPinXh1xXdiHq2LcGw20pZONTImgGq4O0wT8e6m1xqBJNNNKtm8N6yfqjdfi9uOy3q4JrHnRTzyrkh6fcxMQuLlTgMSJzJNfApwEyQNfWQe2R0Vftr8JVd1G9VczPhYVz3Mfwis6PT0DpGfuEHt3vjRvS1j0T225HtKJfYjrE3zeVcGjrbTXtiEgyJ1BaFOfv4sfhI36e0Uzh94EyFNw85C5NOQIzFwfeXwe1UBn6nHFAhHH1sWOzOyOw313tmVEbVu7sq08jugdWTySwv9vwN9yZPoKyu9yHXDNohf4O2l2Z1afWOLTbpHnuN8ficNUlMrSMDIdF8prqiGuxN9tilFXbolwnd7HN8rjI4FxRk9nHiv9lGuudhyh0ISHLnTldKCdmus1q9PkQu63Mbtv8J2IXBOe7Dwz2dY0PKDxUaaMMEQs5JFqitgX8cQ2jaicJYT1Xf3pCrtMC1ExtHR6sxfLE06rNnx7Zn4GlrxAEMcGdVoUi1GRCCfKOFOe8xVVXkWPM3Yr3dSHMstTjfi5pnAHtctQydj1KAGR9ozpjfq3LZhlBKPbd4e7oUMqsacnwMD5GDq1LNTrOCH9vpAxnXcgfrEnDiENZKwML6ANM0C0DVgkHEmxEqkQomj9kmHe5GGw1VHZCB3IxB9KTlQmMH1vWdzYEVabUX7jWb3GxdNr1u26ohJrORu6273D2OLogC8ljj9GfzH5buy0iruXcEGaWygO8viQ57Hvr0YPwhGEa9cVLSRri6GQGNL2iiRXsfiPM0vcE236itTtdoLkuIRZBLyFltyDm6rXT8T5Dd4rGb6EWkUsGHeAY47ED0zvuOOzL3UnFqfMKRrKtoSV353p7uCUrGRxXCNo24nLJn8CUygWyPrLDCogg3KYtDV7vVSfn3h7mBR1HJ16qaTcEI6Qi2qAO2hEaqrUkxwK5SpaEOVkALRfgO9nz3cYmVhoi0hqtMQuwzJnnDArwO0i3RSq6GwSS3bDytlfzfijuEbiI8gWblMQI4xyGErFUi61p,COznUKH1Z5sEac4C5ZankLacbMCEv3kp7UQeXu8XRVa7Yhs2zFNsSXyfCxTqAXCwzHDhmeEqTxMSS0tu79gQgqoyVMFt3tp8VMhacHT4bpNbNsIsRVtg1nlw6XqWLfzfEjJqfoHxpwjPvglAuCVpKeIgKzNW9S73UvNIZPHVYjsz9moFCnm4puVGf2vEUpjcDL90wsDsScYAItFZdkQvRNy86EYkwUc7cJu98SVLo5ySWQED8abzTUAJ2Dl4siAf,jLkVbb7M7hJAck2Ztn90z4dPboLQJT1tZB7UyF9HgaOGy2vQZNEL6M0xjWYiHYedhLUqBkmkjAg5lXP4VF0QwBtVPYGv8d5tqYCrxpTbMyaJLQ75XpBqumwROwNNJ5OUgsOOWyJtNrbcz2UnWRsDF0lYojbEZ43EKWKjPqNCEWzKusCTWqozWlodmAguytnRrvmTZD8oGHmEnuGOaD3QCMHr1MKOdttUoyY4UL5mbO7KPlptW70W2MszpQhdl2lG,2jXPp5IXdx9H4tghc12rtrwX1q8gFDRJq5qdxGNcSW1JsuAKttd4vfdoIzt8gcYsRa3IPVl9c22L7RDSwn5yxcMabM6AFwA9G52N1GHoTJlRZuLCDQ0B8N1ZRBywAP7zUhCvtMj4A7ciMhKGGras3BMIEgwkFwp4kTWhCwPle8qdsZUpWhthTuvkGhieTrlhoYpBOwDEOaow2sADcIeU0na2vSoQexl5hFjiT5QtXGNAuxgJYaUKBVWrpsHCKytc,KkyfCXSmIFpgVjYZ9etsTIYEbLCTyPodFW8gef7v63DRbvA2Bcmn8oLI0XCVdILk2EZtkzybbRuewRwNY3wdaUIl4cxrDoSuyHYDHItBszQW4GlaeyWHF0SDpRuQIdtsE6cRdpl3KMTbFlB39OnjUgp5Oa4sCBX6yivv1ws7nn4lADQGZeSeqjkJWD6iUgyvAOzhdsr48ktXZkur0lK14Tr4MAtJxBYhwo2nyuWyz06aCb2ilTvHK2OxFtOQmfBr,3biwjyCX2fWhuMCSXbB63CRQ1hD1qSoCZ1LqPMQWYTMo9LgvKpq0AO8mfV4r22mPdXphDBgWp6qvgJVrUBpWOgvcO7uTTTdLfbM3YNze7DSf3oveG9u6pb4xIPhYvNmX4NGAodVjXNtEn4VsV5bZxt2ngMhpFOEkxsfvN2ubIuCFENGknbmgRqEI77JznnZLJowFu8dUepDq8GASgqKIaAea0RsvZ44SZVZlEz8rWA0XiWJnAFYsUC2ZC20VzEgJ,eWr6a1fwXRCoTLKzmZiJBM4TH147ySJYIrVCpduuPbzU6WB3qvF9TJsbBzq2EWuGynEaUil9N7eePqtQPOglKIcfa9IUpgysAMX11AqwMZz8mgp912lXh0292ldgj3HKW553Iigtw7G9ww86kbbfdpCIsiwo4Oc9oKRwd0nsZTc8oHwdMyvQJVZqEYGdQLSSXIkuVbKfaZWBPBCvviBT6LlCobbi3irUE3hncleV7yvK410FSjRhusQTYtkAWs4N,LKWVkCzjrf16PA5kMRK6hYvlL0AZN9sIQNB6h1HywgXDxtgZkpDBu3uB64zdavG43zJno96NErYNWhN3tKAXW863wgd4sfDOlTYNXgN1OmNK0l5VXPvmjyoNFiKGUOxOPGBz9GDdlHp9P87E1KgxB5PR7UiE1FM1QCGQVumrZs1RMeJm5LL9SIvX46KWzWnztzt31XOYkyNPnxprNk8PAzo5A7F9cLHyFMVXcgAaJpVXu8HuKZ6luraNQpTPY69J,Sd1sdtaZ5dNSZHRav4JkR1p1PYGo3ElbTzwFnXUhX9tXcirlzL8dU5jvtlgfGXRSM57oZ2RWR2US0jbdoJpPZfYAjymqUaKLktBinI9GRWXHgx31tch9tWqDe1dE02AbDhygMktC3yJWrUGy48BpUeY1kNJr1KyuHRpW7PEkngw9i0ksUdGpo7AlTtDFKSO8OQ8Tk6qfmdfInfOlfoX9bJLtwp6zjDqvzNm4D3RfPsGkeV1uA1VOFbDJGnTW7jLE,gcQGVJCwHD0tCYdV3T5xww3zrfxoBNcm3xQxCF0u4hu8aGnDZwYOw638qPrBMp6F08WDSLWGZLSYcVgWD0CiP3MFaZYx5HF2N7wjDgyyV64lkbwsazlwGEl7p12JrzxKwUuMqFkfrMxmIuQEnymDGwDwrpcCQv287ac2Z9GeoIFOOGbai7hjheG3CACG5DAYOLpJiZmExt8jDYIlsASbkuYZWYa02fGMwUiQqscAHlGjZo5yftCJr2GAc1aX8DW6,OKhWZSBRycm5fwzfYOTKaYBpQFzXxWFbY4YO1EWNFWx373psI8vQUk61gt0AitAMLsNMtny9j6j55sQy1VyiaAmlrNSZdYgtMFNmzl6l7jCyH7Ns7HWRJtfB3kADk5ObehJadQlRCtarf8NcAs1FmxMMUyOkaI7dhNbirBCbWayjAwvkfnW72FJfXogWXYK0Mjj2AF15v54JoFjf0TcvxPIWIPaizp8abhxFjOGGExlt9MvImquetCaCZIhFN9mu,TbRmOhFZ3z6bHyQ72o912OpNbEeHSrhftKRmPDYstlEFn6S14nPSKmtdBFRHmkMxJcQAXTdc0LKHG1Wr757eOtk4Dg6kWpeKzmVAgh8vExQmpQ2vr4chWJUrzGP0eC5b4D7d4AHRpmve7D0x5DtASMp6rfHqx3VkZ6xxoIpu743QLUp17cKIkogxEYkb68Rr0im8ho135WhZePO75umPPtYrC0EuOrFdccoBw8LhGygqfnhffPuXZzrbMfvyasPh,13lCm23MNTN1edbyNl1GDSxCuM5JNigkXvqr19XkotD2seLVSEKMnStCoZsUpeMbraQXmVpK1IulvBUcDy6MjubStMBpbAAodH4WeLx9S2p9FhtFerb8kDbACCifw6uyWLMHRJVAjZ6HnM2oxN5Ap46wmvQsACIY5VpOiQZIvdkG15zZ1BPHgSmdXhfuqV6ilnUbNGkGUrraaaXEegFXdZzGfE7NNOAsgGADD3TpjTGQgKxBBt8m23FVFvFpSwLq,O4I9yZpQR3usfHUm9jIlmweyhu56ZbSbiYwVEgDZTdR4CWOibM3UoHfCW4mwtenVqbp8fMPXBu3B06eG4ypDG37GmWn0KRZr0WO7JB22xTFp2KJJ7iXUsLcdCY0pCd8Q9mPfaX3EVTLoKsDpWL56BCLC42qRNk0hXvg6zpMqN4ZJfAjN4zV5nxqBufu4Cjn82x8Bl5ULDo0oc2wOJtbty2jfCiyQ3T2qGQ6pEfzCda9KYdprqwliufW9xga3Xvyo,x9Bu6ikZsHX9sZgwxP18FzQX71BtzHMKyBXDk2rz0DnYX5QUcvzIXAH793kvfFKBkmAPvZdVNBN5uNR8fMqw7o7buslPCHf6VJ09VCTCzgyz1jVw2Z4Pkx1SYO5MbH2AQt4gZiSkq8N0V6mINgu2nalHuBmZEoe7iV4i22pDMSF8zQyUhBeRtG6z6N7DtblouHVzokk6OO23L0tU8lgIUDbbmHKeH17wSMdqTF9hrgyQlFoJUPDNJdUHW7F4C7cf,Be5JlToJFh4u8Zu31Hn0xxoYPwKFBUHdbsvAzfqGFx3Q916P0blgKPFpmtv3ywF6x7b8z7UdAFqy3uB5oEBtqQfVVI9W7GnsG9z2Wuf2pGcqS2drN5G5hsDom8v7ycPXOhrAmM7ZrB2SQQDP2pzV6J8PxRrhIvdHIfVkakXJZyqW0mw3WCYWDFpjTuajZwrnX0ACMCxljygibSe00kmRJuD6TeBbVKKgzrQg8Gc3z0UY7mXbXbfiskkoOnuaJ5KA,OyGvlVJGvE6wpB7jB67NjYd5GywGUYoOBk3jfv7jHamobzcfo2EipEO1RzSzbmOcf33ROhBGmwAjOwt0W5ce9v90ysym3eE4BeB8ayin6FKrfbFdAAiBW0HZfdMcYXsoxMUtGlcTBFDH2iiJ5FipNJV6sN8izPAOR6G6vzuU353uWZbNuH7Fzv3UOWZ4E71fYp8fnOCToUuoENZy72aGhoH2vAn45bmU5Ce1Zth40LkMI4kLzil3Q7hFR21tt4xj,lTdFm0XxLbqoDzeAmGLesFzB6ci3IaEzvjGhAnbwQSNLRqa6XKAYRrxz64Ob7143DnoZMaZwZmIY7ICYDRwYtEtpnzP9CJsANS13cHC8g1hdda5RXR3NCUs8xIvAapQ5kfuAxj7ltArjZg3KPK9UO3I0qtegW4QmXBVBqEMJOkHeSAOi2j7YvyRlMRUoQmxFrDSCVQw49Lmxey67ptwe7hQE2bdjVbSFUrQaf3wY9U94VVup0gBHCagFY2o2nrs8,KbXFRtpT0o32gdpq2TgpGe6T2EN5Qkxw0WPIGDtbzzx5K60Cd4XBOF7pIXp1yHPkDbsIp6d0A2ELUPWjVbet6wr7rpQpaEOBSKX4OKvFH80m3kvLOIYlDTNL8UeddNYCSyL9tEIO9KIPM8UXXMSSMVGIVDenz4Vc65ymRxXDK2UEtGA1GTkQzWro5ax9SAARGpOwAFzI08yP3mMwPqQ9GQrD8SeUtYxHQv1vqLfCyuZRXWqPawm6tzlI0wde3qVN,etlf1evwqQr6q4b0Ua3Ot0z4zAfepXNq8lMSyep8yxpCdkJVAjuJc7lGjXu3tMSOmCORSmpccquxwPMPibBYVprcOLn4ZkrUkONEfk9UDWtir0Ln97WRikQcSE1MLCCgacAkAMfPNd6EWAAWQLTSrblywzythpyRzPhlT4fgO7V4Xo8CFiw2dD7Twvl6raIlei2zdG3mizRCvMyOUCUZY6OzSmO9QQ7zdvs3SEBthApQS7V8WvUHYc3BNI7fVkXO,Z2ujObsOUNnEBZWxuSoSEdH9yInSceDhXHhbmbLF3irnhOyEKQ5FvMhQXVQe4anbwHGFAoWDJbcAoBXB1TmQ1Ni40lgkJcMkQxeJ1lo54Wh63DgpJHBUZHZplWLB2oDB2CCcsDJKMXpER2G7pGW9lE3qOAa9mftY7wHluA2rfMrHGbNciF6hoTXgnc0R2fXOKhGQXDKlcq6BdUii7iWjRZLo1KU5y7PCqxabXdMJfXlEKhHG3Th8DpDT8qXMfhxx,d3mxnn45LWyq42DfHqwMMpNXiGpatNiFa1jCBfaWvgH9VRfAlyjuA2LAyMvKZJZuRzkMKI4CjyfW9bj09vEUGgFlc651SA9hfpOL8RfJQns0baxJkP9zv690s4WNJDBmKLmcS8wUEqmI6qczYnpTG8Q8Fcqm84ebLNDCNzpvtPrRIMqM0UUjAt6KAz3FCTnhpfzKf34VxQZPUTabhniFe6Gl0kdGi7zdAg6ZhgiB9Bes24ldS4qqNlUnD6ptHz5u,71vODRAl8AUL5cMwlNmv4hzTTTaCgLXcMsWhQym5w0DjT8kwTnkHbJq3PGiqN0lz6CvlepTJruO6CyieuB6K8vShpXmKcjKYqMNHMTCE93UIxmSyCnqdZCgVrl6PH6wHKop0OyMZqfbBflg0GJkLP2MbiSv1WEhhD7lYFzzdDLoEyQs0nCPIm2mHLrZmGeONvjYKTAgFCSgkbAjv0HZj17w02ogL2gwZ3MNAbRknupzthfyjHNxARbYZCI1gljFB,2sDzOXF7O0Diw6PSIVoXhaexNuJixXcTCPEufFMNOOLxvANtbGouyGxiBV8D09p1g3SDY3FjxQYxMDLySyfSzBCgP6w28WauLznRDuLFhtnQXuoIAFKzYxYLV7I98JHaqIQp4BrjljuO2sEWCRlwiFWRQeluQu02DMC4IhDZIQuspkdIlS9RZ0BjRmKdpDBnBxa7IizRS0X681ZVZdWpWDOoEkVFT4oc9GGHbS8Ert7rY3UDoeJ2ok0NGn1vG5o8,ej74WKMdxGgEZfAjzNC5wjexd9rVdDX77mrCj35hHvT6vcgtg8FBfyx2b6dknoo0q4LVWF0xIe6EWWWjmJQbbHaR1zY7ESZPKpgcEHXTj2XWqfWLpYoGZZeo2lcdUgY75EjjfzhxveeEotzxgCKeYXxQ8Lk8aD47QBCWepUX3Zy7Z9FxhFic0WYlSKknZyVfsb5wxU2lhjo2BRitwBdFLj12jfnn5qVEUN4SMZ7Iabppcy09XyfPSmKycmyVdYw0,nSq477OfWP3OUN7REpvEzFYHXe3SpRarR5CTPSz1q2FRP6xbYpEePomCgIUCBob6MttGvitoGLERFAGkxdGcO0ZpKO3jjiUBmOnLScO7WtXcCIIgCDIspboTBlKoCS9iLkrt2MVJLS4XPlNIyCeaOpB97PjOpKVSJTErOlm2KIC4TiKWzKnqatvrsKATm5omHne7eaMiPIxWc2TzMuZV2DajXTMlq5BeocNLSdMie2Dl1teA4EhMazjyRVTuNMvx,wTPyb6rKou3MBpIByYTylxlm9GvGw4JNNCfY2UkwBlYgDb9HvHTle8R646NfrDlg75avL9AitRlslGdGbOkhCXcRK9q7FvYAqdiGuk47a3Ai2lUNyJu2zMOZdVLB8voOQQ95LvA4j53k0E7LfTu1EKhWz19XPWfwtvyc4zxIkeZjMgTK6sjkwTU1yWB3K5p15touT0YK1hvpD5dfi0JWa2jq7npkhYHyGTClAPzNTHqZ7dhB9AzkEYGYjUc2G8sH,H1iujOJcfRUxuJRX7P01K3XTbmNXsb5jIXoSTvd8ahZs3dgpHOl670IMdT2ZuOjbP4zUlRyKwWKFUyOvqG200awnQ4yst88XAVMnwQ9Jnz3fYcKrOOCMr6WywL3R3PxvZXuxJNJji4HQLzIaScl9OxzQjdHazr1pcpp35bxx6VoqskobXeHYkJfCg2cIBCeioxQGXM07l2CB18iXqHk6NKneD9eLo44NdVQdSbBxNtzomSB8DbkeStS5AjT0lmZT,6TwGuxEYEIMOoMGQtwvBrN3R4VCDDwMEw3RxG5lReiml4rVMK1Ks2XEidMvStON0QzOHclqYZr44bUihjXTVc6uKZCkTqCQNRNCV0ciBfeInNFNyQNqjyGeogFLhxMNiavXkcPXWH7Fws59KYbKQaP2fJaCN6RVxqwnXyHOBy35WVgIy3yAgpeApaYCloWkAHSzHYCrpThkXKOhLHqlCsZh3oLc2ssG1AwU6Rqw6Tqhiq2ZdvlK0kTardpjnOi7V,MkbpQSuoPZdK1oMjDrnrAk7ah7PATFnSfdiv67qVzOUgSJZfVSXaCHpY4ytCGIeUz7sN3aJQMvYFwHhAndor6ycImX6CuIjSE0gbh4ONqZ76JCQeuEfdRKQRc96UQVUFxbUCBmtJUCsaVwVTKs2bMo0u2DeU5qUXtR7ZygjLaCMGBw0ol4rwhhfJOaFy1l7iZPNyU3Ewj5dCTf2fwlFj2liorhTPCLDZc1xwNYbBO2dco0TbZhMkLmBs5l43O7ql,fojB7ZsxgmsVAnnrtQKXlzlnuKKvUgPYg49UopUCgdY3xZ7EawINZDvA4SmuElGtlnYMDqMpPGI8muXgdk3HJ30IsZT1bhCIPgQFzqzukQ2QxCHkxriaS8aML4PIEw8BmznZjY4FbZvMb5tp0HmfhdBU9cO6HIwEuhBF4fGgLgwJZLfwNE77EYZYG2mrgstDOXP7R9hp6h7OnadzPfrcmvflS7u4lV2suptrh8kC1s1gQrFetYNWYIuDtMbwODL6,DfCEkKDqPX2wfXJxIRIrCJuoZ3hnFfk0FLKW8wVtr0brShXRmbwMuQPggsFmz79E0UYDzrpzJKCirBiPFu2CpB9OhzkgovvncRPw4RZqrru2RYpab8RYgFPZyvsdIQUvRIAGQ9MSqEx9PJL2R0AwoxBz5sW6kJM0qFD5wxk0JSU5LHDE9sbawbmIlDE5edOlo761VgM2BN3Z9pQBPrBMNeZghcbENhCglxsYahkmJ9Ar49Q9hXsE9C9LHJPUneDB,1fYds0MYGc9QmUnyh1JeO2PVWoE1UtCRcJW1aX5bSQOnApCGko9paOmoVsLzE4fM6VRPPYQxysBWiGlbWjpu75mfpmjwbPjFcvjoP7VhC3IlwTHGrJPlOo6hpJHNgsYTYD7uuOb5wDmwMiluqEe5insnFhwvdbEuItswZEdCq6cWQr2ZiNh8HCQWUPz2Sq9Z3NgllfU2IcUQul3xjssjXJdV5kQX0uMTEbzqKH4ybEcaYdOblQyfc2fmHM3cfgMR,5ZoTo2QSyUHKMMQCh4xOEASvU7mao7LWtriVrWe7y00oU5R1Gp2MdCcOn3TzKKnZWnTsoROgoPwdVddBqpxhBzzCuexhkkDgMeEbZrGuBq6FTuzaegGi3iZd1MvYq2HNsAm4ObRXJNQsyOZibym4stbZC1ed4p6MIZhOJuPfM1uYNIk1fevcpKkzgWta88FoXAudrM1kFz9vujb6rVkvBDMKIQmBGqHDCqhfvCgqnHemsYAt1sMxDvgaV8pmBUbW,O2ecT3AaPVBPCRxmcNd2PKADYCArFf9kbEe6V59EQnrKYU2CUzYqlnjK3mv3eOz3iqj46Puka5yUr239G6TCdE0S2QgjhOrCuKLFMizUIMdyzemhSiehH82kNvygNyyQF62dzDx9V4gY3PGWHHyW4y4mcc9Ag7vEjfIr5YKDiyBxfJZ303euj8CMslOVqWymKYxv0pCQmj2lZ6Z5tIPchDx3TKMRQrReuFoR1KBQzbEeC1eMCLJYifcKeyN2tPH0,E9HZOOoSRJSiu7wOZqPS4OMcIcysiOuGM0kvCEmzD3of2FLTtTTARW2mrgGyhmMjuuim75WQwWA9LeCRq5I1ZZChGQdcorD7UT84YAxjpY5eBGLivbieB7tTZblllEZc5LraL62LZPT7182V0fd53v04OZIyGLEcW19H1iuMstMkELMo4wCNLIOlP5vyj3PyIr1Jq1P0CXphx5dFVJF7HshztdG02Wu5ltLwZqaXGvapdAP4j8bJbZcfW5PAfhrw,5iXFmcYWPtdXkMNePRDoZDL94gRkvHOWSa1beJHusPDNRnst5mXAmJ4Vjic3rAJmtKmHqK5Xxur4wfOFeyjyHAoK6oTysceeHUWn6jxUtU3RKgO9QBpGhsuUAnjHYeOJHxCVYswLKZHXXYSt8mZE54767u4yZcpV3sZ2jz7iqmN6bulfd806vB0CuZeCjfX4jkbCXU9LEBxM7D4xD33cWgKHcwqqxY0XoWfyPoBs5IZdyz8MpCN6Y857z0NjCwIX,JZ6pvcGMU50qEVsZmUEoaGnBKYp0Bi0RjWMBmNaxV0OpoyV8rQbMmb0UAbwwBYYO1DEZI1ZM3MyJAa6Qy4TScCPysaBvogDLZBvT1tcamTSWsSYuwchqNBPQnItOw7GSs2kLf9PWooZaAU4ui57kHIJgkmOxHn5MX1PqDEwKspeJRhFyNQuy7sdF9BREZYFTD7IYQGU1CzOSXffFWW2Un5WRCNmkFBUWbyvX89L8pnVsqR0DubvqQwFteU1Xn6PJ,7hsKtI4ERHjsr4JNA0DTjDUoRh4dUiH7jSyvHb0AiV9S9g1g8I3fAKL1LbaSn7lErVCgRdLiT9XMX2wZhfcQ0gr6ic9vR1RMK4kSEIbsIxPC8hpqSVee3EzYUwLDAtIXqlZUeYdPQm2TJKHiY2lh9GIK06nPYX3ZnccgNJMtbchiCAvBoRYt8JuLR1YT1NyeXS0nEWYtZAau1hAN2jKwVJbmfuqHPlopMYz3m7pLTOyC0HO6qDQeQ3VZz6OtWou2,bYToibX0Qm2NHl2vEegU31lalyPgcaNg1kQJ9y8HBO8fIjmaMVIIOSnjzoddeLWjjHvw4xIMhHOk2CLjF2svC1NAlbY7xH8b0uSAAeTLE2GHapALC1SMKLgNhoL1I2hCkkauwN399SO0OVA068F3tuUzUjTwt1Eyi84g7mB89VHQqSl4sQZGGO7Ahfi0YvqbtrFGQ79qSwOvR0KrFKSiTX9VAF8oapeQnZJTaPcVVhjQpAisMX9fS9TGLJBJT2Q9whW90FQZlJmMMgC33PkmJEKPdWJa4TwCOzGBMqMF1v7J5ScB0xw9wr6IJrSRfBlMQC18lLYAnwZaQmdeSuLCBwX7uFfkM6g36jtuwso59DPvteMMzjFcxpNpnaXN55S61VDf76FUE4yqltLDeUGtzTm5Ry3sL3Efvqly8YjsQIAS3hDiJGk5gyPn4LqjPXtiolD52DMOqXipHMYIBzea4juNloELqoXj7KYmxnNPmoIVbmVVAFgT1hHqvBQbTh9D,dKONrU8PZfVBV3e5nZPyBHQoEfMqEbfI9InDS61lb0mKnNiS9U1Z98nXSL6SAwlk1oiD3OiOs5T7h5llOYo642xkp6aSlPmEoJKYZXu6NE0NwGjiDns0HixOX4dEIlIQjRnPumMdZUwXtthdQ4F2oMFmWBU3Smrv0MXRovEVviQrf77YJND7VYeijz2AZu0YuqEgPNqOI2Mmn4wuGpTHmLjwB15MowLbWNZqFW9DuIfuYuXWPk82vRxCVuLxBU9D,QNMSnkxEOgf2lbRcPYhbc6w0O97DEeNvoMkSINpCJ3H54JSJgXuO1c0zGeOuGKZLAQf1YwkD60Qa8ud5mSBb8kgD6v4ra30C9OasObTewCSnJRhQNz17s3OPZBxpciifyfqQQfjQBpmrOfAEi2fvwSJlLfx3PvdQz0aX9BKAABuFin0T106GgNNyceCi4qhLKY7WsxhNOUUBWYrJHs46VoQ0QJbV7tKwk87g97MfDEFwaTE3Fbh1Q9BoKDvagPjf,73VPZQvHEsIm6xoOO1Q0UGyuYpMicCICpkFiGeWXvB1ZqXqkkdAzgsA5jSrwDqhwt0A8w70FYeIoKhIshPEDXjlFTGFmDRE785HKkKHLXU43PAaaddgVTWrdwLvFOHFRqjhJ6uf20ci4vSC9lXacfu6xSxd5uAEcwzO1csVU6FK5hWgvtnlWmyzvkiEjO0U8QIE2YieGA9pT1gGWwQ2j4huCUTdC7TMcelT7cBHI97usYhb5KIyTBoZ8rGcGfbuO,ejLuBzrcEcCKBmrj5Dl5vGkMeAWAOBTLE2ZWtUNLj8OOWRw6yiCUmGziaMXnQEFus6qdQILF72m8pDCJ6rohTCpNcUebbpK3FJuWsBnU5KnM1xemLjQqcou4W34cGM0A6WMy0747Ptlb3vvVvnFSTnWZkZ96qSWghDPfDQ6EmPBIU4q8U3Er01AydmX17HSRVSu2dGd1YRZ0YR56SJnzHZPmzSReaAEvhuZFe5jW2UiA8rXuucxDilHiErkdXQAo,EtWZfGUfUtAXxJ9qPu6lUBSrfHTI4NZIYsvHA4E4Emcd4KnJMAJAv4WSoHwRMOsLbeSqS7ZuW51g3ChSpillvI1PhRuDaQ8hAQRiIVxtHKq6HYXg3isBfxareaWv4iBL17jN6uMDWrrjW3c5bYfACkvEjATmvTXElw2vaRhhaseCDUi75xGdpAPkcFfUy2vtqekQ303l2pT2tddcOqiSdpFeFuL0WFWuNTLJOmbbt7ZynN2PY6sFmFyL0HuNdOpb,Sm2kiyU9Imcxgp8bTmoabpiPoCDQhTXOEFFvh5RDoDcyDDMcmXYlg3HfKnilr7WDs6J4NJxvzDBpf7eCwpNSMZCQFaGIK09rJg3581p9N9PPZ3eBINaVmEnLXDan25NM8ES0mmZFjRQ6b3f2O1lm8VGZyWHA1euK0B1CcUmL09V70tIO7MijzSu0A2OMZelgG3J3SGhovp4XUbgrk17Mgrd8tkJ0GmGs5WpOZT3QjjVcWcNlCKVcLoWXl4NR9Y7Y,4zgK2yM3jb9thVPBW1RVCNuJhZZZ3R12VOC8jUot5xrNbSJB5NJcXQMwu1VEUQwRlVKj8szUzEPNzEzWFBZyIXTEzvylcF1XN3q66OErshuMmc5CajAPVshZf9jJTpWEyHVbYtxUxaWHr3Pip7N3NNg9PGECPekzDCjXkNZpNQJ7MJ27ktcmZQ8EFQ2J71XkrnGMaWJuQgfWoFg8fT0tkDsNzjK2JYuBRzNAo3eLGpIC0BdgXLR9tkzRcSeeBbT1,0SdC2Q8RC9HG1kUgB4zbWNqbb43HtBGWsBoFtdimQVLIkWCry217zeZ2IVhwGuY44jLD0RXap0NVzVdfPnjmS4d491gYcASIqUjgVCRSVbCEDm6yws6uAwYsjkfuaCKdTxCXHqK3bQB5PTA1EUrU0WKhJRYwLSMHKMZQ2KBImJj7YgcSihyJn24ujcrvNydv6oY8ELHs7SGtVNruAT6FLubyt157XAyRN34Nuk3abueXXWscIU1aNxXuZMR645Tb,SRzrLTuALqPsDxO2rnEsJOgyBPiwz6Fwn0rx56NTOmQqoqdmkhNqJmIKCyqCxvhevkwLPWCe0mWmkDJclLHSbei2mbuFobNdpqDbvCFwREEkpsAynw83dtvPQYihIXnrDVdmlqpYW1Zv551XrcwDCQDwrjjKRhD5eXWEprFfH856xcg0j6ZPTRgrKswVsK7V9xM8T79kPvEzwwtWt48b794fPqMhmAu6U3IKt2Owb4kmyESfdWhbVSuE71XJhoW1,EqRGj6LvjPH8wKkTBMvS6GpblwnRm6fgqQUEiQQSBrWyYMbAhcGVq071KtKuZu2X2Ljx4cdRT2EkppD6AmoAMvec6EPRjL4ZgFh8Hw7EhyFpzCwxMIotABPGpdDmkN3qlcHSBBbueSt5wFaqkQ9vxmvZGJpkSl632NxnvL09Zc59ptr7NfApeodW8lPMCVpRYm8nF1RTnDoiRdxvBm7nlgZ3ZgWTpk3kZDiwdpUqHpnyCXHLqPgyPEN18RwsTxAr,CV4SI5aTjmfFJWdECm9grJadvn8yT1z7PiwHeazornuLhiL6AwaOtOLxL4RlnkKBorfW8L5kH5D98ru5x2BeqjAavy90lqBBCjOSz55xFEmTJjPWJwDcyDcDXvpxnS4SudTbqv6W8DZyKTLjUYdmdOspg0Omy41ce493aO1KuilQNLbccWUfSb50Rg7oNZmMy1IpeaTFxNiOwLRjWEWVPWEdO88dI0C8ta9TvBvmd83E3Vq7zJuhD7IqJ2mdUfK0,RkKS1mrwqbVmvJEpmQmogS885FN0nCEJLq9xOZspOzt8raSkS6ZTOi38i01dU0KcomNU03jRJmEaJf1rYI3LqmMUNeAGiuPIZDXUZzQMuJIiZAx6UCTNk0KDTTyyspsfCzDMLGNLzQpcs5pODJeKNqz6mpoZNhuqqLSe4BQqAZSRK0zQdoqowVPq55iZJjZbpgEdyqjQkr64c2jDEKhez9PXHHO1PUyi8bpndJ0mLv7xTSuXdPN0TubRdX9EduCj,7XALgLobVlZYRSM8QpTPHNXfFsxKv8cm6Cem3HT9sC0h5tNyKKtxdRvvurOIxFe95GYBxWZ7JprHQOvFkgSgGLMKWWg84vX7zQUiDjBWvfHWoLf8rmB4wTVi6IYnkQG5Fn5QXWKRQARkYQY8CF4rGODxiSiX44CaBKXvU8IYPBed2MkJPhTdiuiWXJTOEWozyA38cWF8tLtMpZc2ZqouF1Kv6ETIoYbVR74oN2VrauRYzroSQgte96m3r1gib2CD,kCCGNI7edi23wyLDdtHC7AXXHiuY2IdB8Nztgmiegplj9uryd9ZaNhNDbkWFLeWJC2XEirhf9kBKjYab498IwnOq1huJ4dWsVQUZFITA0I3u95nGmAjbBBZuboBYNY3kowqeCoFRzwF3FRL8xNA4HqI6hu5UyvcsGxTyyX6LOMRHBNlQvwiuOIB09Br8zjA2zyEKpTj4GuNCYOOwcoquGWZTFXaUt47TQKDgGepzLwVvqFnQ4mA7LoNB7EhuGduY,vzUPqThte3vDBRfK3pj16tP0UvI4zSvCOSZAPOL44QXWgvWpdIplh5xaOPGKhcokYo7mYMOFTCPy6iWTIbjpyImZMLHk10ZzTQk08ZAq3Gm94VQ9I8jfhLDrgmUc26od0L9ZgPNs3KiEEe0xYFS5K2tfbTtqZ3alN5j3uBz9McnF4IFBeEuOEfO7tA4mpJU7zdK2dlsjkxDoKTsjAt04f60FIE0Dtnr2z5OicTxIKPwHgSda0hbbVQ75OwnnulrJ,Q4lDFmGkQqgzr3yRG6aOkoC4ykzujRcoeYFEBtW6vKq1w3nWeLT3CXQmCHYEFTfjCgxG4B7w2MjGmRGSu9LUcXjAwvxBzYNBd7ly3tc3f9XNk1Nxe8nUH7nNfvJx2Wq5FSm84b8uqf7WXYyA0gUtDhHB0T3xkOdoQvTbb9RdWRFQdYvppscpwr5CkwtR7fco6ZZKbpoNtUdCk2FaqtFSS5hiR58tGyRKiO9C1moh5RxIfS2k1LzL2jHuhst0zZBk,GqLqmCEtNOsyHyWfCNSfmbbXlHCE4VDFW0f2Bzuy7sW8fKdp82RGlI8nuMHg7jwQ857GzleaJGOWHOXQL4VOQGbfKJbW9kXw0bp6epJFRmASXOH7r4hflsQB7GHJ1KEySFV2xm9cLvCMgalNjD4WOCiM9r2VKyL0XRXpfq3v8c9SP7dYBqKyAMYRmf1khsBnItXKxaDIIvHjv1ZPdV9qYzmLXow7szphKljKO7OCW35v9L5BFJ04uHYj7YQ5yWVJ,FsPzL8Fhrtzp60n5BFSML6eOrbITFVZx85rpbuKnc3VEdSK6ga80IlTVcnOH8kmzizLCn1V0tL5Sny4STaVrzDIOGtMr8uhUXVBQvOyhmi1hmLh4lAVqYq79ooabhGcn26H7J1pSUYS6e7rgd1YzOm7VRTgzt1YqOHjuzugcueEkq3iRnsbddeOWUa0pX7I63nSEZ2S57C2RKwniFLFpY43yfWkL35y1oA98yQpJ5To4RzTIsPmrS9ZiRTdgoQFc,u9womXoUUiBcWB0cddzHBdmfwllQPHvAFpxTzhh0ci06ATKbkLUKcG8z5MOzmdDI7ZC1Ui39vmirKzdASkrEO1FEe4iu1g0pZsFimpLCFRlu8ftwiAybeDYGnZQ8WCicU7qngIFmLZZh0xz5QiZhbhOUeqFxd7aGipW6G9WGE0zNdHDcDRC2jZZK3ebAciskt8EL1l2ixXuQP7WpHJdUfMPk9C1uSteFdLpDvMpdI8wR1yr6Jeuqri7OSpiKydbW,8i0KEb8e3byT6kvOqGIm3vSvo4Adjoy8ugj9Nix7lMFdeK6fzRb68XAaUjxH3Vfn5AHmWIgB2ERQ5S7rFnt5lJk9bmSlqXN4TsDnePWQYXM0LbN29MfW2oB5YzZeb6QfNjYo39FltgGM1VA3CRue8HgYjlssqKT4JjpJeu4epaDojFgim9vUP8UItwez2x4MKgaxNwxuE2OKBvaIoYQtXL8CW5V4zQuNGl3lAHs3YCF5KdKdidX4dYz0r2OvK3xT,6uD7T7Q650oRXS9ZItqvdwCWg3ZRuwP9F87CckI4lj5jgvZdaROQw8L0GCfgmE191lam4gJKirHZD2YuazSmGpn7XjaCNEucznHGs7z1MrNJNzaDilwwnnY3OUgKV8LeUP0yu02R6TG3zXcHaY4KF2ugypZF5euvtCB2cMwJtMIOYAyKsdZ8rDXecIj2HvGtFLQZ471IetI3IoJnQ39nYdJpzdhfO6DK1R0g8ZBSqVg4LRPFSjWzFqZ3sgLM9MXy,o7UpGia8jLvgW7KMhzVcy7ggcshr88hKQiHRGQ14qKXaduQO8NaaDRSNJ9nBqnMYmrOJ9yrk45Aa2WGTe5fPUcWwaDB3XRKjfH7VvdPkg2aFQEf4RMVCfSXFxDz05Zp3uD2cbo07mC4D9ADCiMLip3nGYPqb7yBs2r6MjqND7T9S9EibD05gBloZLfkrgOuYjg0Oprqjez9d4ybMEEvc1VArqogKhcEyNmTz8dKfIKW38gJotc67PpRlqBRM2ORc,MMXVfjtux7Z2xCe0q7ZoxZdtwW7Wiqj9bVUp5aLZwftY9CEfeumrj5FYTXvUog25F2gXIaO4Bn0LEfIN5KOPhCKDwGsQ617j4oYONalljsa3poqwLM4LfvoMqnGMRyYEILreHPGMUQ5zbV3yHdNnXpNYeDlJzjQsJhKHM8mKB0TC7WI5E2L7B0WRNHE0zZILhct6aW5gLY0qXo0E60eotU3KcWGLl5pdp2tLXb8Vwf0tcPeneIlBq8BaanxhKjlT,A654DdETynHvobmX8wEBaFHSHGpnfIDqZBnsn8NVgSRhOAZBVdOf6nj058eyLmjIKIzryGwVYscHtrk1paBJtPW8H1i5TDpD3EfYKx33q2V1BjRPBRxTapx4ptmqa93riVesc51iwjEnPcGCRhyD9GLG1bC4o4QPSFsWIFLunIKIEl9dKODPyLRbkRErK0vQUYneZC06PhKkRWEGtoO1r4boFTw6FV8fHm5lOkEdlBZKdCGNLaFV7yWJCyzGrbPs,fqi0kXrfi1vhDb33hW3Wh0f7u6FjHZvFMWaVwG05QZLUaVkld47Qt8NfeiHCyj3u7coMWSbvoG8Q22oNtduW4wW5p9vs2xrQXlvbDrD6lPTn5ITkgN1JEmmFaowYkjjmKb9W3fKn59BVDKsPCC4v8Lo3as1asP2O3BmzZ8e7uTGDaYvWKDePtbZtPgO660QjsvuCaxIHEjw4Ww0qlIhB6aW5AOtJ6Jj09hykBlOej3X1BVkv17aVPO5Qq1SeQhv2,KjIfUJcEjgio5zTasorBjhs26z1f0luMU2CVb2LnAyocMQnJrSmBLMObvWujaHucl7mDFZNxtdQ1O0HCBfLsvywDPGE6BASbwlktPFhoC54j7NvUpcEOSxtCjZAtSwNTtiBz76xIAY9Qh8zfaI7JXkpklplCdtbqRr9SQd3d6JMYUnLBNwwUvtOpf8sOqVaCBHleNkW9SkDAMFuZVAy13AsFMh5Mrola0FbBIeYNGpSJJCGXjdJHtbSRCCbMxEn1,FBqH4pOZsiEcjygvc02ufHkSXFOFVcRKivlBP2xl28Bqvrk1rdHjPlLlw1dtTyfEbq0Pi8UtxdOCX0RaCb75QFlB77nPOZ7KA9W2Uovvaa1P3nOYEA2G1qfNQQhMf3rLlyypU3MLokRMNnbfc5SWRNJlpkAqnCV5LT3wD4aIMWZi0svtfbaQQx3HCZ6xWDwOCcQutGFVS3FzKhKKZUdXvAwzOjkB5UwfWtXPnvQQf3Hj489hy8cel2AVrsMl2Kfs,BreQvSZpG6ISVFnZfATYD05Esh9LFXZAdw0NEAYi0KUYpTPtvKgziOSKgKBkm4bn7tthVgAM5V2gVqpAH0jl883xB3enwyZGH6LZTIsPRaMG1XVPIYOWNBXQDEkiYURbBAu6fPKf6xGuLaFMRFsvJxFlMJI2zFrXKAXnvqwVjxj1h1Pj4tKKnEfuZPrIDyok1Jf8Zk1lTaVyYaivu5aqsMNj17L65aF263SHA3hHvIPXmawuumWLWftcOUc8Mi5P,QSESHH5lEGot01oQk7eJMpPr4En0tfHPpHCwiseQE4C0Y4oEYGe1kK5LKK73S1oZswyqF4jRmkpGsByxfjUzbRygqojRbBugcBkFSFPqH72av6NemaykeluQP7xHGLQtdtmkQQnrfaU9Ur7FIiSC21689P5lptlny9bF7dV4aJeUbMjzSZ6lusKb5uVhdz51fEIrcyggA8wg983gVm8QMurOwE3Qep3Ae5QCQy4CmIY9MqQcuWCSDcYblWdnpte3,Iii5p1eHuDWBvpptkcbHu8KSaVs7QavW6oL5gG8ZfgZQZvAKrlv5j9RgDMvA1udmZqNG2LBWGLeSdhnYefmfOAB1GGx9I7cwuKbmHfPl8mNhz79mqiXw7gSRTsEEihGDUKmjBkTdb4DvOnJlHZKOLgC3H4uwQYTUbH70hOnzKqN0gu4FtyElGBkJurHcJblY3ULyLHujWbUREdCih40QZBJ4xj4Hh7S4LNFoTNGCMh9dbIh2fITM8ATfJhevKUV6,CXJfYecJwlq4ja4nVPUOE3b0MqsW3xo0pjoE5HFFZeikJ124FWNxwFjiWWiP3sLnfPWUOD3VdFvm3mq4bKNg17mCs7M8lxPcqYzKux7tCg9WY09rOqrv1dEejuam7YzBp6pbR4vgMFEAtXIAN1T6Kfg2le6cCIgu9TH0qEgToRlNapiOCeaDqPAetEjjjA08lER3tZjL7dJOQZggwtQA9wZpZZDqAE1KVM6fWiqxKk7uVT6sjtlJamv1qU8sDjXV,QT3aWHvDgdxN1VdE35X19CK4vgiKxUX8y8o4qkHpmUzLgJfppw5zOEyG3U4DKC2MDPwlHbIFcosCq8ThQDqqYkS0JG8qc187mi6DBpYlqJVQhCOYF1vTOrMFA3TNDFegFstegDPo71UuZ4L4u0Rvk06BpV94EWLyCICJSTKVXvPkqzrn8XMACeJtH7QBzNuOvX3OZH8uof1Ft5PeXzCS2DjEwkD7daSS8rcInPT1Sf8h3oPo4QdSMsWv39l58quC,UyNxHsuSggzcLElYbYhfUyCOqQ2PY9Zbce3MNxyI89Cgybr1jQgTYwyoBTajBu4Sh4JeuKId0nptFXd8NMmdZ8lqeWdegALy9EHrbdoedseQXE0XQoamvCgfLj3A5MbXYMFTJo65jByGWYtqLykCayAmxGxRNE6XIo1Aw0kI75Mmw5itYt4czWFnY7Ys18ot0wzjS8QKDJuJL2OSY87W0dEgxLCaXsmknKjgnjYdpAlFZJ3ViC6QJSjlf1NnVn7m,FWgfebNNbZIRgtjtRvplUzeZxPaXnIzPlsclQbmjp6tIHFykJbewQ828e2APp7XfjGINbgZbQzGQLG9v8cEWvtQn8AOSzmoKratyHVAxlw2KCMteVkg9Nq7Uxk99g3yP7RtrEVaWVlWk6UJV2r1aDb44cFpH1Wbwj1uQBAv4Odc76G4QU8rLWOiQlbEyhqgUyl73tJlTHEgzJ1ZmYSzr1PkJLPugCfosH6S0MZYJ9c6qfe2znyZkz1ax2kIbNpJP,mZEUQHQpbgO4TIfJ4SXULELPCMYjYlvXeNHFkSDyNNzSjr8AErDuAlm8IrM1TgPjmu0OFKbEMPwLOes03G9jDsVx0SBymd2SVF7nBx8AUNf9y6B5i1iPdZV7CUiNJKr9YjyRoptT1S3OI7dC6nwJWAaWv4e7qFbmbBybLyMWEDWab6zYjEPBreenOKRpoafChEuI3wDmUW8W6dYRL5amJqEOVEU6FBCh90JIHHb8dh9IphLKAYoNZTuaUyQu2Bnd,fqS86W4k1m5rxhHII5srVB8qHk2A8svpZWd0NJvoqjgDoEK2oH3WRVWp66hTF3dAD8iphwuVELdQTjFlhK3mNIaunGkeYJuRwydX91KVFMjKrnz9hMgD19Xd8vTk7KiErUcf5nC1ywEll8hLs4ulGn382MMRDU1ZGFjrKWV7XrsP29sKHr0u7YdNBRxtpC1fN8UsnoLuaZtS8ZyztCRJtIe4iiwQ9iQO7VCrHtryvAvSCkwpMHrfdL6UNfX3xZFr,kQYLR3V47AdwrehY9kTxTIIsShukWesGvVurflWmCeigIFQ3lBgCVacF4BzWI6RTXLCyQ34CiU2ZuzGKvQulgApvE9WGF6r5DdbAcOR8gU2L1g0yAahnqMRMhsqLTLoRGDgdm3CE3Kqy22y31nlDBnyPhn1T2rHhXHxMvRSH8jxERpFO5asgMhGuUYws6nsWo6shJiHk19ftMAG9W4xLIjRcUInRWVwBvr3C8q1YWFeR6py6XYvucb9TDkczLbfJ,CmaU0Yu3BgLKVEFJK8E6CqwjajTecVq3sPuuypxSMoz6fn5I8Q3dHxIkAd8IYDcyBpJqWSDamdXC1zL9ivrIbdmQrO9D8vCqYMFhuOkUX8gEsktgHCqZhifEvBoCMDW1A5I71lBTb6HE7GROwlVdN4mvZEqCzGL1jx57N5ZBTaYeU6MK0KVYi37HiY5hudNSonQP53Rb7OT6oagV7t7lxi6CYJeufZqGAPmwTAzWDjR9iJbaQ2pMXRRrjd7WoaBz,vNcSmcnWQ5rlKCtkK9MsNrVQNCCjElCxSIQ8PROCXr8jstNSc4uRbbxh5OWXiMmRZbjA4OB3P9UTF0lOj6upvnrXZWzef9ON667qGxYS74BBqTOAYfPZivfzUGSv7FYQmOChmd6g9y5BYwgsmAJ8vUXFU59bRjOruIgeB9XuZdFMic1cVai4oHke5yHviTxvsN9QfWlUUQAwRXHi4MKUuKy2gZ9epfL2jmDC8WHPiS5v0xWpgk0UWCovRSbyGtcw,7bhESo0A1qkAEISYKgzajx3pbM3BhlMr4oI7v4XZDpy2erIUT9dpm4lwMXf9xTtYRaYiW1pyHWP9Sf25RW7tv8QfwUNHxoOc4PyGj3VerhLXKIQl0B9oGmsSTl4fmVuTfR9Uk8xklnoA3DWeURhNGvHTYcZk5GoqFIMiS5hbsmhhwRbJK12mXcFIU35DgOJj2hWHsmFb8kzJTl59msJNL9ARL4534WzgV5zPWjDZ8Fno1dZMkbBoqriPCu2jWnNR,DH5yeUyjEsKZ89XNPcTenr7E5wryjx62JtxKWvfYJSX2NNeSDrRGh3m5yLD2WbMm1cNCR5GA2ZhuSDsMBxNdxdXcrpN14U55OnAxw4XOEej57i8vgJlNUqCsFrRPtzAMtzg1LpRNSaZinfBCoDxGxyZnEyQ31BS0KMDH6vWmqlK5D3jcfrsW0TUWEZmeXnOKjt725gqY478uK5oWvs8XZr4pjwNffagOrNfvqK0zR27LPkSNsvtEEoqEpl6p32eR,TsnILo9z8YmJa8IIDaciXkdRHzfDwxs5ImPtz188ZWGjpaTjFt56LGCrRROuFQonuyGC2q9yohYph1ncvgVdnC1eNLfYlPk0Du6Oqr5Hm77REsmZvChEnl0UU1bkYsukaes4kcWZ17z8ELd4XUan21qurZEIwrx4nryOex0jbOJJGzjMfS64Qg5vHFPhmcCEiYBmNRe07o7uzSkoSGEHpkDePP2EsdVFiqHA7QSI7w7g0SiexUw5T1IY8iohiNkr,jWO00XuhKiJV9AlACQoEUTM2q8sb9Kqm0MvnM624fB17p6c9JRvTNLQgXpJK7YaiGmsmFZxMKcQQdpBPWR0K5JPXLwrKpXb2SthSpivVqOUh8u5rTnt1AxI2lg1c66TDhCJ56mSaZDzmDOKsdi3sRaEaledL51zfEUGKHqzziSxK8kF1H84S4Qi6J4wMNpGGRVCDM1ni3iuxPwa7dxGGqKysF5B6npR5FmpLRBPOy2ox33rejA5UwlaDTk4UCPRs,u7IjRN7ep4ujGPJlWht6q4QShtmq5c3nemLoCVjEmGCCFlG30wAyJzipMiCJzpjRUPz7BMglBdzQRO3fudFrIQHfuSSCJ9DCUCxC4srfjQPg0tqTgV0JdJogICAgo0PgkPTqDhJHSuOzD8JGO7fKxdaGMY3KDFL0qZaPncNyhUxXRff4AGTLR8LtkzJaO4BBrQntXOuzfjgUirScuOoLkhNapGWVlVjaJbP41ij5zJT3hekMHfIeodnB6qBSr8gx,gSIc2bymyBq7u0Yyx4PrwC54ktBGa4FUHI6S9JsWCn2sd4b5UF7WASB9GzjTZq5zQhlOjHXxvIQXR1yFGQObgVDuOlnJKW2htAmgOt7VNxmQoQFKNQomQTCvO6TMaF7nbhXWzTnTFDBQyDZciwA76wh4FY0flxZcRbH4acPNtyipQTBWkCYeAWEnjvFg6mzSXTH7IfQCpLIqrvbsY2bFzV9927FtvbkGO5UZUhiL93MqxGg2SDgkb4kc1UNfSmeM,YJz5psxfQQ8wenTO903tEgKsAslGR8yMCoZGpaCrg9AuCTfTJ1782SQeMSRkSfzO9pZW0G8lnzuuGgx7dfiR8nJUsH7Sda45cHm5qk5ianlH4Upli1tcoaub50AtXYr2ZVKVMc7EQFw1pYnIXVS5EFLwnVSy8HkmeeavCMzCm3MfIwkbCgTzscxBNwNoFnUiVy0FZsr8V8oa9fI89X4oszh4wwYv2YLb5mAnUw2SvIgfoEt3OWS0zV5DRqDUjGT7,YUQrF2vEwoXChWiiB8y5GaZIpPVPcYAVlcGaM69h9qz7wtGoPgpMSm9Gucm7g8awcqepkWM8cQySk55d5dt3p5HJpCkVTxWmiemAiAVL66MimvBMeCkQr3Odv0sMNt20PgJemJNdqsvltiBsVgbZDeOKjaBRsw9mNZIvv3QN0DVVjqhWXx3fA4TRnvsXs3UvjzoXdjEc6l78RXtXHVtUyywYqfz1WckB18e8AUQ3b1ux1ptZREMjb8pQMOG79THu,D2HKVLf6dLEruQP1VvOw6QYTgHQxql6lcTD4Eh16472fKzj9FwSrSU1Lgoj3N5nZhVYMUUysh0IImruuQd4HzRgmh64n7mxbdQImgVudd2MZfRZt5lNSG8K5yibPeirS58ydlXFhcfBomgZljXtUbhqtR4X1CSYuyCmEj5xjZ48VuIULZ7g6aMB3EtJTNVavaAi4Yh2VtP2EfrcrodKxLWqYL5krR7zdVbspEDe0Mkq2wicrpjwfmOkVOQb5UcDT,uZrdRLYFLzayXYI5ar23wSZk7j4aAhqabIlrWerdyoyW8WASUYOVB5hTHKMD2lt7bEi1j8x3wGLzH2wiUPoVsOHBEkI6UqOuNjGPbKNpEPvpxoXpZYUV2fH7Dw8GiUnUURoNqW3ZdpQSeb58kH5f29TCJthg8G3DCSZlxCHOaaAHefKo6zz4mkrBCaaw28iWukFKymvCGyJYHo14h6tm69wMqhu36zJlUmZLXJBxSKe77Yzvh6nMG5PKzYfeAHzT,yqrG46z00dSOJoI1BsHVQgvjMzf9kWZzoeOPHA2dlB7LFUOgAD0AUX5PsmYSCte4D83Yi6sidobmA15tJUxMApjAwDzwYEt9TF3gmLinr8eFJxQaGcwPQTfk0Ea3UOkLF5mnh4rL2G0uAZBH2prHJiupjrDh9cqPSA5EOgIe0Xa5bfrAXkBscZsWIBTlY8T1GdOtn1QmTGj46VLCwfWqu0R580kKClgflbzfdzj7Em2htmmUTU2zRdWR7gzn2kCv,HAfuVrurRMi3qovbpGHUyNxSVFTFBC8v57zWABnmhTVhwKd9NjeH3ecsWh5M9m1yHNqwqeJVHEzhztxduzh4TNjyzGpR8mo9ZnzsSHCNktGGicPteKpScIYGoVVeFFFDppNjpFIRq5bARgFeAcduHFp57N5Ew2E48AANpO1lK74ORygvumNJqYqQT2HNW7BKTlRNIUuBFrQ3z62QWRXNI3v40PXS1LMHjuWuVRemwEt7jUJl5eRnyKm5EenLpVMm,nurVIxCKtKjztCm0gGHL0rp7DQ1fom6w6J1Svlc3o78uJXT2qT0644kqT8cqzjcDjFBIqhxTDjZ9567oeMtd25jWP4syzC28VpXt4Ozo87JvRfqCuBzsKhwWvUEe9KwiSqqgQzLkGG9U0U8zETli8tadHdhmji7k0YgRSDNcwccmHIDCF701QY1n7PVUn2c9bPedHETubAuRgGn7lqVZLOtCdGcsO5uBp6hlkKXBPBHXppGEyk1JSxCQK16vE0Fd,NqNZfrVGbKYdg9amDxIOX89l5azq62mHux9ACyEGu6A810TWs2xdnWVp2IG2A2gy0tSlexztVzkS6DSZ3zz4JSsPdIdVfPnqv6g2geEH6WxHF0Y6DTJtlG7NhRT2vEQ27J1AFpVCg0wh68eWYuLXMXnDWQD0y7ELA3FWJy16UYI4FFKSkUi0zXW7gTDEuAOrHvwYmEBIAqr2ssVOxBhdfZTVwgRzdpZVYqzB2G13CbRefG4ycyGHs0JWsqzcGgJa,YnGKvtvykmXjkqkZTWszM48DBtUjT3ZvYLz18K5HqqbAfsfVlBcvAcT9dBNNXMjzWDbcRsb5qG9D1LXDpLVx1DvYULg3FAaBuDK9rRXitgUGf2bs8CwJdfTGMNpRvGir59iQpfTYxGrVUpnwglKpsCIuwV1pMFqaECwaGJEgj3nIjYcymTvzkb8oKaXHWCBTYrmoWipxF5wx3R5MuQNAMnrh82SJeFGxcE2VB06xrcsNF3mu039xXu5HxjGbfUhh,TTODWwSwLZ0IaOh3m9Wxcyq3LiMUfHHhPtbcmdoKVhzha5oFVCCHCDfNgzkteTvSQyWF9sIO0cW0Ju0fUF6MxPuTsclkKS2J7b1p6wRDcRMiP2iSzlpW4nBIZg1aUBkT69AnnltkBYErPY8kRB3y8vMUJ8Zn6VmbUqICZWc6YTc1Dcb7JkJyQCWXQqTjkJho4jbCQYoSfhmxyKKMDQ7bM0c24wnGbuh8J9ir5ZJ8DMd2qX2lCbWTvzUCUnk3Ihe9,Bd8u9Gu53ngtjAjtZLl3HSlOznJDN4iuKI3RAiLrFTnrYO9wvLZqmzTrZUcX3FSSdKIRhiq2do73C3KjfTtrEh8B1m2lqX56mqVt6Nwdq9vobkLcV6Y8ycADV9AmZwUvvNPRU6kvnaVaCI8Dn2zUDNp5Gq35GcYrknNpCL7X9GI6e1SLoeCZFeG22mQpxLwcL8IWlLEGPlan7W2V79arXFIGE50ma1gaHlbBycfIKavaGddTK8n1AlZKzIrYUBJa,X3PlDwu7rfA8uzsgR1MDbRcHCevcPs4CXhSXAkaupEgKzUi9cjSMKS84uQEtvkw0fIUAQR2MUOKtAHI8C3uijNCO5eVDqa4xraJPcEXiIyuaL2TA6QZjreXuzmtfrJ3kKR6NNbGrtY4xVdbUkdNUKyKqDgcGyPpVDh5R5Xyt2hoZNq20WZag0LkubFe9FGnWYp61eT4CRR0MJT7CbFCuiUuu98fLCjP8FIl45c7aHmQ84q225Yx4ffAeZS5ZYPtX,zImrNOy99kKlU5rrJL3YeVNaHPfgiQwXJxfyllzFPo834TgPSXFXYFxUysvxRPhuwoaX7YjvUWBNWpY44njTZ2mlmjyWhRIYmkdQycrU3S61mmBxznAT3MDR1H8XJm3zHF1Yl5ur0dKX1RxFq8NPdlrhCQrjaQzqGBzbjtGi2AumG4irrII8fWfgZrD8gia4lilI27WlAUCibqjpmKMZ0TEivfIuPPNdryJcKODBjGvCQFqIfkibG2vzxH9lfwz1,lafPwjGENqKCHBThsx2N6ahB8M6V6a0bqHIPIGtZfZHOdgPufDmfn4UGDN4BShNAOPFIMmEpFwWK7vm28W4qTRS9fIABYamkoTw8Ve88nTwltQ2PdlN0zAXt5XUJuhz8FEdq2CHzf8GTSfLA5pdQhHqypGdOsAxSPvXZKc9l5Ju6QcR404MMLH4cfy45qGCEgpj7zVuuyyxZvhYvpvE7430qDpurwGC7vs1TCFwQFR2oZ2ahjKT4j6BvQfHPw5E4,So0UpEE5ROk03ebT28jsJYEiyGu5i0f7bwCQvJw7ISPhtgVeRlPgbj8DF4Q570TGG4hbggg8PcUpGy5VvgbfVtvqyS5p8L38oMWnAgXb8qxcmWXTnDoe2drF2JQhvzKzt1FvdXp3GFVvhoblE5eyuenqhG2EngLr15A9NtBaA7sOZsPhGq7zdoqvMKuncu2e3LSFPdzonf8v1NEr6xI3woApCneZYuLPLxkY5BeJU1KamQjDBC92qarcXB3AvWcf,v8PwUoxzizHAlpPZnP5DMSIjGBQnErL83TjYgEApiH41lT7wsMc5w3swDls6PxSk1IEqLwiQYvhJVpOTKFwmZ39lQ3bPiC4nMQxOiNeXLLd6fxTgAVTTU2FrouIgi3YB997J0W7Muc1vNQtRAQZwzhr2SqznnRspXnZwQXcTJHih8KPpR8fH0aZWIKZHOx8vLJ0hLIZysRloHjRXDyimxy7aveBnke4OPZp8uHraRvP537CB8cfb0cl4EXAnR3Pf,XtSrkLLgTHKvc26B9TrfG373EANIFpex0EiWYl7T50qkDO9GIhbcTuWdxBB3Oqnv7bwI3CrwDEzrFeSbxI3IqsRB21whqYUcA1qfDfjwdOcYg8Y2r6Arxn8Y6eDqqklru6i1NLgdFrmAgL3FinuAFhmz3cih589WTa3farN6YRgEHdEwt9B1Lg6p69TEtDlTY0NLSzoXiOlec4G357PHr3VifmCjWc3KqvPZX8FIF5ZliWdA6ZTn5oUeOGD1OrmC,sctjhPSMsy3vYmy1nW39k7z3kmNYaoPv742U3qDlk7bMkuKpa3EDwc6hsCk5lDvcMwDZ62jIqWBrJpVuny06BK07MyH0Ald8fuWx4lqcTATR12c96FGYfUYL9dr5e3IyP6YGVre39Kj1Srqg5IRuPzC3QSC7vUea6p502LxtEEJOQjUISZgEp8dNMPBo1Ziop1j73zKwKaiiia78uJDzJKxubE1iAyIQOqBFizegRH7OkpIAVH2iwiaDOPw7Wx0C,4B0rAPLHC4iKgoKVK9VF28B0GhGyyBD9XJNj6SF1t667OgBA6O2Yhcq1C96dO9yEgeJpcipH9L15KSMfbNjA1H9MW735u44urVbfiKzFcsVvDfj7oIT2HK1IhraLUxcffkgAyCwAdonuzFROG5ny7OgdYyQyG4ZOSHwMdAuaIVkt6B0NZiKES3ezfTSKQUezwTqhpFavSFhxMxW1rx4MVJBEZei5EYPks55PnewavWRpVS2JTWVIC8HVQUZdHdWS,ALtc6rALnEunh95nZ2FfzcSe9ixkJL9bd6qJsjNwR9lrgTBN7cJI2Wdby7LtFTsJ83D7X7YSrrSiH9XIfLOaYrSz6TxXwI8qGrJbFKZouY7PF7DvYDovUqWi94918pzIGsfxALtjPGMIKOR2V5aGFpEnlvlD5YXC96NqAfPRBxXrnr1T4KTHrxHA1iaoCdvQyveS0hnwPB72C6zqYPiDBDG7WCsSTKrPqrX8pqavuKz4HjgQ8VLnFG0MMqQW1OBM,pYEuuehNs5AhuIdXQNaF0kqOJwfT140JkkAYRQ8xBUnSZa7YpUqIpasS4ZjPTQuLdsiRVKxDqW6FmUC9IBvcIrZmz2esm1iQV3WGO6zK50okhtGXf0vBswR2ePtrnebicITVwUO5tJOlUFISK0DBHgnIDpjAZ5GI8WeRkG0OBK8eenPjivY1XocQRH75mKwYQ1jUD8yBauiu2J1x0VMTMN7HjKgRseUqGo2vyHkPuIVl1hQX6o02pXpA5CLBlXZx,7xoiwNYtlZW4wRHlYe5Ney8C4wbEC0BgsIVTgVp3uhCd02uVRRVlT1LCepSlbuExqQGKi5D2eQls46z8vJv3WSKHU6W4uNj6QDg4M5zemsAaAQRobS4QRlddwnTP4uLmwv6N4uFBXxNxWJhycJ2HVxDphFFQUgU1v5RTSNKCQzUxPIWMt0yrrdOA0d984kUdjsaCIc7Kw1F0zPlHYgZaR5PJGNLcOnhd0yC1fd44CnVyGj8AVdPYMY6cESsrjGDF,tU64ChYPYx7i4xI9mGSKOh0Ty3zOtmVy7vLh023Li4D1tu24spHYEBIck7au5t5rsYCrX6qB1SCgORB0rJfTfWp1jwXjRZkPaKpBFdsz6VGfR3YJEsM8xE8YdWNV8OgFEuJpED9lJPpIbbuEq0tOLOWK84zKrSE75Vvu9ddZ7oXTj4pArrG8CZdr7ZZCNlnD5BnmgVmcacpxdCLMB0bJabfwW5QeBkivPNwzxGEHuw3FNSZiZetkjldxW31Pv1D6,xNSJ8mKitAu3jRtJUf0JF2NKuJk0pA7T8K26BhXq0aGPpeKSF8h5T7K4s36YFSdgOamgrh1i6qHvLnhpj36HAUgTsEJoN8A1GHPpeMGlKtP1dLXgsoiSATQvawV9aQP7dBoyvPzKOV1FMMacrRiXK2smwhd6vXuR9pqy5qcIJMddMV7IfQzV88C1nPQO47Lx8ECLzceiLGaxrSEMND55qPTRboXYRnVS8QtY1sGZqBT5qk4UFSTs7heAVmSVoGde,lAKAxEoDsCgab52U9wFLlOEBL1z6Ef547KuKgLiYZqZqTMTlDkt61j4TBb2ltl9sL9CfDqzaZpT7eHHSJQ4qJC9eG7NCT6zIICXy3gVkrUFRfRLtO3mtcBYLuGE0SnTntaw4eHU3LmAFoiKnpZrOPCdRLKfRsMQjbBgJrbnvfZhqIHj8PuWTWzPamPbPZrP7hs4qMyO45BBQ8dul1lS3StHUFboQfPO7mWlyzv8XH8ZaplCt0r7vp9I5QvaZQuiS,EQNvV0CkYFkLom1jGs4WMXosbGTFdWtFg7vrcwfWEPFtRPBamPePod5nl1h30zxFV5vVmjH0gqIgqmSgc3U4tRF51sXqBPP5CtffngEqVF8Pgk3E60wn2HpsytsVBQW3hM0C1Bm2FGhwsAaOv0kCKQelYt5MDjFaiJ8xkgSCfMiYxZuj2er3PB3Ww9SuUm38DZcLbdWFFUPRdwSde3wf4E5U80MueXJUgPmPKNfIgYkWuJABKYpqobXu4f0I6dkG,eXdBswZLjEHrzYgNDVFCWipvqkF5AWhg0djRgpsqWjWRC6ST805wG1FTxNkMSwpZhkpD43XwzjlUHDGcdoz2sc97lKeFRJN6PEzsBNeMGOppiT6WFc91FY4UQtmSPc0RbVXbIvYiminakhl2OLvD10jBEKERHIK6NdnSKVkj8fXg3umNalouQfJunXTk0FynMRmZZwG2Hwm0i3HjAdlGiL5mNA9xjvggtyE15r0Sqzoz9gW5b1vSaLCTNgMv4R1g,1OWZ4GorMcWvXaCTCFKBnmJYdTw5DFgH9QWdVbXvuebjWPe3Kgrcm3ditTyvKvQbZO8b3AxTgzxp2O'
2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [9]
ok 124 got the same data back
,# teardown
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:0193AF29-BB70-49A6-9678-9B2D28BC8830
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49954
,[ThaliCore] Session.disconnect() peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:A70FC736-E8C3-43CA-A8DA-5648E57634E3
,# setup
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FEC59BCD-AEDC-43F0-8AAE-7E53444C9723
[ThaliCore] Browser.startListening
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 127 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "14FF933A-6407-49A5-B304-4E3B0E38C0F3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:14FF933A-6407-49A5-B304-4E3B0E38C0F3
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0B6584A-55E2-4F22-9640-4ABB1B359C49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
2017-07-13 09:31:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}]'
2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}'
2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
2017-07-13 09:31:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}]'
2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
2017-07-13 09:31:04 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","generation":0}]'
2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"258A0987-3B4C-46D2-8465-A55E41EB0EBC","generation":0}'
2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14FF933A-6407-49A5-B304-4E3B0E38C0F3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14FF933A-6407-49A5-B304-4E3B0E38C0F3", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 129 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-13 09:31:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A0FB99D8-EB22-41D2-8049-E0B4CBC811C7
[ThaliCore] Browser.startListening
ok 133 discoveryActive should be false
ok 134 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FB012635-D2F4-49E4-9D40-915A2F71F5FC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FB012635-D2F4-49E4-9D40-915A2F71F5FC
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 137 discoveryActive should be false
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
,2017-07-13 09:31:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-13 09:31:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 09:31:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:2cbcb075-e7a8-48e9-8b2a-eb4e9588bd07 error: startListeningNotActive
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4XAtDnN8tHbuTWMepK6z62Z8C4NtdqNS","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2cbcb075-e7a8-48e9-8b2a-eb4e9588bd07","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2cbcb075-e7a8-48e9-8b2a-eb4e9588bd07","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89E5C470-0760-4252-B08F-09BBBC448A44
[ThaliCore] Browser.startListening
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"16getYvy4UY6mPIGnTYEbZtA6VYY2yHd","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
ok 166 SyncValue matches
ok 167 Got right error
ok 168 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0B6584A-55E2-4F22-9640-4ABB1B359C49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
,# teardown
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}]'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C0B6584A-55E2-4F22-9640-4ABB1B359C49","generation":0}'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
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
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:329EDE35-14CE-4662-B994-7F69DF66E078
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 No error on starting
,ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:8641a2c0-f7c7-420d-bbb0-c2d66b46b51f
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 181 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-13 09:31:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 183 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-13 09:31:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-13 09:31:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-13 09:31:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:31:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49960'
,ok 185 Should throw
,# teardown
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49962'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 initial connection state should be CONNECTED
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 187 final connection state should be DISCONNECTED
,# teardown
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49965'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 188 tried to connect to right port
,ok 189 failed due to refused connection
,ok 190 routerPortConnectionFailed is emitted
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
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49969'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 191 Send/recvd #1 should be equal length
,ok 192 Send/recvd #1 should be same
,ok 193 Send/recvd #2 should be equal length
,ok 194 Send/recvd #2 should be same
,ok 195 Should be exactly 2 client sockets
,# teardown
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49974'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 196 socket shouldn't close until after stream
,ok 197 incoming remains open
,# teardown
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49978'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should not have gotten an error
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 socket shouldn't close until after incoming
,ok 200 incoming is cleaned up
,# teardown
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49982'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 201 stream was closed
,ok 202 incoming should survive
,ok 203 mux should have no streams
,# teardown
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49986'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 204 we should not have gotten an error
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 205 Buffers are identical
,2017-07-13 09:31:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 206 native server is nulled out
,ok 207 native server should be closed
,ok 208 incoming has been removed
,ok 209 Incoming should be done
,ok 210 The mux object should be closed
,ok 211 The mux stream should be closed
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49990'
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
,2017-07-13 09:31:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 212 native server is nulled out
ok 213 native server should be closed
,ok 214 incoming has been removed
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-13 09:31:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
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
,2017-07-13 09:31:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 50042'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 215 we should not have gotten an error
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 216 Buffers are identical
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 217 server should be fine
,ok 218 server should be open
,ok 219 incoming has been removed
,ok 220 The mux object should be closed
,ok 221 The mux stream should be closed
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 50046'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 222 we should not have gotten an error
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 223 Buffers are identical
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 224 server should be fine
,ok 225 server should be open
,ok 226 incoming has been removed
,ok 227 The mux object should be closed
,ok 228 The mux stream should be closed
,# teardown
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-13 09:31:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:24 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 229 serversManager must not be null
ok 230 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 231 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-13 09:31:24 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:24 - DEBUG createNativeListener: 'listening 50049'
ok 232 port must be in range
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:25 - DEBUG createNativeListener: 'listening 50050'
ok 233 second start should return same port
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'listening 50052'
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 234 we should be connected
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 235 now we are disconnected
,2017-07-13 09:31:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-13 09:31:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 236 Passed bogus id
,2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 237 Passed good id but bogus port
,2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 238 Passed right context
,ok 239 Right server
,ok 240 No error should be set
,ok 241 Retry should be false
,ok 242 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50054
,ok 243 should be equal
,# teardown
,2017-07-13 09:31:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9705760D-02FE-451B-910D-A16CB2A3B940
2017-07-13 0,9:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 244 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Browser.startList,ening
,2017-07-13 09:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":0}'
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5BAF6D3-EDB2-4528-B144-7C271A324831 (syncValue: zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz)'
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Advertiser: session connected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Advertiser: session connected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}'
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02 (syncValue: nb9xVNH975QBchGX6HApK9CE3LSQnBw5)'
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","generation":0}'
,2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF (syncValue: v29MmJiUULxruALUdyMQb3nZWywjAEhk)'
,2017-07-13 09:31:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
,[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50063
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nb9xVNH975QBchGX6HApK9CE3LSQnBw5","error":null,"portNumber":50063}'
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nb9xVNH975QBchGX6HApK9CE3LSQnBw5', error: 'null', listeningPort: '50063''
,2017-07-13 09:31:32 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'nb9xVNH975QBchGX6HApK9CE3LSQnBw5', originalSyncValue: 'zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz''
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nb9xVNH975QBchGX6HApK9CE3LSQnBw5', error: 'null', listeningPort: '50063''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nb9xVNH975QBchGX6HApK9CE3LSQnBw5', error: 'null', listeningPort: '50063''
,2017-07-13 09:31:32 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'nb9xVNH975QBchGX6HApK9CE3LSQnBw5', originalSyncValue: 'v29MmJiUULxruALUdyMQb3nZWywjAEhk''
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50065
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz","error":null,"portNumber":50065}'
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz', error: 'null', listeningPort: '50065''
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz', error: 'null', listeningPort: '50065''
,2017-07-13 09:31:32 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'zrb03AmSQPSjTeUdYZcj9XpRaeNzcBdz', originalSyncValue: 'v29MmJiUULxruALUdyMQb3nZWywjAEhk''
,ok 246 should be equal
,ok 247 (unnamed assert)
,ok 248 should be equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", genera,tion: 0)
2017-07-13 09:31:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"v29MmJiUULxruALUdyMQb3nZWywjAEhk","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:31:36 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'v29MmJiUULxruALUdyMQb3nZWywjAEhk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:31:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:31:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:31:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:31:36 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:31:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF (syncValue: pT1dJz3eJrp6EIcXSlS7e80ERVZwyrTU)'
,2017-07-13 09:31:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Session.disconnect() peer:2C25A8FB-5F4,0-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connecting -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Advertis,erRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Sessi,on.deinit peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", genera,tion: 0)
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pT1dJz3eJrp6EIcXSlS7e80ERVZwyrTU","error":"Connection could not be established","portNumber":null}'
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pT1dJz3eJrp6EIcXSlS7e80ERVZwyrTU', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF (syncValue: tKk2OE2TpGpMSoKJEqOcD3c3ogoTnmAy)'
,2017-07-13 09:31:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
2017-07-13 09:31:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tKk2OE2TpGpMSoKJEqOcD3c3ogoTnmAy","error":"Peer is unavailable","portNumber",:null}'
2017-07-13 09:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tKk2OE2TpGpMSoKJEqOcD3c3ogoTnmAy', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-13 09:31:42 - DEBUG thaliMobileNativeWrapper: 'Received p,eer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:31:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent ,due to not being in started state'
2017-07-13 09:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":true,"portNumber":null,"recreated":true}'
20,1,7-07-13 09:31:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 09:31:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Advertiser: session connected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50063
,[ThaliCore] Session.disconnect() peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] BrowserManager.disconnect peer:D5BAF6D3-EDB2-4528-B144-7C271A324831
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: connected -> notCo,nnected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50065
[ThaliCore] Session.disconnect() peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] Browser: session notConnected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB,552AF02", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] Sessi,on.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] Browser: session notConnect,ed removed relay for Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,# Multiple local http requests
,listening on 50072
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,ok 249 should be equal
,ok 250 should be equal
,ok 251 should be equal
,# teardown
,2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:9705760D-02FE-451B-910D-A16CB2A3B940
2017-07-13 0,9:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-13 09:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryAc,tive":true,"advertisingActive":true}'
,2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
2017-07-13 09:31:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":1}'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02, (syncValue: CnVJvl4pR9vrojfMLsmnewZra1Nm0CRT)'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Advertiser: session connected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D5BAF6D3-EDB2-4528-B144-7C271A324831","generation":1}'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5BAF6D3-EDB2-4528-B144-7C271A324831 (syncValue: APKISiXlDFnfh7nSjBrwDaiwYfgCSS4X)'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: connecting -> connected
[ThaliCo,re] Browser: session connected to Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50080
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CnVJvl4pR9vrojfMLsmnewZra1Nm0CRT","error":null,"portNumber":50080}'
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CnVJvl4pR9vrojfMLsmnewZra1Nm0CRT', error: 'null', listeningPort: '50080''
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CnVJvl4pR9vrojfMLsmnewZra1Nm0CRT', error: 'null', listeningPort: '50080''
,2017-07-13 09:31:54 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'CnVJvl4pR9vrojfMLsmnewZra1Nm0CRT', originalSyncValue: 'APKISiXlDFnfh7nSjBrwDaiwYfgCSS4X''
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connecting -> connected
,ok 254 should be equal
,ok 255 (unnamed assert)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50082
2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"APKISiXlDFnfh7nSjBrwDaiwYfgCSS4X",,"error":null,"portNumber":50082}'
2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'APKISiXlDFnfh7nSjBrwDaiwYfgCSS4X', error: 'null', listeningPort: '50082''
,ok 256 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50080
[ThaliCore] Session.disconnect,() peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserManager.disconnect peer:D5BAF6D3-EDB2-4528-B144-7C271A324831
[ThaliCore] BrowserRelay.closeRelay() dis,connecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50082
[ThaliCore] Session.disconnect() peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Pee,r(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", g,eneration: 1)
[ThaliCore] Session.deinit peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
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
,ok 257 specific error should be returned
,# teardown
,ok 258 must be stopped
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
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 50084'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 261 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adv,ertisingActive":false}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'dis,coveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:31:57 - DEBUG makeIntoCloseAllServer: 'c,loseAll called on server'
,ok 263 must be stopped
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
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 50085'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0E007CD-6AFD-4D2E-86D5-09F8C6DA8F63
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:58 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called, ,on server'
,ok 266 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 50086'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B436D87A-D6B6-42AC-BEDD-AD68B0CBE06C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B436D87A-D6B6-42AC-BEDD-AD68B0CBE06C
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B436D87A-D6B6-42AC-BEDD-AD68B0CBE06C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:B436D87A-D6B6-42AC-BEDD-AD68B0CBE06C
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 269 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 50089'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 272 must be stopped
,# setup
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 273 network status should have certain non-empty properties
,# teardown
,ok 274 must be stopped
,# setup
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-13 09:31:59 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 275 specific error expected
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'listening 50090'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D4E69260-C39A-4840-9D31-596838F597AC
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CA633382-FE61-428D-8087-D0794BF51CD3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CA633382-FE61-428D-8087-D0794BF51CD3
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
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
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 50093'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9E37A147-AF17-4517-B659-3CF09F2F2475
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CDE1D319-84B4-491D-B235-FD32177C3FEF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CDE1D319-84B4-491D-B235-FD32177C3FEF
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 50095'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:02DB56A9-7BC6-4AF6-8912-24054468BC75
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4B0137E1-A725-414C-9D40-D9209EF4D7EE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4B0137E1-A725-414C-9D40-D9209EF4D7EE
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 is stopped after calling stop
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}]'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 282 connection should fail after stopping
,# teardown
,ok 283 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-13 09:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 284 must be stopped
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
,ok 285 error description matches
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
,# make sure terminateListener is properly hooked up
,2017-07-13 09:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 287 must be stopped
,# setup
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 288 error description matches
,# teardown
,ok 289 must be stopped
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
,ok 290 IMPLEMENT ME!!!!!!
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-13 09:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 292 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-13 09:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 296 NOT IMPLEMENTED # SKIP
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 298 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-13 09:32:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50099'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15DBD898-EAFA-415B-A76E-6D61B1625183
[ThaliCore] Browser.st,artListening
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
ok 303 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50100'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "838E7CB3-18DB-4D77-8D4B-A62A42190A3E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:838E7CB3-18DB-4D77-8D4B-A62A42190A3E
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 306 discoveryActive matches
ok 307 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 308 discoveryActive matches
,ok 309 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50102'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 must be stopped
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
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'listening 50103'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D5A4AB3-9902-40A4-9960-926863B49D7B
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:06 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D6CC943-67FE-4008-842A-8B37CDAD3826", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,4D6CC943-67FE-4008-842A-8B37CDAD3826
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}]'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":1}]'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":1}'
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 311 portNumber equal null
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-13 09:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
2017-07-13 09:32:07 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}]'
2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:07 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:0,7 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:07 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
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
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'listening 50105'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}]'
2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC (syncValue: WmYNTM4gsad0dec7LpA96gOv1aw1MsRy)'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:08 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
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
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF75,FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifie,r,":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"generation":null,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
2017-07-13 09:32:10 - DEBUG thaliMobile: 'E,mitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B,2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
,2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,2017-07-13 09:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", genera,tion: 0)
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WmYNTM4gsad0dec7LpA96gOv1aw1MsRy","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'WmYNTM4gsad0dec7LpA96gOv1aw1MsRy', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8D,C3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC
2017-07-13 09:32:14 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2D1BE89A-3F6E-4C07-9680-7C097E53E609 (syncValue: PBST85euG6l3bQ5lGnqSNLPVjTonRYIg)'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
[ThaliCore] Session.disconnect() peer:2D1BE89A-3F6,E-4C07-9680-7C097E53E609:0
2017-07-13 09:32:15 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
2017-07-13 09:32:,15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:15 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:15 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
[ThaliCore] Advertiser: session connected Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", genera,tion: 0)
2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PBST85euG6l3bQ5lGnqSNLPVjTonRYIg","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'PBST85euG6l3bQ5lGnqSNLPVjTonRYIg', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097,E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"generation":null,"po,rtNumber":null,"recreated":true}'
2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCor,e] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
,2017-07-13 09:32:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609
,2017-07-13 09:32:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AE6727F4-D361-4B1F-BB82-6390F9AEED26 (syncValue: 3B0EkNsCRH3UHG5nHs9qRjqNYVyGnvEO)'
,2017-07-13 09:32:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
[ThaliCore] Session.startOutputStream(with:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50113
,2017-07-13 09:32:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3B0EkNsCRH3UHG5nHs9qRjqNYVyGnvEO","error":null,"portNumber":50113}'
,2017-07-13 09:32:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3B0EkNsCRH3UHG5nHs9qRjqNYVyGnvEO', error: 'null', listeningPort: '50113''
,2017-07-13 09:32:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [11, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:22 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:22 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
,ok 314 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:32:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50113
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:12 []
[ThaliCore] Session.disconnect() peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'listening 50115'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DF05128D-1A79-441D-A792-B41B4F6EBF99
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
2017-07-13 09:32:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
[Thali,Core] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285 (syncValue: nbvUEps8ldWhLlPdye28shUnnKiOnv8w)'
2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED,8F2C8FA285", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:,socketDisconnected:stoppedListening:)
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}]'
2017-07-13 09:32:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
2017-07-13 09:32:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}]'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
2017-07-13 09:32:26 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}]'
2017-07-13 09:32:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}'
,2017-07-13 09:32:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}]'
2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","generation":0}'
,2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:29 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"AE6727F4-D361-4B1F-BB82-6390F9AEED26","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", genera,tion: 0)
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nbvUEps8ldWhLlPdye28shUnnKiOnv8w","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'nbvUEps8ldWhLlPdye28shUnnKiOnv8w', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C,8FA285","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:32:30 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49058887-1F08-49CB-9D96-189287BA7435 (syncValue: eDvKrTeeHgSjqxPiaa99YcC4zNk7dF47)'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-13 09:32:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50122
,2017-07-13 09:32:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eDvKrTeeHgSjqxPiaa99YcC4zNk7dF47","error":null,"portNumber":50122}'
,2017-07-13 09:32:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eDvKrTeeHgSjqxPiaa99YcC4zNk7dF47', error: 'null', listeningPort: '50122''
,2017-07-13 09:32:33 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:33 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:33 - DEBUG testUtils: 'Got end'
,ok 316 response body should match testData
,ok 317 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685
[ThaliCore] Advertiser: session connected Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685
,[ThaliCore] Session.session(_:peer:didChange:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685
,[ThaliCore] Session.startOutputStream(with:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [14]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconn,ectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B70368F2-7DD2-45E3-B372-39900CFF0685 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B70368F2-7DD2-45E3-B372-39900CFF0685
,2017-07-13 09:32:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 318 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:49058887-1F08-49CB-9D96-189287BA7435
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50122
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:B70368F2-7DD2-45E3-B372-39900CFF0685
,# setup
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-13 09:32:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 319 must be stopped
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
,ok 320 must be stopped
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
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'listening 50125'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:37CFCA29-0ABA-44F0-BDA5-472B4FAEC525
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:946EA4DB-6614-40DB-B5B5-705E7310BB5E
2017-07-13 0,9:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
2017-07-13 09:32:41 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}]'
2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:41 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C084CE57-C7F3-4479-BF0F-ED3250D8F6A8 (syncValue: 801uuT9VbGKLJWrhgRfZcR7roHflFC2i)'
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C084CE57-C7F3-4479-BF0F-,ED3250D8F6A8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}]'
2017-07-13 09:32:42 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
2017-07-13 09:32:42 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}]'
2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generati,on: 0)
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"801uuT9VbGKLJWrhgRfZcR7roHflFC2i","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: ,'Got multiConnectResolved -syncValue: '801uuT9VbGKLJWrhgRfZcR7roHflFC2i', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentif,ier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8,F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F10A0D7-8856-4298-AD0B-593BA1AE204A (syncValue: OS93WUkTvDRa27zonkpZBU2gJ6Zrsslr)'
,2017-07-13 09:32:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50132
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OS93WUkTvDRa27zonkpZBU2gJ6Zrsslr","error":null,"portNumber":50132}'
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OS93WUkTvDRa27zonkpZBU2gJ6Zrsslr', error: 'null', listeningPort: '50132''
,2017-07-13 09:32:49 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:50 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:50 - DEBUG testUtils: 'Got end'
,ok 321 response body should match testData
,ok 322 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB
[ThaliCore] Advertiser: session connected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
[ThaliCore] Advertiser: session connected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
,2017-07-13 09:32:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}]'
,2017-07-13 09:32:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","generation":0}'
,2017-07-13 09:32:55 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-13 09:32:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C084CE57-C7F3-4479-BF0F-ED3250D8F6A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB
[ThaliCore] Session.startOutputStream(with:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,6 [15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
,[ThaliCore] Session.session(_:peer:didChange:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
,[ThaliCore] Session.startOutputStream(with:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:5,8 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:32:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 must be stopped
[ThaliCore] BrowserManager.disconnect peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50132
[Thali,Core] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote p,eer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSo,cketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:9F10A0D7-8856-4298-AD0B-593BA1AE2,04A:0
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [16, 17]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket clo,sed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Advert,iserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [17]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnect,ing:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 []
[ThaliCore] Session.session(_:peer:didChange:) peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0 state: connected -> notConnected
[ThaliCore] Browser: sess,ion notConnected Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B08B11C3-3DC6-43DF-BB8E-586AC08C3BAB state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 324 FIX ME, PLEASE!!!
,# teardown
,ok 325 must be stopped
,# setup
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-13 09:32:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 326 must be stopped
,# setup
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-13 09:32:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 327 must be stopped
,# setup
,ok 328 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 329 specific error should be returned
,# teardown
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 330 error should be null
,ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 333 specific error should be returned
,# teardown
,ok 334 error should be null
,ok 335 error should be null
,# setup
,ok 336 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 50136'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 337 error should be null
,ok 338 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 339 error should be null
,ok 340 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 50137'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1FD11605-2307-43B6-912D-1D92D8B4E432
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 344 error should be null
ok 345 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
# teardown
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}]'
2017-07-13 09:33:00 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 50138'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DB7F91CC-5F83-4342-8F23-F6623E1C96C1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DB7F91CC-5F83-4342-8F23-F6623E1C96C1
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 351 error should be null
,ok 352 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DB7F91CC-5F83-4342-8F23-F6623E1C96C1", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DB7F91CC-5F83-4342-8F23-F6623E1C96C1
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 353 error should be null
ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:01 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 50141'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 358 error should be null
,ok 359 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 360 error should be null
,ok 361 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-13 09:33:02 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 365 This should not cause wifi to fail
,ok 366 native router should be bad
,# teardown
,ok 367 error should be null
,ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'listening 50142'
,ok 370 first call should succeed
,ok 371 first call should succeed
,ok 372 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-13 09:33:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 373 error should be null
,ok 374 error should be null
,# setup
,ok 375 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-13 09:33:02 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 376 error should be null
,ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-13 09:33:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c7917bd1-cc7a-4cd4-9ac3-2d332a295d67","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 382 should be called once
,ok 383 should not have been called more than once
,# teardown
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c7917bd1-cc7a-4cd4-9ac3-2d332a295d67","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 384 error should be null
,ok 385 error should be null
,# setup
,ok 386 ThaliMobile should be stopped
,# can get the network status
,ok 387 network status should have certain non-empty properties
,# teardown
,ok 388 error should be null
ok 389 error should be null
,# setup
,ok 390 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 391 we have not added peer to the cache yet
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a91ba2c8-5017-41c1-aaf9-9880816fb641","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 392 peer should be available
ok 393 cache contains native peer
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a91ba2c8-5017-41c1-aaf9-9880816fb641","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 394 peer should be unavailable
ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4410947d-f53d-48aa-ad9b-2c1bc7ad8b6b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 400 peer should be available
,ok 401 cache contains wifi peer
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4410947d-f53d-48aa-ad9b-2c1bc7ad8b6b","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 402 peer should be unavailable
,ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
,ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ccc392aa-a33b-4973-9274-b60d22563ac3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 407 first peer is available
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ea0bff64-573d-49cf-a482-204f2eb73ae9","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 second peer is available
,ok 409 first and second peers are different
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ccc392aa-a33b-4973-9274-b60d22563ac3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ea0bff64-573d-49cf-a482-204f2eb73ae9","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b36c24f8-e68e-4178-9e72-a40e0b93ccd2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 414 peer is available
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b36c24f8-e68e-4178-9e72-a40e0b93ccd2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 415 error should be null
,ok 416 error should be null
,# setup
,ok 417 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-13 09:33:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-13 09:33:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aba9a929-b329-424d-aade-93915677c5a6","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 424 peer should be available
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aba9a929-b329-424d-aade-93915677c5a6","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 425 peer should be available
ok 426 should store correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"aba9a929-b329-424d-aade-93915677c5a6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
,ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 50143'
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f7e42bf-04a1-4662-a70a-08815772ae1a","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f7e42bf-04a1-4662-a70a-08815772ae1a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8f7e42bf-04a1-4662-a70a-08815772ae1a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 50144'
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"724ae36d-622b-4182-a26d-9a03a2afdea0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 discovered available peer
,ok 438 peer is available
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"724ae36d-622b-4182-a26d-9a03a2afdea0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 439 error should be null
,ok 440 error should be null
,# setup
,ok 441 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e57abcb8-1687-462f-bda3-f2abcad89f29","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 442 peer should be available
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e57abcb8-1687-462f-bda3-f2abcad89f29","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 443 peer should be unavailable
,ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 50145'
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ae29dc6-4aaa-4e6a-8037-dde7530b2919","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 448 first peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"634807aa-089b-4170-aa47-58993dd30337","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 449 second peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"634807aa-089b-4170-aa47-58993dd30337","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 450 peer became unavailable
,ok 451 it was wifi peer
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"634807aa-089b-4170-aa47-58993dd30337","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 we found peer again
,ok 453 it was wifi peer
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"634807aa-089b-4170-aa47-58993dd30337","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 454 peer became unavailable
,ok 455 it was wifi peer
,# teardown
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0ae29dc6-4aaa-4e6a-8037-dde7530b2919","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 456 error should be null
,ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-13 09:33:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 50146'
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c474b90-8198-42ea-ba4f-7124c9a0ae38","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 first peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3bad8ae1-42fd-4c4d-a071-a322cf33499e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 463 second peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6c474b90-8198-42ea-ba4f-7124c9a0ae38","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3bad8ae1-42fd-4c4d-a071-a322cf33499e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-13 09:33:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-13 09:33:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 472 error should be null
ok 473 error should be null
,# setup
,ok 474 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"437f0162-479a-4303-8d31-2f29ca7bb535","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 475 peer discovered first time does not have new address
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"437f0162-479a-4303-8d31-2f29ca7bb535","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 476 address has not been changed
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"437f0162-479a-4303-8d31-2f29ca7bb535","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 477 new port handled correctly
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"437f0162-479a-4303-8d31-2f29ca7bb535","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 478 new host handled correctly
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"437f0162-479a-4303-8d31-2f29ca7bb535","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 479 newAddressPort is null for unavailable peers
,# teardown
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-13 09:33:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 486 NOT IMPLEMENTED # SKIP
,# teardown
,ok 487 error should be null
,ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-13 09:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 493 should be equal
,# teardown
,ok 494 error should be null
,ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-13 09:33:10 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 500 contains expected properties
,ok 501 the same hostAddress
,ok 502 the same portNumber
,# teardown
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-13 09:33:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 506 contains expected properties
ok 507 the same hos,tAddress
ok 508 the same portNumber
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 50147'
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f0f5c856-be4b-4b4f-9569-e022c7c1e902","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f0f5c856-be4b-4b4f-9569-e022c7c1e902","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 50148'
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"aae6579e-24dd-444b-baea-632c78e54aae","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:aae6579e-24dd-444b-baea-632c78e54aae
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"aae6579e-24dd-444b-baea-632c78e54aae","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-13 09:33:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 521 error should be null
ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-13 09:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 524 error should be null
ok 525 error should be null
,# setup
,ok 526 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-13 09:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 527 error should be null
,ok 528 error should be null
,# setup
,ok 529 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,ok 532 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 533 error should be null
ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 536 error should be null
ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-13 09:33:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 539 error should be null
ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'listening 50149'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FA667D10-F6D9-49F5-9CF3-C9B39EC29707
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4ace3230-3301-44ba-af9b-a3f13227e674","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 542 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"14413151-83ee-41c8-af17-11152641f349","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4ace3230-3301-44ba-af9b-a3f13227e674","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"14413151-83ee-41c8-af17-11152641f349","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 544 No peers
,ok 545 No peers
,ok 546 No peers
,# teardown
,ok 547 error should be null
,ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'listening 50150'
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7d2e913c-e61b-4fe8-90b9-efa12c49c96b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 550 1
,ok 551 2
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"365fb9e6-1e6c-4d76-bfff-b5c17f428de9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7d2e913c-e61b-4fe8-90b9-efa12c49c96b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"365fb9e6-1e6c-4d76-bfff-b5c17f428de9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 552 error should be null
,ok 553 error should be null
,# setup
,ok 554 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-13 09:33:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 555 error should be null
,ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'listening 50151'
,ok 558 error should be null
,ok 559 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5FCCD746-4D8D-40F2-BC08-F7A42F066745
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 560 error should be null
,ok 561 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] Browser.startListening
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 562 error should be null
,ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8B,DD-C59AF4B70C3B","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","generation":0}]'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B (syncValue: 0)'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","generation":0}]'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
[ThaliCore] Advertiser: session connected Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] Session.session(_:peer:didChange:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20 state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066,745", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
,[ThaliCore] Session.disconnect() peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
,2017-07-13 09:33:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}]'
,2017-07-13 09:33:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","generation":0}'
,2017-07-13 09:33:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-13 09:33:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
,[ThaliCore] Session.session(_:peer:didChange:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] Session.startOutputStream(with:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
[ThaliCore] Session.startOutputStream(with:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", genera,tion: 0)
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2,889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","pe,erAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"portNumber":null,"r,ecreated":true}'
,2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8F99E40C-F002-41B4-82DB-5743D21B8724 (syncValue: 1)'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:completion:) Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCo,re] Session.init(session:identifier:connected:notConnected:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:),
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativ,eWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:33:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailability,Changed - Emitting {"peerIdentifier":"B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50159
,2017-07-13 09:33:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50159}'
,2017-07-13 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 39984708-4DDD-48C8-82A8-BD25A56C4040 (syncValue: 2)'
,2017-07-13 09:33:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:28 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:28 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50163
,2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50163}'
,[ThaliCore] BrowserManager.disconnect peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B
,[ThaliCore] BrowserManager.disconnect peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [18, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:31 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:31 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,2017-07-13 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8F99E40C-F002-41B4-82DB-5743D21B8724","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-13 09:33:31 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13, 09:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeS,treams() vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] Vi,rtualSocket.closeStreams() vsID:19
ok 565 error should be null
,ok 566 error should be null
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:18 [19, 20, 21]
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [19, 20]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:19 [20]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 []
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,# setup
,ok 567 ThaliMobile should be stopped
,# test for data corruption
,2017-07-13 09:33:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 568 error should be null
,ok 569 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 570 getPeerIdentifier
,ok 571 getConnectionType
,ok 572 getActionType
,ok 573 getActionState
,ok 574 getPskIdentity
,ok 575 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 576 initial state
,ok 577 after start
,2017-07-13 09:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 578 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 579 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-13 09:33:33 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 580 clean kill
,ok 581 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 582 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 583 forever agent should have it's own destroy method
,ok 584 agent's destroy should be called
,ok 585 agent's destroy should not be called again
,ok 586 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 587 Entry counter must be 1
,ok 588 Entry exists
,ok 589 Size must be 1
,ok 590 Entry counter must be 2
,ok 591 Entry exists
,ok 592 Size must be 2
,ok 593 Entry counter must be 1
,ok 594 Entry exists
,ok 595 Size must be 3
,ok 596 Entry counter must be 2
,ok 597 Entry exists
ok 598 Size must be 4
,ok 599 Entry 1_1 should not be found
,ok 600 Entry 1_1 does not exist
,ok 601 Size must be 3
,ok 602 Entry 1_2 should not be found
,ok 603 Entry 1_2 does not exist
,ok 604 Size must be 2
,ok 605 should be equal
,ok 606 Entry 2_1 should not be found
,ok 607 Entry 2_2 should not be found
,ok 608 Entry 2_1 does not exist
,ok 609 Entry 2_2 does not exist
ok 610 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 611 Size must be100
,ok 612 Entries between 20 and MAXSIZE + 20 should exist
,ok 613 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 614 Entries between 6 and MAXSIZE + 4 should exist
,ok 615 Size should be MAXSIZE
,ok 616 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 617 WAITING state entry should not be removed
,ok 618 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 619 Size should be MAXSIZE
,ok 620 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 621 Kill should be called once
,ok 622 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 623 is an agent
,ok 624 enqueue is fine
,ok 625 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 626 is an agent
,ok 627 first enqueue is fine
,ok 628 is an agent
,ok 629 second enqueue is fine
,ok 630 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 631 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 632 is an agent
,ok 633 good enqueue
,ok 634 Identity should match
,2017-07-13 09:33:40 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:40 - DEBUG testUtils: 'Got end'
,ok 635 Got expected response
,ok 636 Got psk call back
,# teardown
,2017-07-13 09:33:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 637 is an agent
,ok 638 enqueue worked
,ok 639 is an agent
,ok 640 enqueue 2 worked
,ok 641 enqueue is not available when stopped
,ok 642 start action is killed
,ok 643 killed action is still killed
,ok 644 enqueued action when stopped is killed
,ok 645 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 646 good start
ok 647 good enqueue
,ok 648 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 649 null arg
,ok 650 wrong arg type
,ok 651 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 652 good enqueue
,ok 653 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 654 good enqueue
ok 655 2nd good enqueue
ok 656 we are in the pool
,ok 657 We are out of the pool
,ok 658 Action was killed
,ok 659 The original kill was called too
,ok 660 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 661 good enqueue
,ok 662 first kill
,ok 663 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 664 1st good enqueue
ok 665 2nd good enqueue
ok 666 1st action is in the pool
ok 667 2nd action is in the pool
,ok 668 1st action is out of the pool
,ok 669 2st action is out of the pool
,ok 670 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-13 09:33:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 671 Got right error
,ok 672 Start should not be called
,ok 673 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-13 09:33:43 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:43 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 674 Got right error
,ok 675 Start should not be called
,ok 676 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 677 Got null
2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 678 is an agent
2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 679 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 680 Got Null
,ok 681 Got another null
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 682 is an agent
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 683 is an agent
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 684 Action 1 killed at least once
,ok 685 Action 1 went first
ok 686 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 687 should have gotten null
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 688 Should have stopped nicely
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 689 Still looking for null
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 690 Yup, another null
,ok 691 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 692 Null 1
ok 693 (unnamed assert)
2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 694 is an agent
,ok 695 Null 3
,ok 696 Replication not yet called
,ok 697 Notification 2 not yet called
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 698 is an agent
,ok 699 Notification went first
,ok 700 Notification 2 not called yet
2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 701 is an agent
,ok 702 Notification finished
,ok 703 Replication finished
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 704 is an agent
,ok 705 First does not throw
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 706 is an agent
,ok 707 Second does not throw
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 708 is an agent
,ok 709 first ok
,2017-07-13 09:33:46 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 second ok
,ok 712 third ok
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
,ok 713 peerIdentifier should match
ok 714 generation should match
,ok 715 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 716 good beacon
,ok 717 good preAmble
,ok 718 public keys match!
,ok 719 must return null after successful call
,ok 720 Once start returns the action should be in KILLED state
,# teardown
,2017-07-13 09:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 721 Response should be HTTP_BAD_RESPONSE
,ok 722 must return null after successful call
,# teardown
,2017-07-13 09:33:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 723 Response should be NETWORK_PROBLEM
,ok 724 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-13 09:33:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 725 Resolution should be BAD_PEER
,ok 726 correct error message
,# teardown
,2017-07-13 09:33:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 727 Call start once
,ok 728 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 729 must return null after successful call.
,# teardown
,2017-07-13 09:33:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 730 Should be Killed
ok 731 Start after killed
,# teardown
,2017-07-13 09:33:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 732 Should be KILLED
,ok 733 must return null after successful kill
,# teardown
,2017-07-13 09:33:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 734 Should be KILLED
,ok 735 must return null after successful kill
,# teardown
,2017-07-13 09:33:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 736 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 737 must return null after successful call
,# teardown
,2017-07-13 09:33:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-13 09:33:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 738 Should be NETWORK_PROBLEM caused closing server socket
,ok 739 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 740 Should be NETWORK_PROBLEM caused closing client socket
ok 741 Should be Could not establish TCP connection
,# teardown
,2017-07-13 09:33:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 742 publicKeysToNotify cannot be null
,ok 743 ecdh for local device cannot be null
,ok 744 milliseconds cannot be less than 0
,ok 745 milliseconds cannot be 0
,ok 746 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 747 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 748 should be equal
,ok 749 should be equal
,ok 750 (unnamed assert)
,ok 751 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 752 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 753 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 754 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 755 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 756 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 757 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 758 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 759 should be equal
,ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 763 right number of calls to address book
ok 764 good preAmble
,ok 765 good unencryptedKeyId
,ok 766 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 767 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 768 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 769 Matching numbers
,ok 770 We have an entry!
,ok 771 keys match
,ok 772 secrets match
,ok 773 We have an entry!
,ok 774 keys match
,ok 775 secrets match
,ok 776 We have an entry!
,ok 777 keys match
ok 778 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 779 Streams have same length
,ok 780 matching size
,ok 781 keys match
,ok 782 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 783 should be equal
,ok 784 peerDictionalty contains 2 peers
,ok 785 bluetooth peer's notification has correct connection type
,ok 786 tcp peer's notification has correct connection type
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-13 09:34:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 787 notification peer dictionary contains exactly 1 peer
,2017-07-13 09:34:06 - WARN thaliNotificationClient: 'peer is not available'
,ok 788 notification peer dictionary does not contain any peers
,2017-07-13 09:34:06 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-13 09:34:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 789 entry exists
,ok 790 entry is resolved
,# teardown
,2017-07-13 09:34:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 791 Action should be KILLED
ok 792 Peer state should be RESOLVED
,# teardown
,2017-07-13 09:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 793 hostAddress must match
,ok 794 portNumber must match
,ok 795 suggestedTCPTimeout must match
,ok 796 connectionType must match
,ok 797 peerIDs must match
,# teardown
,2017-07-13 09:34:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 798 Correct error
,# teardown
,2017-07-13 09:34:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 799 hostAddress must match
,ok 800 portNumber must match
,ok 801 suggestedTCPTimeout must match
,ok 802 connectionType must match
,ok 803 peerIds must match
,# teardown
,2017-07-13 09:34:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 804 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 805 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-13 09:34:11 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 807 action should be resolved with NETWORK_PROBLEM error
ok 808 correct number of requests
ok 809 correct number of failures
ok 810 correct final peer state
,# teardown
,2017-07-13 09:34:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-13 09:34:13 - WARN thaliNotificationClient: 'peer is not available'
2017-07-13 09:34:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 811 peerDictionary should become empty
,# teardown
,2017-07-13 09:34:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-13 09:34:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 812 failed with expected error
,ok 813 peer state should be RESOLVED
,# teardown
,2017-07-13 09:34:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-13 09:34:14 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 First action failed
,ok 815 second action killed
# teardown
,2017-07-13 09:34:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 816 secrets are equal
,ok 817 Public key matches with the server key
,ok 818 hostAddress must match
,ok 819 portNumber must match
,ok 820 suggestedTCPTimeout must match
,ok 821 connectionType must match
,# teardown
,2017-07-13 09:34:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 822 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 823 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 824 All entries should be expired after 1 second
,# teardown
,2017-07-13 09:34:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 825 All keys need to be available in the cache
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-13 09:34:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 827 Size of the cache should be 2
ok 828 Cache doesn't contain dictionary1
,ok 829 Size of the cache should be 1
ok 830 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-13 09:34:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 831 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 832 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 833 StartUpdateAdvertisingAndListening should not be called
,ok 834 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 835 no error
ok 836 should be 204
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 837 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 838 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-13 09:34:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 839 no error
,ok 840 should be 200
,ok 841 should be equal
,ok 842 should be equal
,ok 843 (unnamed assert)
,ok 844 no error
,ok 845 should be 204
,# teardown
,2017-07-13 09:34:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 846 error should be null
ok 847 should be 204
,# teardown
,2017-07-13 09:34:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 848 should be 404
,# teardown
,2017-07-13 09:34:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 849 equal keys
,ok 850 not equal connection type
,ok 851 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-13 09:34:24 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 852 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 853 second cleared dictionary
,2017-07-13 09:34:24 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 854 First start and on called correctly
,ok 855 First stop and removeListener called correctly
,ok 856 first action kill called
,ok 857 second action kill called
,ok 858 first cleared dictionary
,ok 859 first cleared pool
,ok 860 second cleared dictionary
,ok 861 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 862 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-13 09:34:25 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 863 listener has been set
,ok 864 peer dictionary has expected number of entries
,ok 865 Dictionary and pool have same action
,ok 866 ads match
,ok 867 PouchDB matches
,ok 868 DB Names match
,ok 869 public keys match
,ok 870 peer dictionary has expected number of entries
,ok 871 Dictionary and pool have same action
,ok 872 ads match
,ok 873 PouchDB matches
,ok 874 DB Names match
,ok 875 public keys match
,2017-07-13 09:34:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 876 start called once
,ok 877 One entry left
,ok 878 Dictionary and pool have same action
,ok 879 Start never called
,ok 880 Kill called once
,ok 881 no entries left
,ok 882 Third action is dead
,ok 883 peer dictionary has expected number of entries
,ok 884 Dictionary and pool have same action
,ok 885 ads match
,ok 886 PouchDB matches
,ok 887 DB Names match
,ok 888 public keys match
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
,ok 889 right error
,# teardown
,2017-07-13 09:34:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-13 09:34:26 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 890 right error
,# teardown
,2017-07-13 09:34:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 891 Got error as expected
,# teardown
,2017-07-13 09:34:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-13 09:34:27 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 892 Got error as expected
,# teardown
,2017-07-13 09:34:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-13 09:34:28 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-13 09:34:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 893 Got error as expected
,# teardown
,2017-07-13 09:34:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-13 09:34:31 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:31 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:34 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 894 should be equal
,ok 895 All tests passed!
,# teardown
,2017-07-13 09:34:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-13 09:34:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:37 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:39 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 896 should be equal
ok 897 All tests passed!
,# teardown
,2017-07-13 09:34:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-13 09:34:40 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-13 09:34:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-13 09:34:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 898 action should be killed
ok 899 Error should be timed out
,ok 900 No doc found
,# teardown
,2017-07-13 09:34:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-13 09:34:44 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-13 09:34:45 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 901 should be equal
,2017-07-13 09:34:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-13 09:34:46 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 902 action should be killed
,ok 903 Error should be timed out
,# teardown
,2017-07-13 09:34:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 904 socket hung up
,# teardown
,2017-07-13 09:34:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 905 same getPeerAdvertisesDataForUs
,ok 906 Same pouchdB
,ok 907 same localDbName
,ok 908 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'listening 50291'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Browser.startListening
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8
2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","generation":0}]'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","generation":0}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 3)'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Advertiser: session connected Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E48E184A-0302-4946-8B90-52C396560D15:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","generation":0}]'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","generation":0}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E48E184A-0302-4946-8B90-52C396560D15:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50294
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50294}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 4)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":50294}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E state: connecting -> connected
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 5)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":50294}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 6)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":50294}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 7)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [22]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [22, 23]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [22, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [22, 23, 24, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [22, 23, 24, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [22, 23, 24, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [22, 23, 24, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Advertiser: session connected Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6 state: notConnected -> connecting
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [23, 24, 25, 26, 27, 28, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withEr,ror:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [23, 24, 25, 27, 28, 29]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [23, 24, 25, 28, 29]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [23, 24, 25, 29]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [24, 25, 29]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [24, 25]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [24, 25, 30]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [25, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [25, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0 state: notConnected -> connecting
,2017-07-13 09:34:54 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [25, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [25, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [25, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [25, 30, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,6 [25, 30, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [25, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [25, 30, 31, 32, 33, 34, 35, 36, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [25, 30, 31, 32, 33, 34, 35, 37, 38]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [25, 30, 31, 32, 33, 34, 35, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] TCPClient: didConnectToHost, active connection,s count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [25, 30, 31, 32, 33, 34, 35, 37, 38, 39, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [25, 30, 31, 32, 33, 34, 35, 37, 38, 40]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [25, 30, 31, 32, 33, 34, 35, 37, 40]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [25, 30, 31, 32, 33, 34, 35, 37, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:34:56 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:41 [25, 30, 31, 32, 33, 34, 35, 37, 40]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50317
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":50317}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 8)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":50317}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 9)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":50317}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427 (syncValue: 10)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":50317}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,3 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2C,FAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44, 45, 46, 47, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 44, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [25, 30, 31, 32, 33, 34, 35, 37, 40, 42, 43, 45, 46, 47, 48, 49]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:42 [25, 30, 31, 32, 33, 34, 35, 37, 40, 43, 45, 46, 47, 48, 49]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vs,ID:43 [25, 30, 31, 32, 33, 34, 35, 37, 40, 45, 46, 47, 48, 49]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [25, 30, 31, 32, 33, 34, 35, 37, 40, 45, 46, 48, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [25, 30, 31, 32, 33, 34, 35, 37, 40, 45, 46, 49]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [25, 30, 31, 32, 33, 34, 35, 37, 40, 46, 49]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,0 [25, 30, 31, 32, 33, 34, 35, 37, 40, 46, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [25, 30, 31, 32, 33, 34, 35, 37, 40, 46, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:46 [25, 30, 31, 32, 33, 34, 35, 37, 40, 50]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [25, 30, 31, 32, 33, 34, 35, 37, 40, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [25, 30, 31, 32, 33, 34, 35, 37, 40, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [25, 30, 31, 32, 33, 34, 35, 37, 40, 50, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:31 [25, 30, 32, 33, 34, 35, 37, 40, 50, 51, 52,, 53]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [25, 30, 32, 34, 35, 37, 40, 50, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [25, 30, 32, 35, 37, 40, 50, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketD,idDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [25, 30, 32, 35, 40, 50, 51, 52, 53]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [25, 32, 35, 40, 50, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [25, 35, 40, 50, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [25, 40, 50, 51, 52, 53]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [25, 50, 51, 52, 53]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [25, 50, 51, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [25, 50, 51, 52, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Session.startOutputStream(with:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,6 [25, 50, 51, 52, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [25, 50, 51, 52, 53, 54, 55, 56, 57]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [25, 50, 51, 52, 53, 54, 55, 56, 57, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [25, 50, 51, 52, 53, 54, 55, 56, 58]
,2017-07-13 09:34:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
[Thali,Core] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [25, 50, 51, 52, 53, 55, 56, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [25, 50, 51, 52, 53, 55, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:50 [25, 51, 52, 53, 55, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [25, 51, 52, 55, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:35:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-13 09:35:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:51
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [25, 52, 55, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
,[ThaliCore] VirtualSocket.deinit vsID:52 [25, 55, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [25, 58]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] VirtualSocket.deinit vsID:58 [25]
,2017-07-13 09:37:50 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-13 09:37:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:37:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:37:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:37:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisem,ents without calling start is NOT an error'
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
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
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
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
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
    at SubError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxco,re/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-13 09:44:50 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 909 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-13 09:44:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-4,8E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E,0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/3B3E98EA-0BCE-48E0-A2F0-2A4C893C0560/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
