#### Test 113351851e5b8da0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/81F8D70E-20E0-4CD6-8848-808AA2655E2A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/81F8D70E-20E0-4CD6-8848-808AA2655E2A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851e5b8da0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50592"
,(lldb)     command script import "/tmp/81F8D70E-20E0-4CD6-8848-808AA2655E2A/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:28:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests,.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3641379D-DB2F-4B3C-9C40-0D44C505E97C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3641379D-DB2F-4B3C-9C40-0D44C505E97C
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6D7E91F7-ADAC-4E8B-8C80-DE986EEA32A4
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:68878542-,5FF4-48FD-8CD5-458AECF86285
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CB70C33A-D5D7-47C2-9221-36F73C4894ED", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:CB70C33A-D5D7-47C2-9221-36F73C4894ED
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CB70C33A-D5D7-47C2-9221-36F73C4894ED:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CB70C33A-D5D7-47C2-9221-36F73C4894ED", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 09:28:28 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.591582000255585
,2017-07-13 09:28:28 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-07-13 09:28:28 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CB70C33A-D5D7-47C2-9221-36F73C4894ED:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CB70C33A-D5D7-47C2-9221-36F73C4894ED", generation: 0)
,2017-07-13 09:28:32 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 09:28:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 09:28:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 09:28:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 09:28:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 09:28:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 09:28:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 09:28:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 09:28:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 09:28:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 09:28:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 09:28:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 09:28:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:28:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:28:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:29:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:29:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
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
2017-07-13 09:29:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in ,the checkpoints plugin delay interval''
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
ok 8 should be equal
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
,ok 32 fourth
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
,# teardown
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
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-13 09:29:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:54081625-D1BE-4D55-A214-2FC237F1D8AB
,[ThaliCore] Browser.startListening
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
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
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F820D784-7540-488F-89C4-0B97E6B00FEE
[ThaliCore] Browser.startListening
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:43 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:44 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4CAB1969-297C-4E7C-A6EE-DC4637F2E145", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4CAB1969-297C-4E7C-A6EE-DC4637F2E145
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUp,d,ate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E540D9F-C900-49CF-B20F-EFF6FCF433E8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9E540D9F-C900-49CF-B20F-EFF6FCF433E8
,2017-07-13 09:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E540D9F-C900-49CF-B20F-EFF6FCF433E8", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:9E540D9F-C900-49CF-B20F-EFF6FCF433E8
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
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 84 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:29:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8CA63532-F679-4683-AE6B-8D8E453DB975", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8CA63532-F679-4683-AE6B-8D8E453DB975
2017-07-13 0,9:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:29:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9068A14E-5317-46F5-BBC1-B024A5B77C39
[Thali,C,ore] Browser.startListening
2017-07-13 09:29:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:29:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:47 - INFO thaliMobile: 'Filtered, out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:70431CAA-E8FA-425D-A5B4-088C35618AEB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "70431CAA-E8FA-425D-A5B4-088C35618AEB", generation: 0)
,ok 88 peers must be an array
ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8CA63532-F679-4683-AE6B-8D8E453DB975:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8CA63532-F679-4683-AE6B-8D8E453DB975", generation: 0)
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
,2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:29:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:29:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DEB213F8-7240-427B-A28E-AEECE8ABFAF9
2017-07-13 0,9:29:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:29:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:29:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAd,vertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:09EB8CF9-E405-4EF1-9FBC-1B64CAEE2620
[ThaliCore] Browser.startListening
2017-07-13 09:29:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":true,"advertisingActive":true}'
2017-07-13 09:29:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","st,a,rtArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:29:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,2017-07-13 09:29:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","generation":0}'
,2017-07-13 09:29:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 001FF42C-B081-4001-A9F2-6BB3561908F9 (syncValue: kfrGPQ5qzusfypxMRgxQwgGWMNrdEfLw)'
,2017-07-13 09:29:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53
[ThaliCore] Advertiser: session connected Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DEB213F8-7240-427B-A28E-AEECE8ABFAF9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49902
,2017-07-13 09:29:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kfrGPQ5qzusfypxMRgxQwgGWMNrdEfLw","error":null,"portNumber":49902}'
2017-07-13 09:29:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kfrGPQ5qzusfypxMRgxQwgGWMNrdEfLw', error: 'null', listeningPort: '49902''
,2017-07-13 09:29:59 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53
,[ThaliCore] Session.session(_:peer:didChange:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53 state: connecting -> connected
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BCA5C49A-1B68-480D-9939-27D9A9088049:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BCA5C49A-1B68-480D-9939-27D9A9088049", generation: 0)
2017-07-13 09:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BCA5C49A-1B68-480D-9939-27D9A9088049","generation":0}'
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
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49902
[ThaliCore] Session.disconnect() peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "DEB213F8-7240-427B-A28E-AEECE8ABFAF9", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:38A8EF76-CCE5-45C5-8361-FB977DEB8A53
,# setup
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C
2017-07-13 0,9:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B3BBCE61-9D6B-46AA-B78C-2F0B09708D00
[Tha,l,iCore] Browser.startListening
2017-07-13 09:30:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:30:06 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
2017-07-13 09:30:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","generation":0}'
2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 001FF42C-B081-4001-A9F2-6BB3561908F9, (syncValue: RlPkgYRWPKBK86G8J8J5gA4PtWRBECPT)'
2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,2017-07-13 09:30:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
2017-07-13 09:30:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:001FF42C-B081-4001-A9F2-6BB3561908F9:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "001FF42C-B081-4001-A9F2-6BB3561908F9", genera,tion: 0)
2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RlPkgYRWPKBK86G8J8J5gA4PtWRBECPT","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'RlPkgYRWPKBK86G8J8J5gA4PtWRBECPT', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:12 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"001FF42C-B081-4001-A9F2-6BB3561908F,9","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7013A18A-B3A3-429C-A561-7CE2E3F66643 (syncValue: BipIsOk,HXqhww6cSwuY4uHx58PEx343p)'
2017-07-13 09:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7013A18A-B3A3-429C-A561-7CE2E3F6664,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
[ThaliCore] Advertiser: session connected Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49909
,2017-07-13 09:30:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BipIsOkHXqhww6cSwuY4uHx58PEx343p","error":null,"portNumber":49909}'
,2017-07-13 09:30:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BipIsOkHXqhww6cSwuY4uHx58PEx343p', error: 'null', listeningPort: '49909''
,Connecting to the localhost:49909
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,Connected to the localhost:49909
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:30:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 104 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
,[ThaliCore] Session.session(_:peer:didChange:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
[ThaliCore] Session.startOutputStream(with:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
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
,2017-07-13 09:30:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,09:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 09:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:30:17 - INFO thaliMobile: 'Filtered out discoveryA,dvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:7013A18A-B3A3-429C-A561-7CE2E3F66643
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49909
[ThaliCore] Session.disconnect() peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "59CCC3C4-7D77-4AA0-85BA-EAC4EC5EC63C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:7929E7E1-BF18-4C3B-BBA4-750DED2DBA50
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D0F6381F-42C6-44BA-8B84-8E89DDF7C407
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB547500-D6DD-4A32-A817-B7DE4D95D5F8
[ThaliCore] Browser.startListening
,2017-07-13 09:30:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:30:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","generation":0}'
2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7013A18A-B3A3-429C-A561-7CE2E3F66643, (syncValue: 9U2jjnNpHEw0jl1Ec9TduTreEjG8GJfO)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:,sessionNotConnected:) Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0F6381F-42C6-44BA-8B84-8E89DDF7C407:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
2017-07-13 09:30:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,2017-07-13 09:30:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", genera,tion: 0)
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9U2jjnNpHEw0jl1Ec9TduTreEjG8GJfO","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '9U2jjnNpHEw0jl1Ec9TduTreEjG8GJfO', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 09:30:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59B86F41-C2BA-43DD-9AE3-8F3EAE11736F (syncValue: jKs8EZt,7PvJBvQaHBZVzR7iAVyWqTOlr)'
2017-07-13 09:30:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0)
[ThaliCore] Session.disconnect() peer:59B86F41-C2B,A-43DD-9AE3-8F3EAE11736F:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
2017-07-13 09:30:28 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7013A18A-B3A3-429C-A561-7CE2E3F66643","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:59B86F41-C2BA-43DD-9AE3-8F3EAE11736F:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "59B86F41-C2BA-43DD-9AE3-8F3EAE11736F", genera,tion: 0)
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jKs8EZt7PvJBvQaHBZVzR7iAVyWqTOlr","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'jKs8EZt7PvJBvQaHBZVzR7iAVyWqTOlr', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 09:30:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"59B86F41-C2BA-43DD-9AE3-8F3EAE11736F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 272EFB28-A62E-4CC9-815C-88B09C2FD833 (syncValue: fqgKbcc,NCbrGvB7jKc6OpLPmAqmRfEBf)'
2017-07-13 09:30:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD83,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] Advertiser: session connected Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7013A18A-B3A3-429C-A561-7CE2E3F66643:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7013A18A-B3A3-429C-A561-7CE2E3F66643", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] Session.startOutputStream(with:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] Session.startOutputStream(with:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [3, 4]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
,[ThaliCore] Session.startOutputStream(with:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (2403 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (1054 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 09:30:33 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server received all data: 2W4Nwf99B1kYR46yJ1LdtXmT4wnK69vN5l6gRCzhwF3FvWXsbuRkzApRNwk9jeQl5CE8FtIXN1twEos0HIKXDZ1JCemGxhIB77rAQzzuxST8ikGlzcjTqKwwFS4sxrf7wpf4BziC0qNrEzuhJZYNfVzpQ85W7uuy4btGp8TBTQ0WGyZnFU,IhKNoHfyYx4sq2p95wGZXoSsLJz142czCauTXTJ7a6rkIvT5JUGUXduJfp4AwGVfxbRChhz5i8IHenvXysx8NfsPvsldwEu78OrCjpuqRRSYpkRVuezP3YHk4jLEfHNNi66TUZkRzpgC9MC1Yg0JluigHGjbGszscEiEOIQCKJd5vUltAYxzK8hSe5b6EvMiJSrnl4HZ5NDarFsiFmpOIgzkmVe7LArMzBCCr4OTLIslGX4RJaehtU46HeT8ocNf,QiFwNvg2DvlbsxCYZ1g7S8obIxcd7wVdqTDvLD8bO0EUKwUCI55q7vqj9KaLxIMxZ48HPUqBgtuX4Yuotq9Z3Y8KRFD6uuvgLsUlsn8GdOePXG2D1tjd0Y8ZInUmM6k7srU85JPCnj93mwbhpuAyyHuugt3cbcbwOTBDZC6yVYcOU8uqD2yCivF9UiPvCQj9ihO3IIiZAjR8seIzn28eHH6NU3QvAZ3zQT5yI1Siv8FlB7il3KlQysWHqIPKdSkC,3GKvNiAzT99FMAbKm344JB3EMWCCv7OZNoyGacyjyDwoVGKx5xSnWIbF0QFIWthudLWOcc91BDJEzqcLkl22JPYSTI3imtb0dNjMEM3ZwNtfJjxUL4YrkLmP71jrezgdFUzl6QWXydgH4BUC62ASaXcSAea0ZezF1UdXDWYcln5dMbg7Qln8K8V9NAxPnURrAdlybGIaoQLekoOL1XwlIOR1xDI6nQr4k98pk6zjcKY7NdMMghYpMG9QBKBGpY6N,ejazyVC4GMwtFBn6OzhXJkTcxgIUkqsshHSbWbZQcCcHK4rof90um1ivuk7Zpb5D6JVK0KhBcFSH4K4QuL3apA0KK3qDuKNdSfcALvH4zqGCZeORLFuupSCunr42XJtbaGbU50CavYXCq0dTytt6tSpXkS9oT6z85JSfxX0i9uQwdjH91m0OqCUuFANVU3za99iMeAUWAFVZ6LNBm9xBT0UUosyzVUPqIBsdarQSE5ULpdoGMT2MHWa0NMuoykmh,5WIjUG3JiQMs6bW7QKK3uSGidjV3FgixGNaZXeq5U21AATAsUsZR6aDg0wz6JfcgF7iW1fJHCCaJjp3vrWZlEiHcGPtarrr6Me4yiuZPDL3M25HM2XsHWTIvRdV3HLyCBiFagj1DpadR2x90swpQkMZIhdmfuTj5WvFEYPLClHlHuBVbTzKPklRR8w0fsiITfGHa0tHAmjkFOznoJCaFuORV1wi2lrTHkGeMTtuXeaLqnYtx0UQpz3r13stW8H23,W0zW7YDWcOgxFzVcBUecUWdu139mF0DCT6DlKyPkxCvV0t03edepcIrYMEZK7fGRjAaD0zL7WcflqwHoQB7bF1WwPhxusJxbjlvannD28K07Nl4Lhz3j7Gwyh2dTPBjlG6jjoGitMbylpRa4BlmLGX30E3UcfBh6qkRmmkZC22ndcCXUmmYBt9YsAEsAztHuDttJTRsCciR0x7Hf4pgZVXsfmTffE7mRfbiphligyV17aC51xrsteu29iYTEZQ3W,0lu03MFPGhoQbII0bsbvN3miWn9DOe0INm7XjKNDTprFifA2kuLshGTeZs3sq1dgfWAmVSwKYeaAWs7nMdoQB0nWNHIZTnhCSUfKbKjgVNGEay1jDavqFYFPDMBsss3tOOF5SkTqUSEg0Wcp1xVl1RnibH7miF80V0aJuPRLCtPNFqQ8zWucvRQU9kOunKzZGRkDO6tzaSTo85Gc2Q5f5zGGzW6L3bmebupYZbZ2vtjD9TXyEri0Ss0FgwD3xeja,DnOZTP3rnR6qxDkqhFCsdibIO4z7029PoMWByKDWLieblJ82IBlZ8dxJwYizroSFh1sYlg9WjrxwCZJMDgCvwISBCjNgr3G8VDHI5bLUHBaHyBb3Nx7ELsoh1G2RoFlxOnprKvi8nfhlP3LeQxNaxzGk4bjyMh6fuxQ5WOj4S5i6boJM5dKqLrrFPBEE9QK1yjaAvsjyRXz6axNeaDZa8wdKbUbQedd7vWEWpeyKroSUy3L5cH6br8VHRLPnmxl0,NIpcQqRAFEJC4ZHFkvniBQCgPUyYDebfCLbYgSZsf95s1njwyTiL8hKwM8ZFjC4JKpzURjgtzI67GoqccSO4d7Rf74WEVHDOw5wxQLpRSaQEhWLxHM7qI4NsTBWqSMWgBiC2pH4sSjkT0pENpnjDZ8bxY18sjtAUZcDSsz2bfeYYwpwooOOtCqROyhjUA4YrpqIheC3hl2dBuLv6Fqp9J0enywhQwIiu8TpZIcvjOfkqm63u7qBKZ8fgzqPgtWu0,6dlGaLmqacexrlBbZGAqU0CIOnkrhhaebHpDVteFrmGv57nAhtCegwpbEoMnsUIXxF1UawbgRw8XcRT5tsuupMUgsXMnnk0LQX3oBbAcC11UU361JqNWoyWFPsmiKucQGOrulUyVueIuocnk3T7gmjLYEeVbE0x1jWavwezqnbwrS4rljWXL67WDigdqbwDQFqwhBD6v8VsRluJvgSqN4IWPL5TN6aMIRYbPtyJV6HXhBnn106tDTkl1CifaPPGn,gSwGrwN76GSfc89aDFQibk8NjaqkAbAVQ25pCND75SHl7QTvckMJH6U1yXvxRiTcTiSxmBcjkLA1T8llWzhegqdPeJE93GjUGxXOvdnGFaRdXyq9SlKqEWmWso6zeBcbfB2Puq1mEowVnV9fgb6CkwyHAMQ4rQd0YkgWKqnVeostapYuYWKwQbiwUYTeZcZG2YBpHEVnRtQkocAhe3o3AAzfnLiCVNJKfVYVLbwnUVoHrFeE8NN7A6W39HWbetde,TsichOqDOsUHDMU7lN2WnzA7ye4ZNdoTExua4XfnDYig15wOzIUhkZOn5xx8B9mO4K5b4QGocjPZkuLdXJjrw15MuGWSSGkK9Dsfvz9bEGbo4JJbZSuSmCeQbATWmuvId3ki793Nf2EaxJS4lmzfH6hz5MXu6gGLXMJhWOcA4OI1mECu9KYaTgKQdDIciiCOQQANPm4OVPFmzWePlgkGMeW6d7bs0Nfpcqap4dnwRk9YXLoSRGfQ9jMHWeWp9YF7,pLxd0L2yQCvkbVhK3KMMydsJn7R8v3f6Tx8epzp9aAuRITgDvWTv69NiNsjrTkcpgZreGxOmDGA7jhKwwh6xVfgGKL4CEhi6HvNPW2DqR2TJNNuUPxmi6irLaUaaBheaDd1EURpwdStkUYp83F2WFBdZnZ4UIHp8FuOH2EKaKcfiNEfhcerXNAhjPJ7b7VVNvW2UpOMb8kk5dhV8grfiZwsNHCXcYrAPmYm9HaTivKJvgLnDLs2LopisuhJLmUF0,KOsGWENHdss3KpkTRxBKWWjnRDPlj1dKhD8wtUr7xfDkfcu9gCow0NBi7sexZj64YymuzPEyJ6bx08Rl0Bl10oVhrebYKtNSuNylgSxcVloIseQNtPCsiOn72N4PmCPo3f5lIgfM7jYsJFSVbBZQHHUu4vUoU17PomTVJ68DQgCpn8aSSSWjSOpvUMmcrlHrn2GCrmD9tuhdRpUfyP9aHXjuTEFls7DVxLbIjYzQGBjlObecbCUmx3kW19KYX3xR,pov7vFuuFV4PPVhxlEaixwj9EVJ1FmJB0fYVqYv3iZcODPS0jK5jCXCguTOCsJaVeyDybnskoyeYioCZfogd3t4WLOmGWeMRv5BddFkC0MJabrsUwAiYkPVsV1RmphOgR95CNT8lNsliiLMjvHXX7wVeVrWFbDS94WLSEbHjBTUzvVZMaVSh73BPFmwsuGxwrwlVNVRV0238ogjGsjSYy5YQVR3cECTOcpKMkhkBVX0XDaPDcObK6m6mT9uqUcQK,4LLNoAgfUig26dxjJvuZrHU4WgeTXlxBmVR8WRXC35LmMyhE1hkbO8j2CqrM7supilNhqsgxrmF4GUP8bihrhYN1hlKNWq45Jj9Z5VIg3fcmPAxdzmD4Zc2Y2V5GMWtUqdSO11EVSE45wziXFvwmBd8y4Tw0XREtvc1hgkrVMcV2lxdZaxYdzwdXK51zWgQXg9QL204m8c5C5ohBwROvu3hC9EeRRxkkiTDd8thrDCmFNepewYztXjNfHjGf4qzI,NRL9rBKlvfvY9qr32HTbNAjyBaualUGplRjSj52QMdS9MGkr0s0UDyQKS0wS35HVkIBWhpRoVv9NBd5NcJmHmLCPMMOyaKOhEhz0TN6u3jssE6foK1ifbHo9tcGEuq3La3MJlZBubyKF2E7WCcTldUgBGggDMif8xAAiAqDNSIyO4QwjjdSddf5UUVIiyehmFaAb0OkbaHlR7zrdteKy7AnJhHW4fWdOQxrMt3vOgzvhglGA8s99UHiHsDYZAvkR,k1nV84Hwwc60p9VtDW5kttXIYybrq1ubRSC42wh7QewjIQopLi4YBnEX2MAjpSCfrxVWeNPL6LAJa0jj5vVyFcpvD8EawjOVeIFhHfn0g8hCfCYSm6Gi0FlzfmrS6tMPPYA0vaJ1vcHvrkxhx5hUvhHFSSKkFARWUMFwgvqgkg3QU6qX7Kny6Zy3OscioNYf5KCrkP9XHCBurEHkfhfi33zI22MePjV7X1gltEicQ8OzI5Uu9J36inPjJ7RV5vZt,71CjVvYSL4Db6n7FG2o8nTFv5g57wS4C8EBSjAF6rHEF2WECZH3e3FOqEV8wxyWBWy4pvLNvEONN7aSEfqbI11D8faCsaUUjkCWaXuwv1wqXe7qnZnsZ1R1vp1Tphbo9TVsxPFnjTe0BygGRHFl1JK0Yi2af49ZOjZBY5dMJWyquKCkDd2yU6I0k2qASYNlDvFDqkoP6ywZz2HyXShmcki7G5cSNSDBBqw0H4Bg2BzE2VVWWXIoZqD1i4JfS3cHJ,X7CnvnQpTfW8dzO2EMCuOtufT7P1TNfQmMyX3b6tcyaOoLK0exBzy6YDvOJg0JLrJN3UHsqG1t2ZPiEtkFg3WeRQleDJPkjPlM9rjcZRe1fC2mNg9sdS7K8NU58ynVuDlLbrb0wDhew1u9kb7F5R6eSHtNF2F0yTDooQMS0jTOeAa2eAkxzFz8FJPYNUuYLyU1v6qGzvrbFoHJP8yYY0Wf9pylaAzYnB3tShi2WMcaS0eUo69cfUmPf0SDp43HpM,p7mhyTaxfyKXSP64Wt4YamtLlkJEoF8Fj58Q44EDxISQkNUAFp3bbNuzuGw8ROQlMscSeCRHvyfgEsZgsUR1kDENIcs7Ir0DJoJYlrbWocgQXIoqI1AR7sMzglS1LzbYacAzCTQMgzFRKKz4i8q3mNU1U7PurqWTIvHa88eESw9HOzcdLk5A3wzYXL8RIXJs6eLMrm0QwVTA8zo9b9KnvU7mDd8wDzpMVyoR8fZfJeuUkwAK9Hf3iES9kvvaOi5n,dcDp5Yq7K0A2GqL0Reyh2blXbCOvtlR7M0GRs2VBM44YUjYZkutVzKgbYcC7AyIfvl4IDFQCnfCLg2ubn9VIbHsbDAykodpakmhim3An1wOYBC9prVTMZPg1kLKc9grEOl7Pk7sP3Ftw7xyCNo5VMH5LK3bKZBy0tUsRyaHLd7fGOOzSvuKytQU5q5ATJj1AJ6vcD98ejjYt0tQNpZmNuk37uvThku3Sllwm8SvtiltYICQ1BgiGyjNIoJjZWodT,UBfdGiJyQ646EgU2hOozonFenoeHRTjikJG3EYpqewKdCCOOISN5a6beId7f6KCjicgTP9pf4EPzandeqoIXdC5ysZBzN6gKxQPTHvh1wuWVP3Ba03adTCq2sZYuXPLlsDCvjX8dsdroyeB0Sl3uHwed7X0Ry1ODSRTgnxHpePjCZMCLP31f1zKcnHpgGwJCR5EEeeHhpqodrtBMBm1ae6TF71RaovnYabTy7GccNKBXzWijdHk6gWsRwxWyrXL0,d70NkkAE9XUuXyZdmGuF4HqFJRNRah1VVFifDFaaz7uVjUZuMSmfyQfDXLs7zOAtWOAn57m8pFW5YrTjkrEBhumcM6fqxFAXn8wUgYZfOeRF0sT4XetEWGSqFkRnZpNzbK8R1aSszlzIF1N1mIPumYtmyyM9JTbB0aIsboxi2E1DKj02apjO5BRyQ2a3s13DTa6NHZk7X3WSoaEDYJMNA3z2bEm6jWslGRakyRimu3EWt5jNPmkkiMLR2Y21hkGm,40jQWvHCaM0wJfYjwtH0nnCQ6cUMHV9Td9a0doN80yVXBWbbpqxtYR8rn0PhrJ8UWW85D3MpjtLvhtZMiodMSl5xEo6Is7ECMyNsIJM7PdZEViWDRYweOMKYK7XUcmCqKJYQg4e2CY43kuXUSYDUL7IKpFU3KuiU2VfMvWA9XQcOaVu76CAVcLyJZoxK1RfZ2Uo6eGSecVLA6gRj1BAYPnJU5DUsdnwjabR8zXZoCNNEaGfW8JcVTuDPI8eEGz3B,OZjM2GeYFDoftW73SWNPPODre4jIphZrSxOHJzaTK0YkBoaMgDFXRJxbtNS59pPPq0jG3JZ6oQOPwfdwkTdwNMF5o6x3Y12u2Uw2VqdhreHGOEAPplmjyE61dlS5lwtHvEAH8Oi1MlqUbsjS4TIXgGtwCnXVB4esC0NIIAri3cmvJ8j4djv53sGBx4f9bI7sPQu3HKJSr0IETryFJIY9w555kMJ4Wk6JKWFma8gjiYuPF7e6ysSyZ9B7h0ahcSg3,QyxSp8scNbokEDehIRbucJ5qQFsT0NfD4aYuwt3LaMG531bPWGME8ihl3ENlYpVWp701OhYplnv5ieVrAlL9DkXPzmyOkUTJtt2CJR6PfZ9A1YiwDs8hs2sgTHiZLESAvAR1FwJSWc0YNZgx5VRv0gCOZQ7SXlWd1yWuS2NXXA9Go2asZN89Lzc5hUozhHgxYVppiOqlQ8AD1kXt09ohW6eTz67kBOoXy02T2k23q4cig5WCyYzmZomVpmXHw5tn,pNpxaTUlRTLzsyVgoerqlGxPAEFDnvsHEqJjYgGXY9zYGbgGcAsjJ5R39clzcKph3CgZqbKVxtBxoPMQYVORzwIjaJcpyNVxnhQZ6jL7zxQHe3fcmFxhXRISlLhhuMLOu0lnzm0wPfOYmDKibVqBFVwr8KrXT484wFidsSxb40g4gU4cjcwWaFFMp1BAEF6IxyrYhHSK0yDpL7cMJ65P06sAmXfE00sgCuwhgIEtfq33kn48RaJD50qu8GxihV04,1VcgMoTN0oiuvlsuG2WIfl1TpwXEXAeE6cgpQAj79fdALXHeEYBDvLqSeXPBTk7SqEVfRYkrv3Hl0ZH2UXTlxNKPrfhLA9VpQfvLiEnYWH8AOKh26ZfedR0Rwfaa0nulvUbiZCX9MXEsqnCfFqudunHrPrnjWCu2KERjhKMHCGjbZnU9W3KEHCRewbHnrD2nP14PljoGmNNFogdvULrw25C5NZ4as6pdRswmUH1a7Nl4kz2KJYAE2vVNVzTG0GKM,7b81CQHR81D2aB8rWULdIQ0lSO7nmpMcJgjj3gCNth9lHd0zAsyj6t9KDU5AofR1ae8wQBqCT5JxYpdKs2paPIY4rhnFud15sFnYQbWMUbWZdZrT4hFwDPNXwRPz1WJr6nZLuDtQ5srkAEJPd7e7LYjvNN3tNsjoFLcn5ioyUUgSaQE8VlPaTyvxHsKh16i7br3dseGGhzj6wo9OLOtAiI4BQcVMklLUA8SV4vlh3dn1ohaJ86wKRUPFFSFPRUFR,OLB3Xyf3nHmFFsW2FKwf5E8hoP2U4eyAVtQxEdjZzjc5SrCdw7U13trEtn7y4vpfnqQd3leHsS3YEIaY44TQJDt14j8EPJW8nxXqY04QTsaQpxs2URhsnA7w8ZdnNVTo2rbfJg96Aox1v9QsF57mlez0k0VwH6xkQ58f1CoNG3OKmbNMXxk0d9VuXleeMrmUj9pqkG2dNhNTz6U6ffqnr5dQqHqAJAph5zauXsPYn1Cxzk5ndODdFRBY151IEgz1,9sdfWSFDdhRlR3QLxRTzX5xzWzSlalk3KQUiLhMHvNvdczQaEdkX1Iu2bFULJiptMYxeM39rYXJRZPEi3FYStzD4yLp0SZav3K3lPMW3QNuA6OO70HNJs0FUvntEcbT6zhtHlicf4tgkiEPQYEG8wwWn3W4g9jjg7FbS7FlW4VQ5pvQTUmLPRZO9NcxkpkZZsfSwoLjKkJInJuEQd2No9vromqfTmCVOk5PmmiAgHr3z2ib8ntzy4gfVgkpMLyCj,PY5AubyBoK3cp8J6VDaRCUPm8F71V7cMDHlgB66paFv0pEjxUA7s3FOB0FUvBnbJ0ohKunY6OKe6skcpjEC7vFLe01kSorhO5R5W6f29nxvyVRh564Mb8wkeWCDvo84N7Dzkm4oC1Tc6UcEbFeMiOQZjRxv9iVfNQvOohXoO2y3TlkhdGIstjcfgNPBqHe13syTipVwbkicYVWLSY1cWh53wjWUTuYahBt77jXfRiFqAp7y6srOdLjAcsPgChQmE,Am35aRkAwDpRXFGJViVwbXf6KXeoUWbOv9BVkftLquyGeM2p1SgPV2suKzS0XUv7HBAgF0P2Cj959EdyxVKSbb2bqBCMWdUC9BvWnwkM3lPF6oeMVbOMWZqfuhnIKlCszqZdsbDcYF2kUZfV8il0e8D1JXm0WXG3MxoEvCamGc6IWiIVsV7CxyX5HkLrbWKOYNqdUtg82kPDxMl5kefTlJVtULDPKrym0lyeOLwloLOxLruHzkP156BJ9Eufac0n,N7bKpjCXkgua055YF0cdUU3LqwsZId5hdnOrBvlkmYpvuteL0pWWNXNPsDHxWc7bK713IzDjNrF74ENVlsMEIFT6ifUp9bd5O8pJ6EmWJbbkH7GIAqNr12aHC1dP6MLqlRO5sXSQDw7v57G7esBT3sp6tMwmccuFqE3ZkLyUae6eZe7SQmyCuOwE20rDRTmGxsac9bMGTLGjgH0yGztobFIktUoaCK1N6YjjZZ1ZmMCqJ3lx5sBLgznt1Fw6hfEX,5LpEQPP7lG8RG5GsVxOP73w3nAjveWBU7BzKrFZw9dcGVHTDYU7B70QvTgWyVZjztZVGbERCEiFfvfuMEVFiVET8266O0F0V4fHngxHVjTXG3ZicClONhHxEsUPEyDIVdHE1sCEjt1hKcHMVo3spxnSX9rcpJ3TfKg65N0DwokNWlP42ejttVCXR0JEMC5kuHk4tlBr9DOWxpmSShiLm7zZTySSFQrcDRGFeol2inhlwNGPL2AnitHNTANypvwhS,JgIV5e5ZJuutXvkThgPSOJkM0oBog8mTJKs78WsriY2VxH1IfjXcyclkaEAxcrnFmlHNO1yPOkg03KauFRn2PTQVakSKuReiRt2DHOm9qC1hlMMuC9CktmtZOD1CR9ll3eobTN1EP9Q7ety4mTwVZQ2LLEBWqO7epL7Ka2pbVyEf1rMdQyMejVR3BKpR2yZJf2Cl3nJiAuj5OBA2bLL5HFL5Sn6lJsthoa9H5XbMLdKN8XQZwDSSCDqRYyJITksw,19akdtnLvgIW0DCtIbQ4PcbFRdZ1mezdk3cJDRzTB8HPoxz0W3EuekO6eS71byzJllG8upCTeMs0udAjBI55lNhfERWv3AegeM8CrZzGMYhqoN1wwkaOxnMQAder8K7WHrdeX9dytnfMf9yqvpM41EFD9hzT8fafaoykkl7dMi1J5SGOvf7rrGn7XLyBd7l95iuT2iUv471aOGRhAw7yOwOk2u0k7Re5VwZt5v57rdoGT340fUK8OqiDRGLkFPL0,0VLrSBX1bmohy55zvHw5Jf3M4mjy7VTHT974aG9ITeiJkeCezOd3cY3P27FTgDZWbut6TFZ07tRuvZF70gkwkUVnOjz4pP7XL56wcELDMt9hz2MSCpuDc67gmehLRBwGkgowhxDWY47Y3qx99b4Ls15MuAvM26IQ4vsZfqhFk4R0ASN5A0kkk0VaDGoVpPHV91cdUCeTiO93g668QfmgpcUZWWdaQ9CSjVf1p2mkiF76HACICq9ihPQxA86Cly8x,mnxiryqQtyJouDZx33wPioCCo4rhLWHyKHYRyTTyj0zGRJ05gRa1nWnCxfFchXtMuVgCE3oMTThWD6LnmTncVzQLNCU4gNOZYQYIrdQ34e48jMR3fH4uFesLRfjyMHB9blP8aY26uVWkmWsJbtpShDUd88HYUuMqb9daYClG5i0Hbe8Wlfdk9yyFLbct1lqHjjJw6CdE8tRpIZTzKGcL1eOJHp9CnUYRsTUTZqHPp5el6ts0bR8fvgjg78gs7Qp3,8bvS5lsfBvIzOqdlUB1a2Mj1SWbHDDWfumU8eabYcIcw71oAHP9TTQiPxDY19m2gyBPoCE6mmf9j27LEbzVRoS9VQLzDFZzI68ziiueP8px8941pQp1H3rNXWshL3h0juVzVDdPSnLeOz1KNfrIUdFOMp6f5djiiNx6xDY8DTiGgYsWqxqFp5sheo1fWgxVyAC6ICGssgwukFdGy9ZD4K9arM8U93rLA9z8IedVtjpyNkwo4PpHjApvkxikRUaSj,9KSX8afg2XbfDmNsbvIIdpKdAzQLgTqHfMsBra04iJ7P31pjDGl38WxjIcn6IDmDhybO7XFZvVdTNIDkMKy7b7L5kYHwq2F2JaZMAz8cb9EUTcUhRNrckBZ6vyQ7HvbxL34xNd4TBdCh9qNucsCXQZ3rbr8IatkY0CfExbCK94d3us6L0Eglvt5K5TXGb1ciqmjrROa1QdK126BWdpjZpbwIjEPeExBUGxY8WWy3NbrgHeMtflfJsct6gFeJo6aB,va44loVT0KyIvwsZ888HiyQ0JlJuCzhlnPEDYp7gc9o6fe9F0LDB8LyMw40zzphfkqkN5mC1KsRf08GeXDjeqzdDv6ENQANJuOhPWiR9RZbBDTc8sMstIfjMoa1eu7jvyMChO2WhV0IMuuuqNGk8CV4BXj4nyd64MXob5UiKth2G3NwBNyN9bBlkjLY8EqgEHVo9ptaPg4c2nAZ13XYE6Llypnzp7qMIpWMpDMoaEBHWHR5qYLPDdt8bSUk9jMVh,6HxKRuVglY1utov4aXTIlS79r8hKq058OGsWUtxU1yCg4DU99QOLNzYRRYFpRY8sKWHzJhp928AKge95w6DBr7ULXYG85RGSykt6vTCmLgR3zqVYSSkHJjsRlCsC0YG7hxG15WudH9ou2Xo1oXeUgb4R95nVXWdqDlfghZ6994k4za3c96uBdCpo7Ojckt72a3eE8YUylIhzrvHd3WrEycE57hL3CDhdjLqDREAzBgk7LPqqkrmbLLhbMvn6IPkL,fio8QG01vvBuMZEBkp71S3P9QUZV4Hs7mS2AE4gce8u7ftsf5Rgp7F5tbrH5pzz84eg7XCwy7Axw3jTMMbePI1jQ4IpiL4ghe9GNRK6IjUsm3wjoBcdFqKH2tABoiCZLpFsxuE5nwj2EE6LBTh9De124RyhWqbqNDRP9LOT4sYJaVOUYXO382YGKpXAyxoIRpAe0VX9GrfWAWLcmA2CwhSC0THeINqZJNbzEvMhrLNkuG56emSS7cWROfTAt7p1s,gQxGomQeulsHLDcLUl2wPKFLbEGzYk7t9pBtONF10RlbSaY4wN7zPHRXmw1JvtIRguZQuB26AmEFXIgqrBXEoh9Zt9oqESKK5AmE1OsSTonIapuDiNUrPU2QVqRUOb87DS8mON6G8gCZNd6wkrcqIDYHu7FqDPoSBhGCh87UcIlAVQaUvk2lWSEKuCj3cfMO8y9eHmRJqhOsoqkDYRlsbetNHUCfJcpgF38i3a5pwXcrThRKXg4n4YNoDhpDWAKJ,hW9Z1WOEYGjsAsJzLw95G5lHPNdheO77lPrzCPrDjwxnZeno4m6FxsMaGR1h97T6Xu9CRJjFfjcbofGhRlnt7mrZJO27EsTzt9otLoIkiINaESWJgDc9HUcxfvIFJN0YUOIcys87dIX5kYPhpLz9DYwe4rOhNZ8FTpxfN4zRvN0SvE70xDjxc6JlMiPzxoJgW1JhiQi1OYEMZgAPg0fFwhYbo7IbKR14w338acTGLc2HrvK5ru5V9QvwQ48EX9fI,56qdWpnb3GrX3rkHP6xDiSPZoQQ9d6omVKKtZzEW9QAms9GDbvxX3DLOy7Lzj2dETOzrTRhtzsTNl9DoxhCDdWJDh6AafpxKDyTXIaAuMp5cY0yYh2LyL7qgbpSKXa1nrXwfwARqeXGJWQsACzrDXpu7bqOukCN13DnF176pgUJagLLzSFXCHofUw6UZ0Fj0n78wN00KzhgZYiMsJCKsIC9edd5fKDKsOuOv3KAb5PICxaZ3n1p3FDzWHhRLEL3H,uwyYFT7R6pO6hHxPO6PlcAVvv2ORmZdQDEYAulExU5IwirZcIkHKJxOanl421XmLHsj9FxzZD1xTxDWmMSDSxUocYuqxHKPqzUGQ4VHUCUwUtsVVqhfugMRrroi2Jg3nzaSaBvunA0FyLxDgJpUJNJiGQCoI70Vh7o3hDDtaf14a3HT3pgzYL7koCJ7WhORM96E8pfjVUB10dgHNvR2n34qTXaQppx4PgrQZnMUtPZZJMYo6lorPSW5RnXK2wbz2,7405tPZHRycUeaWGsTqbBE8zuMp6aJJNa36QB4G5dj8auO4Oub1VM536R6EISIsYnii7f0KRND1jZkcjt3Um0d55lXmsL1cnZuSrmfHdrbrMvqGMKxWOvosxdzEX0l82DCp3YTVOdtK8ikFaHO7r5kxypUraFyCpVXW45HSVllvthEzK11YXDIkn2gTdSMMzE6iL0KhXh9I4lzFq1TGLOLd7CzIS34Ms3ANjloFy6xKLlM0fHuoVCXB3on2riks8,N9NMpvL7lXSw1nBLJ3z0OBOAyfVTDNoNZyOGkMKyQkWtGVr87nGiSKBnqO9YtzYmqLW3RHZMmqnjKKAhqwwer7OWksUA7oZ5czuAHddiduDFtywjPJOnWN267IAW9VpeWxKJxxpegY6psM2Z3JvpUKcAL8B5IHECAhBx0VIBme4ZolP4XNqdAcXRuEm7njHwuAeaqak1ubOpqq3leHstBNS403ktjtKc8OjciaRV5SSEcuZidwpEbXJxIqjd2mEv,gUg5KhtpJLKaEkQzPS7GCiRRzLZz5SFMvRjvWcKtWd1JmYCgM4UXClo9lP5qmZQI0EKuuX31rh2LQZX87BK7awxRLcGMjxof906KShUxZMUmn7DUIglqVmpJMj48Yltn7Djt3fOQTPRhDxxmKgGh5ywTJOVgKtCqpmAjLrcyYDAFYRpl9qRonaaxcNQQvgFN6ldPb6UKj5Sg7rjxAvoYNh4ahHKXGVKAaxfANS87UtKGxFD41HPms61wNtxz0iUc,NjZiMMbp6gFovWxOpH30lTSufcGyRCqojdeCkNr7tw02uLvgGHfjdHo7Lj8tvdRa9XccBZhW1SYQipgMtTekMTOOfgLz6B30krWWCWOxLqKXCo3EQplowSxIKuX9hNK8t4dGNyx2P2JJz2Uggt73N29dS6pwCDxtaxZozXtX4VpljIXGYgbqwyuKJmTGExYox5GNe56vnnPgtBjMdzzvLMZPzBwitkiaJfuxvil0PYEWCqaogk5Z9AjHi61cFDbV,ZIGKGFdXoYCX1tWid4Ti2Df9DFVNes2EfwAbg0Np64rai2OMu40eEfdV5dFfRwJkyzYB7ONAaynRcRVWSNoKt4t1pLR7y0R6TsyUWZHzlyW5pKJSMlWYIni76PxKhPJd8BYYbdWi7exRlCjdKuRW03QTsNkPBH7ROaC16AMeIr5tHGasnhnoDJwzJnN1ytfxw5aRGlFPGX2cPKUYsgK43fI9t2fLoP6ZZFd68qv06lAx7I4h272TKGzQgZhTFh6d,yVtNMTeUhAqoYPcPGvI6deaSpMfPeFDqP9g7wInwHAp4GcQhFUeNkWAYCUeewFC4p9Bwl3rfHE6Qy1n0V9WgUALFPPzI0tHAp1Xv3mcvV0jS2Nd9xltWd7IS6Ca7kA48uL4cnO1bIhrV4RP8KOxCQ3kaNwK3LlvTjk7um6Ix9mLSBH0TNW1ExXs3nvklVOQ4UWrPVu7XEdrRcxIpiSmMNEAtTjjD0s3IA9qzLC7si5vU7HF3Kb3oH2ewSl2sJHvr,NtOMSQIkjXnEcVLhF8InG76ZlAvGSxUCWJWXQQWTf4mJlsVmjfeGNei1BIg7Q4Gxg551ypLA68ZXM8KW1N9tsCeTZG7B2BHjZAmwNYX4eamsHFhceyqOgAFm1qKwPPmu4m06p2sWE5APuZfRsPLz5IyGEaGmiR7ffebdSAYcZkAv8Tcrb6KVGcZi6TrFqTDKmuJUI4SwbOtnDsuKfeBNXhJY5fRnIHYL1auLZ49DdxDag0NE8sS6XDNg4mqVdV5e,56EQypa0etRb5Nf6kVKw4VUyeH5i5onki3fmMft3nRfdXUdCg29xWKxn5BURZM1SDE1s3NK711fJJ0ofiqy1Yy1fgqN0R6lYxXsnkOQRTumNMI6OPMpfvr632kPs3zq1kviOGyyZdQ8wgQR2pHrmRsfJRoYlIk8dvwXa3nL9k5br8MxskEyzXc2XhMT0VBYIqBuRaNYaJuRmYtcupHMtAmiLx0muPPHVIaHwXAhgt0YDkot3JdvEsKFIsvVLbJGo,r4mdwRM4sVtx5kMnNiKxmr1xqvP27AqqdQ6N8rg3lTBsuOWzzwl6jUMF6EQxfWs1ovNEQkm3JTOF8vLbOZakxmvaaAQZT6zBpLQfJX7HxCYcobX0tPDRFonD4lzelw0ZHDhb4tmRJlGx3rzpZIdIipQMZGdzRwpCn0WDRR6DsL3MdzYUbSkiAvl9oV8Q0C3GgRuOz2umWBGRqjYS8L5SPzQiXjwHOVZVvev2tmgQkz6DID4eHMsBDMbfXeD9mneX,nFbm4171siJwZYP84g1Jrt2bxFZbdRGEdG4YPEoHUK3L4nZ7skJs0jZiitORtREIZ5mnAFvD8djTHQ0GF9SA249I1RSlFUlhrfMGvG36HOaRWi2qkoM2KTUiQnF8GcakDsrNiItqQX6dq3fzMysnhwtu18r2pzm0ptxIVRi4AwTJCUIJ2FON0c9qBXbZSQ6k8nXGMtyc1yUWKXRPz32qGMsaPXHE9FRPN8MyciHbClDb1pslltjQyZiBlsRUYNWo,XfQtI3lY6wtKpHj6N9s9IwyuURExYQvtIUbrYv24JKEATGFXX3Q1w0nti9tbGWjc1aIOuKAy0KlZs28xTAmpbOkKy5yTb8suBgIKbpyOkRe0UZHwO1AYUtBDu6oxU3qHNezJvEWMbb2q9FjYbtQciL9RzTzWBCCJWgzPvjslYVdHtoa0D3iwKHRFTFZRsS29vUG7Cg9rgvGBMX1MQosPUnWvDK4mHjMucVNoqrfgHVZpZFGAXMegYhTNKoEo9WDE,WKutcx3WnnI0ubQV0kanUVkMMz8L5cM6tCPXmPzOzjFtDfA1xwDDjORpBT80MbriGniooFxTSUV8xtWITwM4Zft4E3sVIUVV7DqXcnWuKKYZMHU5ueHNhWG0uJykOpqCglYlWg8K6VDzKcCsUHVGpkSd74e9VfJWVWo5MA7mgYL6rlgdjxKWCpMEUEzIjfh06Zgd4jKb5vAPMyoTLyoKy3qUdzeV946lOpIfOMQDACY1MMhfQgN7XdmLT17w88HL,fT5q9Tci0x261YEPm0FLavTlTSNJ9LW2S6EQB6ftIYYIGwnXqH9Hssxwn1mMb2uxRooX7ceMNR0RqCN5Yyb6rEP2cgCpBPOT3gw3AIiKVK2FpNk1JNPaHjEFkxcd63JCo9VWyX9oPMhtl96NEQ9Z8YeE1qsafrWIQsyd36lnP36jSvKedqApMcUlNmTMEMOKcpJDgoUBQbqRWcP85OHLFyI9bEAvNTD0nEUgUEdXMnxynM7g1RbCmB4aG1n8XM2S,8TMagzmN76wQOB1LbUb4TdOZlrzF1rj8RS84gRdwgGq0onTPj6eYlDvjQTLizYCbxA5Mu3JzVGQZ3KSWJYPsGLFhHd088bw9vx3UUYWygUgi8cgrcNSHlGHyvb1wBbBVDJBAQiWOwg9QToirvniKSrPRx1acBauTGjUlLhE31fj6YxzcOc0I5eENcFwFHLGFi4sToKXKADrSP5s309iPGpibhQJbqhsUCkDSuiADhEgE7VQ6tHoPxPCanl4qFx35,aathH4xDCjxiK5pxpV437rV6aStwdpqBC76wdg810lY0UfFtG1i4z8otbvvCnyPHcjeZIv74L5zoqM'
2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3,
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4,
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client ,disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit, vsID:4 [5]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49922
,2017-07-13 09:30:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fqgKbccNCbrGvB7jKc6OpLPmAqmRfEBf","error":null,"portNumber":49922}'
,2017-07-13 09:30:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fqgKbccNCbrGvB7jKc6OpLPmAqmRfEBf', error: 'null', listeningPort: '49922''
,Connecting to the localhost:49922
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,Connecting to the localhost:49922
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connecting to the localhost:49922
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49922
,Connected to the localhost:49922
,Connected to the localhost:49922
,ok 109 correct string length
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 09:30:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [7, 8]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [8]
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 []
,ok 114 got the same data back
,# teardown
,2017-07-13 09:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:272EFB28-A62E-4CC9-815C-88B09C2FD833
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49922
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D0F6381F-42C6-44BA-8B84-8E89DDF7C407", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:92B682DE-349B-46C9-BB1A-888EBD15DE3E
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D575FBD-A1CF-40A0-9E58-14B0DBE2BFB4
,[ThaliCore] Browser.startListening
,2017-07-13 09:30:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:30:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","generation":0}'
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 272EFB28-A62E-4CC9-815C-88B09C2FD833 (syncValue: FtOMj7VAG5Fr9kdXDhgbkvc3d6lIPKXS)'
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,2017-07-13 09:30:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750CF6A3-B1D5-4221-85F0-7689E1747463","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6EE6A5F0-6678-4C9A-9DD4-9B3793A3C96C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
[ThaliCore] Advertiser: session connected Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FtOMj7VAG5Fr9kdXDhgbkvc3d6lIPKXS","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'FtOMj7VAG5Fr9kdXDhgbkvc3d6lIPKXS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"272EFB28-A62E-4CC9-815C-88B09C2FD833","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF (syncValue: 3l6hAHDTDUcPy1xwGxujbFK9NbKqbo7e)'
,2017-07-13 09:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:272EFB28-A62E-4CC9-815C-88B09C2FD833:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "272EFB28-A62E-4CC9-815C-88B09C2FD833", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49933
,2017-07-13 09:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3l6hAHDTDUcPy1xwGxujbFK9NbKqbo7e","error":null,"portNumber":49933}'
,2017-07-13 09:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3l6hAHDTDUcPy1xwGxujbFK9NbKqbo7e', error: 'null', listeningPort: '49933''
,Connecting to the localhost:49933
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49933
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 09:30:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
[ThaliCore] Session.startOutputStream(with:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 09:30:45 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [9]
,2017-07-13 09:30:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:30:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,Active":false}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49933
[ThaliCore] Session.disconnect,() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: connected -> notConnecte,d
[ThaliCore] Browser: session notConnected Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,# setup
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9B1DC9E3-5BFB-4FBE-B3BF-AFFAE68E22DF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
,# Can shift large amounts of data
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:0702D045-C6DF-4C6A-B432-D753E9FDDA6D
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C0B6584A-55E2-4F22-9640-4ABB1B359C49
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EAB89FC5-0627-4530-990D-9A9AF144B905
,[ThaliCore] Browser.startListening
,2017-07-13 09:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
2017-07-13 09:30:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","generation":0}'
2017-07-13 09:30:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C25A8FB-5F40-47C6-A406-E645CEB4C4AF, (syncValue: UA8BH2TEJeXVzUTKQkgAcSJvVuwach5Q)'
2017-07-13 09:30:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C25A8FB-5F40-4,7C6-A406-E645CEB4C4AF:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 09:30:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750CF6A3-B1D5-4221-85F0-7689E1747463","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
2017-07-13 09:30:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0B6584A-55E2-4F22-9640-4ABB1B359C49:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0B6584A-55E2-4F22-9640-4ABB1B359C49", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:750CF6A3-B1D5-4221-85F0-7689E1747463:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "750CF6A3-B1D5-4221-85F0-7689E1747463", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", genera,tion: 0)
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UA8BH2TEJeXVzUTKQkgAcSJvVuwach5Q","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'UA8BH2TEJeXVzUTKQkgAcSJvVuwach5Q', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,09:30:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2C25A8FB-5F40-47C6-A406-E645CEB4C4AF","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:30:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0193AF29-BB70-49A6-9678-9B2D28BC8830 (syncValue: iX2ApMf,OJexndZToL9zP821FvxwMIrzu)'
2017-07-13 09:30:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0193AF29-BB70-49A6-9678-9B2D28BC883,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49943
2017-07-13 09:31:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iX2ApMfOJexndZToL9zP821FvxwMIrzu",,"error":null,"portNumber":49943}'
2017-07-13 09:31:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iX2ApMfOJexndZToL9zP821FvxwMIrzu', error: 'null', listeningPort: '49943''
,Connecting to the localhost:49943
,Connected to the localhost:49943
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [9, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-13 09:31:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [9]
,ok 124 got the same data back
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C25A8FB-5F40-47C6-A406-E645CEB4C4AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C25A8FB-5F40-47C6-A406-E645CEB4C4AF", generation: 0)
,2017-07-13 09:31:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:0193AF29-BB70-49A6-9678-9B2D28BC8830
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49943
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,# setup
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19D14F05-58A7-43A3-8622-77306C5F7C46
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:258A0987-3B4C-46D2-8465-A55E41EB0EBC
,2017-07-13 09:31:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}]'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}]'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}'
,2017-07-13 09:31:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:258A0987-3B4C-46D2-8465-A55E41EB0EBC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "258A0987-3B4C-46D2-8465-A55E41EB0EBC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14FF933A-6407-49A5-B304-4E3B0E38C0F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14FF933A-6407-49A5-B304-4E3B0E38C0F3", generation: 0)
2017-07-13 09:31:04 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"14FF933A-6407-49A5-B304-4E3B0E38C0F3","generation":0}]'
2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"14FF933A-6407-49A5-B304-4E3B0E38C0F3","generation":0}'
2017-07-13 09:31:04 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:31:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,09:31:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 09:31:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:31:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:08 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F762A23E-8CD0-48ED-AA79-BB2400906C2E
[ThaliCore] Browser.startListening
ok 133 discoveryActive should be false
ok 134 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "90FDA895-25F8-4A81-9AF1-F079841C4627", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:90FDA895-25F8-4A81-9AF1-F079,841C4627
ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,ok 139 discoveryActive should be false
ok 140 advertisingActive should be true
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
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 09:31:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 09:31:12 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:9b3d22e4-431c-45f8-a838-38748bc45f2d error: startListeningNotActive
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"01hAeZB1mc54jSHnqYyzdEJrYOSYZ3oR","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9b3d22e4-431c-45f8-a838-38748bc45f2d","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9b3d22e4-431c-45f8-a838-38748bc45f2d","peerAvailable":true,"portNumber":null,"recreated":true}'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8439FC46-17A5-4062-9713-13F98D0DCE9E
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1TqJYnjrTAmsniTE0HzdLYxRIWUirVDF","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DCBC845B-5374-4733-B220-A78B55586292
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0193AF29-BB70-49A6-9678-9B2D28BC8830:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0193AF29-BB70-49A6-9678-9B2D28BC8830", generation: 0)
2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 No error on starting
,ok 174 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:731C2C5E-0539-486A-B543-8DB415F54546:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "731C2C5E-0539-486A-B543-8DB415F54546", generation: 0)
,# teardown
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}]'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0193AF29-BB70-49A6-9678-9B2D28BC8830","generation":0}'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}]'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"731C2C5E-0539-486A-B543-8DB415F54546","generation":0}'
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
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
,[ThaliCore] BrowserManager.disconnect peer:6dd1ac3a-661a-4fe8-9e31-7b7fdfe58227
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 182 Should be able to call stopAdvertisingAndListening in teardown
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
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-13 09:31:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:16 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-13 09:31:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
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
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49948'
,ok 185 Should throw
,# teardown
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:17 - DEBUG createNativeListener: 'listening 49950'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49953'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49957'
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
,2017-07-13 09:31:18 - DEBUG createNativeListener: 'listening 49962'
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
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49966'
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
,2017-07-13 09:31:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-13 09:31:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:19 - DEBUG createNativeListener: 'listening 49970'
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
2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49974'
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
,2017-07-13 09:31:20 - DEBUG createNativeListener: 'listening 49978'
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
,ok 213 native server should be closed
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
,2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 50030'
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
,2017-07-13 09:31:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:23 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-13 09:31:23 - DEBUG createNativeListener: 'listening 50034'
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
,ok 230 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 231 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-13 09:31:24 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:24 - DEBUG createNativeListener: 'listening 50037'
ok 232 port must be in range
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:25 - DEBUG createNativeListener: 'listening 50038'
ok 233 second start should return same port
,# teardown
,2017-07-13 09:31:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:31:25 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-13 09:31:26 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-13 09:31:26 - DEBUG createNativeListener: 'listening 50040'
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
ok 236 Passed bogus id
2017-07-13 09:31:27 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port, 901'
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
,listening on 50042
,ok 243 should be equal
,# teardown
,2017-07-13 09:31:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D5BAF6D3-EDB2-4528-B144-7C271A324831
2017-07-13 0,9:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 244 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:370A6F9F-F6B7-4A43-9082-DBA67084851D
[ThaliCore] Browser.startListening
2017-07-13 09:31:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":0}'
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940 (syncValue: dRIuWZzzj5sa1jjyphcxP0jgun7zJ5GM)'
,2017-07-13 09:31:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Advertiser: session connected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Advertiser: session connected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":0}'
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02 (syncValue: 8hsncH2GwpjwsK0miGdCF2885E4Q2gkz)'
,2017-07-13 09:31:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
,[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: connecting -> connected
[ThaliCo,re] Browser: session connected to Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50049
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8hsncH2GwpjwsK0miGdCF2885E4Q2gkz","error":null,"portNumber":50049}'
2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8,hsncH2GwpjwsK0miGdCF2885E4Q2gkz', error: 'null', listeningPort: '50049''
2017-07-13 09:31:32 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: '8hsncH2GwpjwsK0miGdCF2885E4Q2gkz', originalSyncValue: 'dRIuWZzzj5sa1jjyphcxP,0jgun7zJ5GM''
,2017-07-13 09:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8hsncH2GwpjwsK0miGdCF2885E4Q2gkz', error: 'null', listeningPort: '50049''
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connecting -> connected
,ok 246 should be equal
,ok 247 (unnamed assert)
,appEnteringBackground wasn't registered
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: connecting -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generati,on: 0)
2017-07-13 09:31:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dRIuWZzzj5sa1jjyphcxP0jgun7zJ5GM","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:31:40 - DEBUG thaliMobileNativeTestUtils: ,'Got multiConnectResolved -syncValue: 'dRIuWZzzj5sa1jjyphcxP0jgun7zJ5GM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:31:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdenti,fier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:31:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 0,9:31:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:31:40 - DEBUG thaliMobileNativeWrappe,r: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:31:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940 (syncValue: I2Wn1dVPMm7bNyzLfx6V1EBpwKhh2zyx)'
,2017-07-13 09:31:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", genera,tion: 0)
2017-07-13 09:31:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"I2Wn1dVPMm7bNyzLfx6V1EBpwKhh2zyx","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:31:45 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'I2Wn1dVPMm7bNyzLfx6V1EBpwKhh2zyx', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:31:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:31:45 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 09:31:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B94,0","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:31:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 09:31:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:31:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940 (syncValue: z1yQ55M,x1gq3qzsJmusuvqNc1rN7sKtN)'
2017-07-13 09:31:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-451B-910D-A16CB2A3B94,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50053
2017-07-13 09:31:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z1yQ55Mx1gq3qzsJmusuvqNc1rN7sKtN","error":null,"portNumber":50053}'
,2017-07-13 09:31:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'z1yQ55Mx1gq3qzsJmusuvqNc1rN7sKtN', error: 'null', listeningPort: '50053''
,ok 248 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50049
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:9705760D-02FE-451B-910D-A16CB2A3B940
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50053
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:9705760D-02FE-451B-910D-A16CB2A3B940:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 0)
,2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F85F75DC-BF48-455B-8578-720B025FD3F5
,# setup
,# Multiple local http requests
,listening on 50055
,ok 249 should be equal
,ok 250 should be equal
,[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 0)
,ok 251 should be equal
,# teardown
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:F85F75DC-BF48-455B-8578-720B025FD3F5
,2017-07-13 09:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:D5BAF6D3-EDB2-4528-B144-7C271A324831
2017-07-13 0,9:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was, in stopped state).'
ok 252 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:31:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
2017-07-13 09:31:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02","generation":1}'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02, (syncValue: OSL5e4H0yqeMPfziKADvR56PUmEojcY0)'
2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", gen,eration: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C1BF13D-86BB-,4,C80-9FB9-C7ADB552AF02:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9705760D,-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9705760D-02FE-451B-910D-A16CB2A3B940","generation":1}'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9705760D-02FE-451B-910D-A16CB2A3B940 (syncValue: DQLc5IGBzk3QmJTpcx21CPEqIxTOWavm)'
,2017-07-13 09:31:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9705760D-02FE-451B-910D-,A16CB2A3B940", generation: 1)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
[ThaliCore] Advertiser: session connected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Advertiser: session connected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5BAF6D3-EDB2-4528-B144-7C271A324831:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50063
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DQLc5IGBzk3QmJTpcx21CPEqIxTOWavm","error":null,"portNumber":50063}'
2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D,QLc5IGBzk3QmJTpcx21CPEqIxTOWavm', error: 'null', listeningPort: '50063''
2017-07-13 09:31:54 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'DQLc5IGBzk3QmJTpcx21CPEqIxTOWavm', originalSyncValue: 'OSL5e4H0yqeMPfziKADvR,56PUmEojcY0''
2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DQLc5IGBzk3QmJTpcx21CPEqIxTOWavm', error: 'null', listeningPort: '50063''
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificat,eHandler:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E
,[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connecting -> connected
,ok 254 should be equal
ok 255 (unnamed assert)
[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB5,52AF02", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50065
,2017-07-13 09:31:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OSL5e4H0yqeMPfziKADvR56PUmEojcY0","error":null,"portNumber":50065}'
2017-07-13 09:31:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OSL5e4H0yqeMPfziKADvR56PUmEojcY0', error: 'null', listeningPort: '50065''
,ok 256 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connecting -> connected
,[ThaliCore] BrowserManager.disconnect peer:9705760D-02FE-451B-910D-A16CB2A3B940
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50063
[ThaliCore] Session.disconnect,() peer:9705760D-02FE-451B-910D-A16CB2A3B940:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:9705760D-02FE-451B-910D-A16CB2A3B940:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9705760D-02FE-451B-910D-A16CB2A3B940", generation: 1)
,[ThaliCore] BrowserManager.disconnect peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50065
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:F85F75DC-BF48-455B-8578-720B025FD3F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D5BAF6D3-EDB2-4528-B144-7C271A324831", generation: 1)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] AdvertiserRelay.deinit
[Th,aliCore] Session.deinit peer:F85F75DC-BF48-455B-8578-720B025FD3F5
[ThaliCore] Session.session(_:peer:didChange:) peer:2250D46C-15F6-4ECF-80FA-8B7DC20CE00E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D5BAF6D3-,EDB2-4528-B144-7C271A324831", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02:1 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C1BF13D-86BB-4C80-9FB9-C7ADB552AF02", generation: 1)
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
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 50067'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
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
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'listening 50068'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E43DEFB2-12CE-4C7E-A368-E82A156691CC
,[ThaliCore] Browser.startListening
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:31:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 50069'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A7F58D2-101E-414B-998F-1954F08642F1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8A7F58D2-101E-414B-998F-1954F08642F1
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8A7F58D2-101E-414B-998F-1954F08642F1", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:8A7F58D2-101E-414B-998F-1954F08642F1
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:31:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:31:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-13 09:31:58 - DEBUG thaliMobileNativeWrapper: 'listening 50072'
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
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'listening 50073'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6B9B7EAE-91F7-48F3-8D4E-7A9C31976962
[ThaliCore] Browser.st,artListening
2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D260DEBD-92FF-489A-8612-2A07593FC7FF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D260DEBD-92FF-489A-8612-2A07593FC7FF
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 277 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:31:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:31:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:31:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
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
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 50076'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C65BA19C-85A7-4654-BA80-B8174D7750F4
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "578D84ED-C402-4082-846A-1C0A39D48B6E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:578D84ED-C402-4082-846A-1C0A39D48B6E
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'listening 50078'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3FD63265-E5B9-40AD-9FF5-B729A54DB489
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "039C3E42-B405-4804-BD9A-E4D2738CF06E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:039C3E42-B405-4804-BD9A-E4D2738CF06E
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-13 09:32:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 is stopped after calling stop
,ok 282 connection should fail after stopping
,# teardown
,ok 283 must be stopped
,# setup
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-13 09:32:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 284 must be stopped
,# setup
,2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-13 09:32:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-13 09:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 292 must be stopped
,# setup
,2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-13 09:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-13 09:32:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
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
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50081'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73DD16CB-E7AA-4B3E-A80A-7B1D80FA1CCC
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
,ok 303 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50082'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B1EF4BD6-4A69-4FD9-B3D2-3ADD603C5A27", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B1EF4BD6-4A69-4FD9-B3D2-3ADD603C5A27
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 306 discoveryActive matches
,ok 307 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 308 discoveryActive matches
,ok 309 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50084'
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
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'listening 50085'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:46404877-B76D-4675-945F-ED4B90E015C6
[ThaliCore] Browser.st,artListening
2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 09:32:06 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC
,2017-07-13 09:32:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 09:32:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
2017-07-13 09:32:07 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:07 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 311 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F636408C-81C5-48E5-BF5A-0AB8DC3CB1EC", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'listening 50087'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:63D2DE2E-AFBA-4D5B-B500-3054131B4E8A
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AE6727F4-D361-4B1F-BB82-6390F9AEED26
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2D1BE89A-3F6E-4C07-9680-7C097E53E609 (syncValue: cfOFFEEHT988tGGyGlj8nCWwLf8RsTKz)'
,2017-07-13 09:32:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
2017-07-13 09:32:09 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
2017-07-13 09:32:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA031,3-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
2017-07-13 09:32:09 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE6727F4-D361-4B1F-BB82-6390F9AEED26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0)
[ThaliCore] Session.disconnect() peer:2D1BE89A-3F6,E-4C07-9680-7C097E53E609:0
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}]'
2017-07-13 09:32:,14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","generation":0}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:14 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "2D1BE89A-3F6E-4C07-9680-7C097E53E609", genera,tion: 0)
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cfOFFEEHT988tGGyGlj8nCWwLf8RsTKz","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'cfOFFEEHT988tGGyGlj8nCWwLf8RsTKz', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2D1BE89A-3F6E-4C07-9680-7C097E53E609","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:2D1BE89A-3F6E-4C07-9680-7C097E53E609
,2017-07-13 09:32:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B2AA0313-20EC-4F3D-B0CE-C2A671E93E47 (syncValue: eNXx5lKxfFGQ5sSHvp4FDKxxbFrfVujP)'
,2017-07-13 09:32:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5
[ThaliCore] Advertiser: session connected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5 state: notConnected -> connecting
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5
[ThaliCore] Session.startOutputStream(with:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [9, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3
[ThaliCore] Advertiser: session connected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50093
,2017-07-13 09:32:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eNXx5lKxfFGQ5sSHvp4FDKxxbFrfVujP","error":null,"portNumber":50093}'
,2017-07-13 09:32:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eNXx5lKxfFGQ5sSHvp4FDKxxbFrfVujP', error: 'null', listeningPort: '50093''
,2017-07-13 09:32:19 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [9, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:20 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:20 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
,ok 314 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3
[ThaliCore] Session.startOutputStream(with:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [9, 12, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:23 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:32:23 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
ok 315 must be stopped
[ThaliCore] BrowserManager.disconnect peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAn,dDisconnectClients() port:50093
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket erro,r:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSoc,ket exited RunLoop vsID:13
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
,[ThaliCore] VirtualSocket.deinit vsID:13 [9, 12, 14]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: connected -> notConnected
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] Browser: session notConnected Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore,] VirtualSocket.closeStreams() vsID:14
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [9, 14]
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7B0B94C-601D-440A-8933-C566AEC326F3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B7B0B94C-601D-440A-8933-C566AEC326F3
[ThaliCore] Session.deinit peer:B7B0B94C-601D-44,0A-8933-C566AEC326F3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit v,sID:14 [9]
,[ThaliCore] Session.session(_:peer:didChange:) peer:8FFC04AB-E06E-425C-8AB7-66FCD27E0EC5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "AE6727F4-D361-4B1F-BB82-6390F9AEED26", generation: 0)
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 09:32:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 09:32:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'listening 50096'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D53DF4B-468B-4C8A-8FC4-0A7692364E72
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:32:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
2017-07-13 09:32:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285 (syncValue: FF7E93smW1Fkvm9zKyHYf6dGD8VtpEqE)'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}]'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","generation":0}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
2017-07-13 09:32:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}]'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49058887-1F08-49CB-,9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAva,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
ilable":true,"generation":0,",newAddressPort":false}'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeW,rapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}]'
2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ev,ent with {"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C084CE57-C7F3-4479-BF0F-ED3250D8F6A8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C084CE57-C7F3-4479-BF0F-ED3250D8F6A8", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0)
[ThaliCore] Session.disconnect() peer:DF75FDF7-A43,A-4303-B9F6-ED8F2C8FA285:0
2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}]'
2017-07-13 09:32:,29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","generation":0}'
,2017-07-13 09:32:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-13 09:32:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285", genera,tion: 0)
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FF7E93smW1Fkvm9zKyHYf6dGD8VtpEqE","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'FF7E93smW1Fkvm9zKyHYf6dGD8VtpEqE', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2,C8FA285","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:DF75FDF7-A43A-4303-B9F6-ED8F2C8FA285
2017-07-13 09:32:30 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Connection could not be established''
2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B2AA0313-20EC-4F3D-B0CE-C2A671E93E47 (syncValue: CSGf5ViahasVecaMVDve6aLe28jyI6a4)'
,2017-07-13 09:32:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0) new relay
[ThaliCore] Browser.invite,ToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B2AA0313-20EC-4F3D-B0CE-C2A671E93E47:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B2AA0313-20EC-4F3D-B0CE-C2A671E93E47", genera,tion: 0)
2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CSGf5ViahasVecaMVDve6aLe28jyI6a4","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'CSGf5ViahasVecaMVDve6aLe28jyI6a4', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671,E93E47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:35 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:32:35 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 09:32:35 -, DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49058887-1F08-49CB-9D96-189287BA7435 (syncValue: VL937bfn2ZX9bLDQgOuXzqW9WW8MfgvV)'
2017-07-13 09:32:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserMana,ger.connectToPeer(_:syncValue:completion:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generati,on: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:st,oppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50106
2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VL937bfn2ZX9bLDQgOuXzqW9WW8MfgvV","error":null,"portNumber":50106}'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VL937bfn2ZX9bLDQgOuXzqW9WW8MfgvV', error: 'null', listeningPort: '50106''
,2017-07-13 09:32:39 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [9, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:39 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:39 - DEBUG testUtils: 'Got end'
,ok 316 response body should match testData
,ok 317 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:32:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 318 must be stopped
[ThaliCore] BrowserManager.disconnect peer:49058887-1F08-49CB-9D96-189287BA7435
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50106
[Thali,Core] VirtualSocket.closeStreams() vsID:15
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:15 [9]
,[ThaliCore] Session.disconnect() peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,# setup
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 09:32:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 09:32:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 09:32:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'listening 50108'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:63F813D0-C2D6-43B6-AC05-ABD1E8DB2C82
,[ThaliCore] Browser.startListening
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B
,2017-07-13 09:32:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 09:32:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}]'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}]'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}]'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49058887-1F08-49CB-9D96-189287BA7435 (syncValue: zUcffcDI0R2DLyp8cSARZuA9srCv6zQ0)'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49058887-1F08-49CB-9D96-189287BA7435:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:32:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:32:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B2889B17-97C7-4AA9-8BDD-C59AF4B70C3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49058887-1F08-49CB-9D96-189287BA7435:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", genera,tion: 0)
2017-07-13 09:32:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zUcffcDI0R2DLyp8cSARZuA9srCv6zQ0","error":"Connection could not be established","portNumber":null}'
2017-07-13 09:32:47 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'zUcffcDI0R2DLyp8cSARZuA9srCv6zQ0', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 09:32:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 09:32:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"49058887-1F08-49CB-9D96-189287,BA7435","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-13 09:32:47 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13 09:32:47 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-13 09:32:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-13 09:32:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7 (syncValue: KLUHVWeK7GNsa0XW2TJQF3bZgetNxzFh)'
,2017-07-13 09:32:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0)
[ThaliCore] Session.disconnect() peer:3A71E3BD-F1C,B-4ED3-90E3-C8236E4123D7:0
2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}]'
2017-07-13 09:32:,49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","generation":0}'
,2017-07-13 09:32:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:49 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49058887-1F08-49CB-9D96-189287BA7435:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49058887-1F08-49CB-9D96-189287BA7435", generation: 0)
2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}]'
2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","generation":0}'
,2017-07-13 09:32:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-13 09:32:52 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"49058887-1F08-49CB-9D96-189287BA7435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7", genera,tion: 0)
2017-07-13 09:32:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KLUHVWeK7GNsa0XW2TJQF3bZgetNxzFh","error":"Connection could not be established","portNumber":null}'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KLUHVWeK7GNsa0XW2TJQF3bZgetNxzFh', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:3A71E3BD-F1CB-4ED3-90E3-C8236E4123D7
,2017-07-13 09:32:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 946EA4DB-6614-40DB-B5B5-705E7310BB5E (syncValue: eGKDiTmdS65EH2YACLToyK1xzAGxOheY)'
,2017-07-13 09:32:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50117
,2017-07-13 09:32:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eGKDiTmdS65EH2YACLToyK1xzAGxOheY","error":null,"portNumber":50117}'
,2017-07-13 09:32:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eGKDiTmdS65EH2YACLToyK1xzAGxOheY', error: 'null', listeningPort: '50117''
,2017-07-13 09:32:57 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [9, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:32:57 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:32:57 - DEBUG testUtils: 'Got end'
,ok 321 response body should match testData
,ok 322 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:32:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:32:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 323 must be stopped
[ThaliCore] BrowserManager.disconnect peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore], TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50117
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] Session.disconnect() peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [9]
,[ThaliCore] Session.session(_:peer:didChange:) peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,# setup
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 09:32:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B2AA0313-20EC-4F3D-B0CE-C2A671E93E47","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 50119'
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
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'listening 50120'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B0CD9D8E-9F40-41A6-A81B-0A3E331C81E0
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 344 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F10A0D7-8856-4298-AD0B-593BA1AE204A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F10A0D7-8856-4298-AD0B-593BA1AE204A", generation: 0)
ok 345 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 346 error should be null
ok 347 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:946EA4DB-6614-40DB-B5B5-705E7310BB5E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "946EA4DB-6614-40DB-B5B5-705E7310BB5E", generation: 0)
,# teardown
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}]'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","generation":0}'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}]'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","generation":0}'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-13 09:33:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:33:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9F10A0D7-8856-4298-AD0B-593BA1AE204A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13, 09:33:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"946EA4DB-6614-40DB-B5B5-705E7310BB5E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 50121'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BFF16C0C-861D-4DCA-83A5-772395CC7FEE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BFF16C0C-861D-4DCA-83A5-772395CC7FEE
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 351 error should be null
,ok 352 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BFF16C0C-861D-4DCA-83A5-772395CC7FEE", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:BFF16C0C-861D-4DCA-83A5-772395CC7FEE
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 353 error should be null
,ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-13 09:33:01 - DEBUG thaliMobileNativeWrapper: 'listening 50124'
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
,2017-07-13 09:33:01 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 365 This should not cause wifi to fail
,ok 366 native router should be bad
,# teardown
,ok 367 error should be null
ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-13 09:33:02 - DEBUG thaliMobileNativeWrapper: 'listening 50125'
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
ok 374 error should be null
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
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5e5e658d-6b85-4de4-a8fd-bc5e8e7a2b19","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 382 should be called once
,ok 383 should not have been called more than once
,# teardown
,2017-07-13 09:33:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5e5e658d-6b85-4de4-a8fd-bc5e8e7a2b19","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8ea68aab-1cf4-4773-8553-6b1080ba01d9","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 392 peer should be available
ok 393 cache contains native peer
2017-07-13 09:33:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8ea68aab-1cf4-4773-8553-6b1080ba01d9","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 394 peer should be unavailable
,ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"517e51c5-7901-4aaa-92bd-b44d104fec76","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 400 peer should be available
,ok 401 cache contains wifi peer
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"517e51c5-7901-4aaa-92bd-b44d104fec76","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 402 peer should be unavailable
,ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
,ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2afef48-7fef-4db2-bbb3-327c972e1a1e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 407 first peer is available
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"710f7efb-4a59-4544-85d0-d6fea0a1b952","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 second peer is available
,ok 409 first and second peers are different
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a2afef48-7fef-4db2-bbb3-327c972e1a1e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"710f7efb-4a59-4544-85d0-d6fea0a1b952","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"87792018-f762-4426-baf0-d85deb9fd51e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 peer is available
,# teardown
,2017-07-13 09:33:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"87792018-f762-4426-baf0-d85deb9fd51e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 415 error should be null
,ok 416 error should be null
,# setup
,ok 417 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-13 09:33:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 418 error should be null
ok 419 error should be null
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
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c5aa59f-6373-4f3a-9aba-3e9426376d8e","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 424 peer should be available
,2017-07-13 09:33:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3c5aa59f-6373-4f3a-9aba-3e9426376d8e","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 425 peer should be available
ok 426 should store correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3c5aa59f-6373-4f3a-9aba-3e9426376d8e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
,ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 50126'
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d0b3b2ac-b797-4281-a1fd-b66997e46fab","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d0b3b2ac-b797-4281-a1fd-b66997e46fab","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d0b3b2ac-b797-4281-a1fd-b66997e46fab","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-13 09:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-13 09:33:07 - DEBUG thaliMobileNativeWrapper: 'listening 50127'
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58cf0f36-3293-4981-93c1-897325f8ab7d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 discovered available peer
,ok 438 peer is available
,# teardown
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"58cf0f36-3293-4981-93c1-897325f8ab7d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d4bce38-8950-4241-88a9-87f778eec8c3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 442 peer should be available
,2017-07-13 09:33:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1d4bce38-8950-4241-88a9-87f778eec8c3","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 443 peer should be unavailable
,ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 50128'
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ae55f805-00d1-4795-bbc6-c5a80e8ba8b3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 448 first peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"737dec59-ce34-4060-ae65-7ea76ba74f14","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 449 second peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"737dec59-ce34-4060-ae65-7ea76ba74f14","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 450 peer became unavailable
,ok 451 it was wifi peer
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"737dec59-ce34-4060-ae65-7ea76ba74f14","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 we found peer again
,ok 453 it was wifi peer
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"737dec59-ce34-4060-ae65-7ea76ba74f14","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 454 peer became unavailable
,ok 455 it was wifi peer
,# teardown
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ae55f805-00d1-4795-bbc6-c5a80e8ba8b3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-13 09:33:08 - DEBUG thaliMobileNativeWrapper: 'listening 50129'
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0cdd35ed-579f-4621-8f7c-a29941a78e74","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 first peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b3703dd-7faa-498d-af5d-35a9d7767717","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 463 second peer is expected to be available
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0cdd35ed-579f-4621-8f7c-a29941a78e74","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-13 09:33:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b3703dd-7faa-498d-af5d-35a9d7767717","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
ok 470 error should be null
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
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63d28c28-94f2-4b14-80f9-394e23c2bbb2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 475 peer discovered ,first time does not have new address
2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63d28c28-94f2-4b14-80f9-394e23c2bbb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 476 address has not been changed
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63d28c28-94f2-4b14-80f9-394e23c2bbb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 477 new port handled correctly
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63d28c28-94f2-4b14-80f9-394e23c2bbb2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 478 new host handled correctly
,2017-07-13 09:33:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63d28c28-94f2-4b14-80f9-394e23c2bbb2","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
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
,ok 491 error should be null
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
,ok 506 contains expected properties
,ok 507 the same hostAddress
,ok 508 the same portNumber
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 50130'
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88a795d9-9979-4be3-85c8-65966da6c700","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"88a795d9-9979-4be3-85c8-65966da6c700","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-13 09:33:12 - DEBUG thaliMobileNativeWrapper: 'listening 50131'
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21fd44c6-eb30-45e9-b158-9606d1976e44","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:21fd44c6-eb30-45e9-b158-9606d1976e44
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-13 09:33:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"21fd44c6-eb30-45e9-b158-9606d1976e44","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-13 09:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 524 error should be null
,ok 525 error should be null
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
,ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-13 09:33:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 536 error should be null
,ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-13 09:33:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 539 error should be null
,ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'listening 50132'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A318BD14-C24A-4B6E-A507-D01E6241724A
[ThaliCore] Browser.startListening
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"eecbc445-5dd6-4997-8601-0003c02f55da","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 542 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f27cc32a-ded2-457a-bafb-bd9106c6d63f","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"eecbc445-5dd6-4997-8601-0003c02f55da","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f27cc32a-ded2-457a-bafb-bd9106c6d63f","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 09:33:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-13 09:33:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-13 09:33:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 544 No peers
,ok 545 No peers
,ok 546 No peers
,# teardown
,ok 547 error should be null
ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-13 09:33:17 - DEBUG thaliMobileNativeWrapper: 'listening 50133'
2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0cc7724c-7f03-4235-9cbd-ecd02287bcfa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 550 1
ok 551 2
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"24a428f6-cc53-45a7-aa49-e92fb2d24871","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0cc7724c-7f03-4235-9cbd-ecd02287bcfa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-13 09:33:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"24a428f6-cc53-45a7-aa49-e92fb2d24871","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'listening 50134'
,ok 558 error should be null
,ok 559 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8F99E40C-F002-41B4-82DB-5743D21B8724
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 560 error should be null
,ok 561 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9C5D4377-7D93-4F72-844F-2719CD011FFB
,[ThaliCore] Browser.startListening
,2017-07-13 09:33:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 562 error should be null
,ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","generation":0}]'
2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","connectionType":"MPCF","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 5FCCD746-4D8D-40F,2-BC08-F7A42F066745 (syncValue: 0)'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0) new relay
[ThaliCore] Browser.inviteToCo,nnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","generation":0}]'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","generation":0}'
,2017-07-13 09:33:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:33:19 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F99E40C-F002-41B4-82DB-5743D21B8724:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5FCCD746-4D8D-40F2-BC08-F7A42F066745", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50137
2017-07-13 09:33:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":50137,}'
2017-07-13 09:33:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 39984708-4DDD-48C8-82A8-BD25A56C4040 (syncValue: 1)'
2017-07-13 09:33:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39984708-4DDD-48C8-82A8-,BD25A56C4040", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] Advertiser: session connected Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5FCCD746-4D8D-40F2-BC08-F7A42F066745:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [9, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:23 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:23 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] Advertiser: session connected Peer(uuid: "8F99E40C-F002-41B4-82DB-5743D21B8724", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "39984708-4DDD-48C8-82A8-BD25A56C4040", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50141
,2017-07-13 09:33:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":50141}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:39984708-4DDD-48C8-82A8-BD25A56C4040:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [9, 17, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:33:25 - DEBUG testUtils: 'Got response data'
,2017-07-13 09:33:25 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
,[ThaliCore] Session.session(_:peer:didChange:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] Session.startOutputStream(with:) peer:9989BDA9-86AE-4C50-B282-DF7F6E94AC20
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [9, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
,[ThaliCore] Session.startOutputStream(with:) peer:5D45A7D3-C9AE-4F3D-ADD3-10572E4A7E27
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [9, 17, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5FCCD746-4D8D-40F2-BC08-F7A42F066745","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-13, 09:33:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39984708-4DDD-48C8-82A8-BD25A56C4040","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 09:33:31 - INFO thaliMobile,: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-13 09:33:31 - INFO thaliMobile: 'Filtered out dis,coveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 09:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 09:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-13 09:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer}),
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.,closeStreams() vsID:18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket.deinit vsID:19 [9, 17, 18, 20]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [9, 17, 20]
[ThaliCore] ,TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [9, 17]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [9]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 565 error should be null
,ok 566 error should be null
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
,ok 598 Size must be 4
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
,ok 610 Size must be 0
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
ok 624 enqueue is fine
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
ok 648 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 649 null arg
ok 650 wrong arg type
,ok 651 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 652 good enqueue
ok 653 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 654 good enqueue
ok 655 2nd good enqueue
ok 656 we are in the pool
,ok 657 We are out of the pool
ok 658 Action was killed
ok 659 The original kill was called too
ok 660 second item is still in queue
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
ok 668 1st action is out of the pool
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
,ok 677 Got null
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 678 is an agent
,2017-07-13 09:33:44 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
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
,ok 686 Action 2 killed at least once
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
,ok 692 Null 1
,ok 693 (unnamed assert)
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 694 is an agent
,ok 695 Null 3
,ok 696 Replication not yet called
,ok 697 Notification 2 not yet called
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 698 is an agent
,ok 699 Notification went first
,ok 700 Notification 2 not called yet
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
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
,2017-07-13 09:33:45 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
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
ok 724 reject reason should be: Could not establish TCP connection
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
,ok 731 Start after killed
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
ok 735 must return null after successful kill
,# teardown
,2017-07-13 09:33:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 736 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 737 must return null after successful call
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
,ok 741 Should be Could not establish TCP connection
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
ok 760 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 761 should be equal
,ok 762 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 763 right number of calls to address book
,ok 764 good preAmble
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
,ok 778 secrets match
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
ok 794 portNumber must match
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
,ok 805 action should be resolved with NETWORK_PROBLEM error
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
,2017-07-13 09:34:13 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 811 peerDictionary should become empty
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
ok 817 Public key matches with the server key
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
,# teardown
,2017-07-13 09:34:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 827 Size of the cache should be 2
,ok 828 Cache doesn't contain dictionary1
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
ok 840 should be 200
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
,ok 847 should be 204
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
,ok 852 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 853 second cleared dictionary
,2017-07-13 09:34:24 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 854 First start and on called correctly
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
,ok 897 All tests passed!
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
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'listening 50271'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1A1703E8-9900-4A38-B47D-D710FC2CFAA6
[ThaliCore] Browser.startListening
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427
,2017-07-13 09:34:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
2017-07-13 09:34:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","generation":0}]'
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E48E184A-0302-4946-8B90-52C396,560D15","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"E48E184A-0302-4946-8B90-52C396560D15","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 2)'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) new relay
[ThaliCore] Browser.inviteToCo,nnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] BrowserRelay.ini,t(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":tr,ue,"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","generation":0}]'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","generation":0}'
,2017-07-13 09:34:51 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-13 09:34:51 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E1D4A1C4-F2E4-466C-8316-4CE316BB98A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E48E184A-0302-4946-8B90-52C396560D15:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E48E184A-0302-4946-8B90-52C396560D15:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50276
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Advertiser: session ,connected Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A6AB4652-B050-40CE-A24C-DC4,10C5E143E state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Advertiser: session connected Peer(uuid: "0BC5F6D9-8F29-4D0E-A0D2-D2915AEAC427", genera,tion: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E85005C5-0D84-44ED-B96D-D756C4327934 state: notConnected -> connecting
2017-07-13 09:34:54 - ,DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50276}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 3)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50276}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 4)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":50276}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E48E184A-0302-4946-8B90-52C396560D15 (syncValue: 5)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E48E184A-0302-4946-8B90-52C396560D15", generation: 0) found active relay
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":50276}'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 6)'
,2017-07-13 09:34:54 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [9, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [9, 21, 22]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [9, 21, 22, 23]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [9, 21, 22, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [9, 21, 23, 24]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:23 [9, 21, 24]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [9, 21, 24, 25]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:24 [9, 21, 25]
,2017-07-13 09:34:55 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [9, 21, 25, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [9, 21, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [9, 21, 25, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [9, 21, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [9, 21, 25, 26, 27, 29]
,2017-07-13 09:34:56 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.session(_:peer:didChange:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [9, 21, 25, 26, 27, 29, 30]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [9, 21, 25, 26, 27, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [9, 21, 25, 26, 27, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.session(_:peer:didChange:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0 state: connecting -> connected
[ThaliCo,re] Browser: session connected to Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50291
,[ThaliCore] Session.session(_:peer:didChange:) peer:E85005C5-0D84-44ED-B96D-D756C4327934 state: connecting -> connected
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":50291}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 7)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":50291}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 8)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":50291}'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E1D4A1C4-F2E4-466C-8316-4CE316BB98A8 (syncValue: 9)'
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "E1D4A1C4-F2E4-466C-8316-4CE316BB98A8", generation: 0) found active relay
,2017-07-13 09:34:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":50291}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [9, 21, 25, 26, 27, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [9, 21, 25, 26, 27, 29, 30, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[T,haliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [9, 21, 25, 26, 27, 29, 30, 33, 34, 35, 36, 37, 38, 39, 40, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Thali,Core] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [9, 21, 25, 26, 27, 29, 30, 34, 35, 36, 37, 38, 39, 40, 41]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [9, 21, 25, 26, 27, 29, 30, 34, 35, 36, 37, 38, 39, 40, 41, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
,[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [9, 21, 25, 26, 27, 29, 34, 35, 36, 37, 38, 39, 40, 41, 42]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:36 [9, 21, 25, 26, 27, 29, 34, 35, 37, 38, 39, 40, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [9, 21, 25, 26, 27, 29, 35, 37, 38, 39, 40, 41, 42]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [9, 21, 25, 26, 27, 29, 37, 38, 39, 40, 41, 42]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
,[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [9, 21, 25, 26, 27, 29, 37, 38, 40, 41, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected,
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:37 [9, 21, 25, 26, 27, 29, 38, 40, 41, 42]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
,[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [9, 21, 25, 26, 27, 29, 38, 41, 42]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [9, 21, 25, 26, 27, 29, 38, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
,[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [9, 21, 25, 26, 27, 29, 38, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
,[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [9, 21, 25, 26, 27, 29, 42, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconn,ect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [9, 21, 25, 26, 27, 29, 42, 43, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45, 46]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45, 46, 47, 48]
[ThaliCore] BrowserRelay.didOpe,nVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45, 46, 47, 48, 49]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [9, 21, 25, 26, 27, 29, 42, 43, 44, 45, 46, 47, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [9, 21, 26, 27, 29, 42, 43, 44, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [9, 21, 27, 29, 42, 43, 44, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [9, 21, 29, 42, 43, 44, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E48E184A-0302-4946-8B90-52C396560D15:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E1D4A1C4-F2E4-466C-8316-4CE316BB98A8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,4 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A6AB46,52-B050-40CE-A24C-DC410C5E143E
[ThaliCore] Session.startOutputStream(with:) peer:A6AB4652-B050-40CE-A24C-DC410C5E143E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55]
[Thal,iCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-13 09:34:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] Session.startOutputStream(with:) peer:E85005C5-0D84-44ED-B96D-D756C4327934
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 53, 54, 55, 56]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.deinit vsID:54 [9, 21, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 53, 55, 56]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:35:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-13 09:35:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:43
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [9, 21, 42, 44, 45, 46, 47, 48, 49, 50, 51, 53, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [9, 21, 42, 44, 45, 46, 48, 49, 50, 51, 53, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [9, 21, 42, 44, 45, 46, 49, 50, 51, 53, 55, 56]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
,[ThaliCore] VirtualSocket.deinit vsID:53 [9, 21, 42, 44, 45, 46, 49, 50, 51, 55, 56]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [9, 21, 42, 45, 46, 49, 50, 51, 55, 56]
[ThaliCore] TCPClient.socketDidDisconne,ct(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [9, 21, 42, 45, 49, 50, 51, 55, 56]
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDis,connect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:56 [9, 21, 42, 45, 49, 50, 51, 55]
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [9, 21, 42, 45, 49, 51, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [9, 21, 45, 49, 51, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] Vi,rtualSocket.deinit vsID:45 [9, 21, 49, 51, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocket,DisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliC,ore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:49 [9, 21, 51, 55]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [9, 21, 51]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cl,ient disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 09:37:50 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-13 09:37:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:37:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:37:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:37:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:38:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:38:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:39:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:39:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:40:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:40:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:41:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:41:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:42:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:42:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:43:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:43:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:44:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-13 09:44:49 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,nts plugin delay interval'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-13 09:44:49 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueu,e and run in order'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-13 09,:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-13 09:44:49 - IN,FO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
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
2017-07-13 09:44:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
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
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if calle,d twice in a row'
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
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event, for wifi peers'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
2017-07-13 09:44:50 - INFO CoordinatedCl,ient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
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
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we c,atch kill and dequeue'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER re,sult: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
2017-07-13 09:44:50 - INFO Coordina,tedClient: '***TEST_LOGGER result: passed - Two notification actions'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - ,Replication goes first'
2017-07-13 09:44:50 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
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
    at SubError@/private/var/containers/Bundle/Appli,cation/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxco,re/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-13 09:44:50 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-13 09:44:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:44:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 909 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-13 09:45:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:45:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:45:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:46:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:46:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:47:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:47:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4,227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 09:48:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-422,7-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 09:48:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/06A17514-A3AA-4227-92AC-36CF99BC821C/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
