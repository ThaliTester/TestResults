#### Test 11335185196ab692_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/798C9C96-E295-46D6-835A-75FD0506653C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/798C9C96-E295-46D6-835A-75FD0506653C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63622"
,(lldb)     command script import "/tmp/798C9C96-E295-46D6-835A-75FD0506653C/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
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
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-13 07:36:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7BC2EE70-B104-4942-AE90-7066AC1A4900", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7BC2EE70-B104-4942-AE90-7066AC1A4900
,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B99F2B53-100C-419E-9726-0F3A4B46E85E
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C9C6ABE-BA3C-464D-AF28-F5E35E4D0C4F
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CD2FE5A5-DA66-4FDA-8807-029E138AA174", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CD2FE5A5-DA66-4FDA-8807-029E138AA174
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD2FE5A5-DA66-4FDA-8807-029E138AA174:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD2FE5A5-DA66-4FDA-8807-029E138AA174", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-13 07:36:27 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
Total duration:  1.304181933403015
,2017-07-13 07:36:27 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-13 07:36:27 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CD2FE5A5-DA66-4FDA-8807-029E138AA174:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CD2FE5A5-DA66-4FDA-8807-029E138AA174", generation: 0)
,2017-07-13 07:36:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 07:36:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 07:36:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 07:36:28 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 07:36:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 07:36:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 07:36:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 07:36:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 07:36:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:36:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:36:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:36:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:36:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:36:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:36:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:36:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:36:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:37:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:37:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429,B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 07:38:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 07:38:57 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 07:38:57 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 07:39:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 07:39:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 07:39:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 07:39:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-13 07:39:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
2017-07-13 07:39:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 07:39:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
,ok 5 should be equal
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
,2017-07-13 07:39:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 07:39:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 07:39:36 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-13 07:39:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 07:39:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FDF94D58-D814-4F81-8B5D-EE18264E5F65
[ThaliCore] Browser.startListening
,2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:39:48 - DEBUG thaliMobileNativeWrapper: 'disco,veryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without e,r,ror
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:436F2243-16A8-4D27-B664-7E0BDEA30CA8
[ThaliCore] Browser.startListening
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13, 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:49 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:50 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A98D8D26-D4F8-4CFE-98BF-DA91B25EDE10", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A98D8D26-D4F8-4CFE-98BF-DA91B25EDE10
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discovery,AdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:51 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C9636CA3-337D-424C-A83C-44EFDE7BEEE6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C9636CA3-337D-424C-A83C-44EFDE7BEEE6
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C9636CA3-337D-424C-A83C-44EFDE7BEEE6", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:C9636CA3-337D-424C-A83C-44EFDE7BEEE6
2017-07-13 0,7:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:3,9:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertisin,g()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:52 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:52 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 07:39:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 07:39:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "668BFA24-1C83-4C25-A698-52B1925BCC32", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:668BFA24-1C83-4C25-A698-52B1925BCC32
,2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:022925B6-6A4D-41F5-91A0-7A710D650,2DA
[ThaliCore] Browser.startListening
2017-07-13 07:39:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 07:39:53 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:53 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAd,v,ertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:39:54 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8
2017-07-13 0,7:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0751906-039A-4376-B8F1-E1498FE84111
[Thal,i,Core] Browser.startListening
2017-07-13 07:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 07:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:39:54 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","generation":0}'
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87 (syncValue: ku9HgIyFpVDwe8CJQmBSWzORJeHWUBa8)'
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:39:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"07BA770A-1623-4693-8CFA-B9750DA025BA","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0)
[ThaliCore] Session.disconnect() peer:62B01EB5-FAA,C-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
2,017-07-13 07:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
2017-07-13 07:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65A3BFA4-3808-4AFD-9773-59BA8C46E2F8:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:07BA770A-1623-4693-8CFA-B9750DA025BA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "07BA770A-1623-4693-8CFA-B9750DA025BA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87", genera,tion: 0)
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ku9HgIyFpVDwe8CJQmBSWzORJeHWUBa8","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'ku9HgIyFpVDwe8CJQmBSWzORJeHWUBa8', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"62B01EB5-FAAC-4F02-ACD9-F2E305E5DD87","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7 (syncValue: oHsQmyz,EVXNJJkiKhWovPS9lTVDypJj8)'
2017-07-13 07:40:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A,7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2
[ThaliCore] Advertiser: session connected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50
[ThaliCore] Advertiser: session connected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50
,[ThaliCore] Session.session(_:peer:didChange:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49330
,2017-07-13 07:40:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oHsQmyzEVXNJJkiKhWovPS9lTVDypJj8","error":null,"portNumber":49330}'
,2017-07-13 07:40:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oHsQmyzEVXNJJkiKhWovPS9lTVDypJj8', error: 'null', listeningPort: '49330''
,2017-07-13 07:40:04 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2 state: connecting -> connected
,2017-07-13 07:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49330
[ThaliCore] Session.disconnect() peer:B977EE9C,-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0 state: connected -> notConnected
[ThaliCore] ,B,rowser: session notConnected Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
# setup
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:883F5BBE-EDEE-48D4-A797-D586985545C4
,2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A1B3E12-2EEA-4C75-9FE2-281E313FFE3E
,[ThaliCore] Browser.startListening
2017-07-13 07:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 07:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:07 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.session(_:peer:didChange:) peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:70DB33E6-66FC-45C7-AE62-2D236D98DD50
,[ThaliCore] Session.session(_:peer:didChange:) peer:89EC8445-330D-46BF-9B57-E0928F563ED2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "65A3BFA4-3808-4AFD-9773-59BA8C46E2F8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
2017-07-13 07:40:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","generation":0}'
2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DF43B91C-BBA8-4DB3-99C5-7CF7E5038090, (syncValue: QWKCEAUCDd193KcBID9XiPTFPjUdq1gj)'
2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DF43B91C-BBA8-,4,DB3-99C5-7CF7E5038090:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
2017-07-13 07:40:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0770DD0B-3938-42AB-BD22-0A1EE963ACCD:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0770DD0B-3938-42AB-BD22-0A1EE963ACCD", generation: 0)
2017-07-13 07:40:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0770DD0B-3938-42AB-BD22-0A1EE963ACCD,","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:883F5BBE-EDEE-48D4-A797-D586985545C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "883F5BBE-EDEE-48D4-A797-D586985545C4", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0)
[ThaliCore] Session.disconnect() peer:DF43B91C-BBA,8-4DB3-99C5-7CF7E5038090:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:DF43B91C-BBA8-4DB3-99C5-7CF7E5038090:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "DF43B91C-BBA8-4DB3-99C5-7CF7E5038090", genera,tion: 0)
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QWKCEAUCDd193KcBID9XiPTFPjUdq1gj","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'QWKCEAUCDd193KcBID9XiPTFPjUdq1gj', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"DF43B91C-BBA8-4DB3-99C5-7CF7E5038090","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:13 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7 (syncValue: cHo2jK8,QL3wZsxohsNItUBRGAQr9owV2)'
2017-07-13 07:40:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A,7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", genera,tion: 0)
2017-07-13 07:40:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cHo2jK8QL3wZsxohsNItUBRGAQr9owV2","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'cHo2jK8QL3wZsxohsNItUBRGAQr9owV2', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:19 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 660CEBE9-D970-4CC3-8112-DBD0DF36D4CE (syncValue: wY70rz9,ktKJH1CF1Ltxh5npUPldEFWe3)'
2017-07-13 07:40:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4C,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B977EE9C-4CC5-4BD7-9DCA-93ACEAD6C8A7", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startLi,steningForConnections(on:connectionAccepted:completion:) port:0 localport:49340
2017-07-13 07:40:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wY70rz9ktKJH1CF1Ltxh5npUPldEFWe3","error":null,"portNumber":49340}'
2017-07-13 07:4,0:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wY70rz9ktKJH1CF1Ltxh5npUPldEFWe3', error: 'null', listeningPort: '49340''
,Connecting to the localhost:49340
,Connected to the localhost:49340
2017-07-13 07:40:21 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-13 07:40:21 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed ,by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket,.closeStreams() vsID:1
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49340
[ThaliCore] Session.disconnect() peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,2017-07-13 07:40:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE
,# setup
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 07:40:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 07:40:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:724A47F8-A6A9-4ACB-88A5-C246773D2521
2017-07-13 0,7:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:82CE4286-2D50-46D5-8EF4-2FB983849921
[Tha,l,iCore] Browser.startListening
2017-07-13 07:40:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 07:40:24 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
2017-07-13 07:40:25 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","generation":0}'
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 660CEBE9-D970-4CC3-8112-DBD0DF36D4CE, (syncValue: XwF036isJdONMsbpRxIVJxmz7LqX9i45)'
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:completion:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
2017-07-13 07:40:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:724A47F8-A6A9-4ACB-88A5-C246773D2521:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "724A47F8-A6A9-4ACB-88A5-C246773D2521", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0)
[ThaliCore] Session.disconnect() peer:660CEBE9-D97,0-4CC3-8112-DBD0DF36D4CE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:660CEBE9-D970-4CC3-8112-DBD0DF36D4CE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "660CEBE9-D970-4CC3-8112-DBD0DF36D4CE", genera,tion: 0)
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XwF036isJdONMsbpRxIVJxmz7LqX9i45","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'XwF036isJdONMsbpRxIVJxmz7LqX9i45', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,07:40:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"660CEBE9-D970-4CC3-8112-DBD0DF36D4CE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F7974F8D-9A8D-4B97-8930-80FC4382D89E (syncValue: oQ8Aos4,qu9tHddoIg7NTPGpxrp3fIPS6)'
2017-07-13 07:40:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49349
2017-07-13 07:40:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oQ8Aos4qu9tHddoIg7NTPGpxrp3fIPS6",,"error":null,"portNumber":49349}'
2017-07-13 07:40:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oQ8Aos4qu9tHddoIg7NTPGpxrp3fIPS6', error: 'null', listeningPort: '49349''
,Connecting to the localhost:49349
Connecting to the localhost:49349
Connecting to the localhost:49349
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
Connected to the localhost:49349
Connected to the localhost:49349
C,onnected to the localhost:49349
,ok 109 correct string length
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 110 correct string length
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 07:40:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
ok 113 got the same, data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,ok 114 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3]
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49349
[ThaliCore] Session.disconnect() peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,2017-07-13 07:40:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 07:40:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 07:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-13 07:40:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E
,# setup
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 07:40:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 07:40:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 07:40:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:652433DE-F049-45A3-95C3-0B1092E6E918
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7D196FBD-5AAD-443C-AD66-7DA180562C2B
,[ThaliCore] Browser.startListening
,2017-07-13 07:40:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 07:40:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
2017-07-13 07:40:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","generation":0}'
2017-07-13 07:40:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D20CF0E0-AB62-41C0-B39B-9E536E7B86A5, (syncValue: z9xB3UTqfawfBf5STMgt6dfcPY4cvYFb)'
2017-07-13 07:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D20CF0E0-AB62-,41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7974F8,D-9A8D-4B97-8930-80FC4382D89E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,2017-07-13 07:40:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
2017-07-13 07:40:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D8525647-2B71-4074-8257-C803B73ABEF2","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:652433DE-F049-45A3-95C3-0B1092E6E918:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9717CC7E-1822-4393-B532-B06F5A7A59A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9717CC7E-1822-4393-B532-B06F5A7A59A4", generation: 0)
2017-07-13 07:40:43 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9717CC7E-1822-4393-B532-B06F5A7A59A4","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", genera,tion: 0)
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z9xB3UTqfawfBf5STMgt6dfcPY4cvYFb","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'z9xB3UTqfawfBf5STMgt6dfcPY4cvYFb', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D20CF0E0-AB62-41C0-B39B-9E536E7B86A5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F7974F8D-9A8D-4B97-8930-80FC4382D89E (syncValue: EGqHD9U,qAlnKbYqnkbYpy1xEH5ppqfSJ)'
2017-07-13 07:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D20CF0E0-AB62-41C0-B39B-9E536E7B86A5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D20CF0E0-AB62-41C0-B39B-9E536E7B86A5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A
[ThaliCore] Advertiser: session connected Peer(uuid: "652433DE-F049-45A3-95C3-0B1092E6E918", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946
[ThaliCore] Advertiser: session connected Peer(uuid: "652433DE-F049-45A3-95C3-0,B1092E6E918", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,2017-07-13 07:40:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EGqHD9UqAlnKbYqnkbYpy1xEH5ppqfSJ","error":"Connection could not be established","portNumber":null}'
2017-07-13 07:40:54 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: 'EGqHD9UqAlnKbYqnkbYpy1xEH5ppqfSJ', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-13 07:40:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 07:40:54 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 07:40:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F7974F8D-9A8D-4B97-8930-80FC4382D89,E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 07:40:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 07:40:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 07:40:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D8525647-2B71-4074-8257-C803B73ABEF2 (syncValue: MCRObQwdjhJ7HxtsalJSz5ST3r0XotU1)'
,2017-07-13 07:40:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F7974F8D-9A8D-4B97-8930-80FC4382D89E:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F7974F8D-9A8D-4B97-8930-80FC4382D89E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946
,[ThaliCore] Session.session(_:peer:didChange:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A
[ThaliCore] Session.startOutputStream(with:) peer:B69838E5-3ACB-4957-AD24-2A06D0BAA49A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946
,[ThaliCore] Session.startOutputStream(with:) peer:C95F00F6-64B3-4ACD-9825-7E4BD2921946
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 3, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,Server received psk id: psk-id
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 07:40:56 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:5
[ThaliCore] Virtu,alSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 6]
,[ThaliCore] Session.session(_:peer:didChange:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D8525647-2B71-4074-8257-C803B73ABEF2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49364
2017-07-13 07:40:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MCRObQwdjhJ7HxtsalJSz5ST3r0XotU1","error":null,"portNumber":49364}'
2017-07-13 07:40:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MCRObQwdjhJ7HxtsalJSz5ST3r0XotU1', error: 'null', listeningPort: '49364''
,Connecting to the localhost:49364
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D8525647-2B71-4074-8257-C803B73ABEF2:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 3, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49364
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 07:40:57 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,# teardown
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 6]
,2017-07-13 07:40:57 - DEBUG CoordinatedClient: 'all tests completed'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-13 07:41:57 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 07:41:57 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can shift data securely, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest,.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
,    at timeoutTimeout@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-13 07:41:57 - ERROR CoordinatedClient: ',failed to run unit tests, platformName: 'ios''
,2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 07:43:51 - DEBUG CoordinatedClient: 'test client failed'
2017-07-13 07:43:51 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'Can sh,ift data securely', event: 'run_Can shift data securely', sent data: '[{"uuid":"7429bd2a-7ddd-4480-9dee-bcb66c6ea3bf"},{"uuid":"ac0e4d72-52ca-4ad2-9509-e84c7cd40172"},{"uuid":"26bb0a9c-78ae-475d-ae1e-25e4e9f16cba"}]', received data: '{"success":false}'', s,tack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5FEA,62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/socket.,i,o-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bun,dle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5FEA62B4-ABDA-429B-9FFD-DA3FBC5E2196/ThaliTest.app/www/jxcore/node_m,odules/component-emitter/index.js:131:7''
2017-07-13 07:43:51 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
