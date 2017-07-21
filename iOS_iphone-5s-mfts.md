#### Test 113351851f8c1845_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/583B358E-DD6E-47D6-B47A-6B05BF6CE4BD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/583B358E-DD6E-47D6-B47A-6B05BF6CE4BD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851f8c1845/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60744"
,(lldb)     command script import "/tmp/583B358E-DD6E-47D6-B47A-6B05BF6CE4BD/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:53:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6E95FE7E-6EFF-471E-ACB4-A99BABF724E2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6E95FE7E-6EFF-471E-ACB4-A99BABF724E2
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CDEF3DDA-7CD5-4503-B5F8-5F23F7999D4A
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B52FABBA-1240-4C10-B528-6DD2F1BB01BE
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DCC128FB-A7F4-4C4D-A762-6A08200E566A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DCC128FB-A7F4-4C4D-A762-6A08200E566A
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DCC128FB-A7F4-4C4D-A762-6A08200E566A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DCC128FB-A7F4-4C4D-A762-6A08200E566A", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-21 10:53:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
Total duration:  1.622179985046387
,2017-07-21 10:53:50 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-21 10:53:50 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DCC128FB-A7F4-4C4D-A762-6A08200E566A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DCC128FB-A7F4-4C4D-A762-6A08200E566A", generation: 0)
,2017-07-21 10:53:53 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 10:53:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 10:53:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 10:53:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 10:53:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 10:53:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 10:53:57 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 10:53:57 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 10:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:53:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:53:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 10:54:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 10:54:31 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 10:54:31 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 10:54:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 10:54:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 10:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 10:54:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 10:54:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 10:54:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-21 10:54:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-21 10:54:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 10:54:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 10:54:57 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 10:55:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 10:55:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84E1C517-B5A8-404C-BB82-320E5941949A
[ThaliCore] Browser.startListening
2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 10:55:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:55:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:17 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1655EE8E-B641-44C8-A822-75C0A117EA0B
[ThaliCore] Browser.startListening
2017-07-21 10:55:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:55:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 10:55:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:55:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:55:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:24 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:55:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:28 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF2D1A55-013B-4576-8903-6134D620F912", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DF2D1A55-013B-4576-8903-6134D620F912
2017-07-21 1,0:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DF2D1A55-013B-4576-8903-6134D620F912
,2017-07-21 10:55:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "342E9F2B-AD43-47F5-9EA3-A4D737ABA84F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:342E9F2B-AD43-47F5-9EA3-A4D737ABA84F
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "342E9F2B-AD43-47F5-9EA3-A4D737ABA84F", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:342E9F2B-AD43-47F5-9EA3-A4D737ABA84F
2017-07-21 1,0:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:342E9F2B-AD43-47F5-9EA3-A4D737ABA84F
[ThaliCore] Advertiser.stopAdvertising() peerID:342E9F2B-AD43-47F5-9EA3-A4D737ABA84F,
2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFC46F12-BB3B-4698-909C-4C2A69860CF7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CFC46F12-BB3B-4698-909C-4C2A69860CF7
2017-07-21 10:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:32, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DC13C39-A6EA-431A-B8B8-7E066F2E68F3
[ThaliCore] Browser.startListening
2017-07-21 10:55:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
,2017-07-21 10:55:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFC46F12-BB3B-4698-909C-4C2A69860CF7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFC46F12-BB3B-4698-909C-4C2A69860CF7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E7E89EFF-C927-4E61-88A8-AA1DF588DD01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E7E89EFF-C927-4E61-88A8-AA1DF588DD01", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C698F9B2-FB30-44D1-8818-CDAB79F25800:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C698F9B2-FB30-44D1-8818-CDAB79F25800", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:55:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:55:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CFC46F12-BB3B-4698-909C-4,C2A69860CF7
2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9322C209-D516-4AC3-B9B3-B33D7BDE94FF
2017-07-21 1,0:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44D1EA29-09FD-4DAF-A03B-8BB0AB5D04C4
[ThaliCore] Browser.startListening
2017-07-21 10:55:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 10:55:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","generation":0}'
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5964CC8A-CCBB-402E-9185-5196A4325050 (syncValue: vXCoum1k6WEqB9NzSyBdQ2PQDt3PdfcQ)'
,2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C
[ThaliCore] Advertiser: session connected Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0
[ThaliCore] Advertiser: session connected Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0 state: notConnected -> connecting
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"pe,erIdentifier":"CAF20AEF-B7EE-4000-B50D-44CEEEB61EDB","generation":0}'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:55:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9322C209-D516-4AC3-B9B3-B33D7BDE94FF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58187
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vXCoum1k6WEqB9NzSyBdQ2PQDt3PdfcQ","error":null,"portNumber":58187}'
,2017-07-21 10:55:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vXCoum1k6WEqB9NzSyBdQ2PQDt3PdfcQ', error: 'null', listeningPort: '58187''
,2017-07-21 10:55:43 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2CD3522-16CA-4752-8390-CCEA2E5E035C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9322C209-D516-4AC3-B9B3-B33D7BDE94FF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0
2017-07-21 10:55:4,3 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType",:"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9322C209-D516-4AC3-B9B3-B33D7BDE94FF
2017-07-2,1 10:55:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:55:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:5964CC8A-CCBB-402E-9185-5196A4325050
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58187
[ThaliCore] Session.disconnect() peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:EB1B9D40-B842-46BA-8EE0-88D3C99582B0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:84A788E4-46FC-43D7-85F3-930F387C1ABA
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E054CB27-C059-42DF-A078-AA7174A3B4AD
,[ThaliCore] Browser.startListening
,2017-07-21 10:55:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:55:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5964CC8A-CCBB-402E-9185-5196A4325050 (syncValue: I2R74H2fhxIbHZcY1tsGw2YXTjk6wqlS)'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84A788E4-46FC-43D7-85F3-930F387C1ABA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2DA78DBA-B755-423F-8440-7648D04FC359
[ThaliCore] Advertiser: session connected Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2DA78DBA-B755-423F-8440-7648D04FC359 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
2017-07-21 10:55:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8AC415B6-21AD-403C-9EBA-E6A7204A5D5F","generation":0}'
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:55:45 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", g,eneration: 0)
2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","generation":0}'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,64CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,964CC8A-CCBB-402E-9185-5196A4325050", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2DA78DBA-B755-423F-8440-7648D04FC359
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DA78DBA-B755-423F-8440-7648D04FC359 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2DA78DBA-B755-423F-8440-7648D04FC359
[ThaliCore] Session.startOutputStream(with:) peer:2DA78DBA-B755-423F-8440-7648D04FC359
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 10:55:48 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,64CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,964CC8A-CCBB-402E-9185-5196A4325050", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,64CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,964CC8A-CCBB-402E-9185-5196A4325050", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5964CC8A-CCBB-402E-9185-5196A4325050:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:59,64CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5964CC8A-CCBB-402E-9185-5196A4325050", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5964CC8A,-CCBB-402E-9185-5196A4325050 error: max retries exceeded
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"I2R74H2fhxIbHZcY1tsGw2YXTjk6wqlS","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'I2R74H2fhxIbHZcY1tsGw2YXTjk6wqlS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5964CC8A-CCBB-402E-9185-5196A4325050","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:55:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:55:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8AC415B6-21AD-403C-9EBA-E6A7204A5D5F (syncValue: Lv7z7NZBpO6rhxsU7zRyaZLLO5w0g88I)'
,2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0) creating a new relay
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:172CA5F3-63C9-4F4,2-9246-81D93ED61B0B
[ThaliCore] Advertiser: session connected Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.sessio,n(_:peer:didChange:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B state: notConnected -> connecting
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] Se,ssion.init(session:identifier:connected:notConnected:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017,[ThaliCore] Session.deinit peer:5964CC8A-CCBB-402E-9185-5196A4325050:0
[ThaliCore] BrowserRelay.deinit
-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:55:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B
,[ThaliCore] Session.session(_:peer:didChange:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B
[ThaliCore] Session.startOutputStream(with:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8AC415B6-21AD-403C-9EBA-E6A7204A5D5F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58195
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lv7z7NZBpO6rhxsU7zRyaZLLO5w0g88I","error":null,"portNumber":58195}'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Lv7z7NZBpO6rhxsU7zRyaZLLO5w0g88I', error: 'null', listeningPort: '58195''
,Connecting to the localhost:58195
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
,Connected to the localhost:58195
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:3
# teardown
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2]
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 10:55:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 10:55:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:55:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:84A788E4-46FC-43D7-85F3-930F387C1ABA
2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58195
[ThaliCore] Session.disconnect() p,eer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B
,[ThaliCore] Session.session(_:peer:didChange:) peer:2DA78DBA-B755-423F-8440-7648D04FC359 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "84A788E4-46FC-43D7-85F3-930F387C1ABA", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:8AC415B6-21AD-403C-9EBA-E6A7204A5D5F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:55:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 10:55:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:62EDF300-F62B-48E1-984D-71A5F52E35C1
,2017-07-21 10:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:56:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0E082915-1D5D-44C6-9131-F37022463E75
,[ThaliCore] Browser.startListening
,2017-07-21 10:56:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:56:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:56:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:172CA5F3-63C9-4F42-9246-81D93ED61B0B
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","generation":0}'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C6A107A9-3C3D-474E-BE7A-580D8B57BEF0 (syncValue: g6L7gkp4SFbncFqXZc82EYc8FOYBJsAd)'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62EDF300-F62B-48E1-984D-71A5F52E35C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC583801","generation":0}'
2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C6A107A9-3C3D-474E-BE7A-580D8B57BEF0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C6A107A9,-3C3D-474E-BE7A-580D8B57BEF0 error: max retries exceeded
2017-07-21 10:56:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"g6L7gkp4SFbncFqXZc82EYc8FOYBJsAd","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:56:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'g6L7gkp4SFbncFqXZc82EYc8FOYBJsAd', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:56:12 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 10:56:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C6A107A9-3C3D-474E-BE7A-580D8B57BEF0","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 10:56:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 10:56:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86 (syncValue: 8LVNv3S,eCqUIPezig0Wh3L9cMoy0gxZ2)'
2017-07-21 10:56:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F0C64DD8-128D,-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C6A107A9-3C3D-474E-BE7A-580D8B57BEF0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
[ThaliCore] Advertiser: session connected Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] Advertiser: session connected Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7FD124B6-9004-4F01-855D-07531362FDF7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58211
,2017-07-21 10:56:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8LVNv3SeCqUIPezig0Wh3L9cMoy0gxZ2","error":null,"portNumber":58211}'
,2017-07-21 10:56:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '8LVNv3SeCqUIPezig0Wh3L9cMoy0gxZ2', error: 'null', listeningPort: '58211''
,Connecting to the localhost:58211
,Connecting to the localhost:58211
,Connecting to the localhost:58211
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,Connected to the localhost:58211
,Connected to the localhost:58211
,Connected to the localhost:58211
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F0C64DD8-12,8D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 10:56:15 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,ok 95 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 []
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
,[ThaliCore] Session.session(_:peer:didChange:) peer:7FD124B6-9004-4F01-855D-07531362FDF7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] Session.startOutputStream(with:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] Session.startOutputStream(with:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] Session.startOutputStream(with:) peer:7FD124B6-9004-4F01-855D-07531362FDF7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (8831 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
[ThaliCore] Session.session(_:peer:didChange:) pee,r:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5 state: connecting -> connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [8, 9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 3r16hFc87RzOAvN8g1jBkL984O01lhBLDAA3fYO5Qf6jBZcatCvirnoigUM2SaY0XVxJMBdCdu5rfcv4Tv8UrezcXMzMvKrhAlZHf3NAyNBkdR2kkhD2CDJYrAeJJc2Jl5kKUUV47roevE0DnN8Bm6RQJ5xtUZlsWLoNELC5yLRLRRZXDC,C2nwOjKpw4uT2bxnIEaiVzd0bixEGsDo1QdW585GRit67EEdMdQPRst1qRJRg4PFgBghcg2Eyi8B9rITjIlDlrSaYmXXSH1QZbnuoSZLIVgvLrJ9A1Q6sSJgjkfTn4aX1drGiEMvl9EUsnigzm7iqrHsrtfQWqWpBWoyj9yLHk6zeX2ZQAonunyI9iO9IITpzMaXj9KJXwkPMdOg5zYZKuDppA4L9i06BcpwYLsckXrPRMVdZmamsTlBkxMRdn55,fiHuvY1oWY404s0BjqclVavh2411hEV6jeuF1ZbBXJjT8acLfkXT9qQvNqVKtaohd6myYEnfRJCUOSVWLUDsn7cgee7IIlOsjoc8GU82ETi93UeQx9LMM1CSl8qCC8zmPJdlzWFgreFSRkTxQdE6lKabz1AxByWu6wAmKNHNn75pgveLbVOK0P5HivQW8sISByuSEJdRqOlpgzVKB40JBbkzLbXBOQot3mpWPdLEP77Bp5vhO0bNnzX3DBeGStiZ,dxevxUJCCyOUHEqf1FVruOoSzQraYfIh0oQ4CaSclvt1arSc3ICj8tpGwW8jGHpwd4S1SvAGOIsWzJwGXPvaM1YrXjVfPoD8a3qOgAuMg6gNdUVLdobT8hbWXRZpyzDaHibZEYBgFZGVeMSBKTBUZ7u57E9aawkeTww7j6BoiKwwhYqCEjbRAnrXxgFxi1dzMefRe8pTY3ObzQwEEnf5VaMLDoSLOzYJxCEwcBVe9rmlYejFSdXj8OBR13IVYxyL,ywvd4hezO3Dv8aCoZV98sV3qrpsf2ApvTYQDpF7NZ7A3gSLWwuYgFjvTEqcuSjxZhCd6NtBSAVn6omNSf3VdHxiw1CTYc3PyhZiIGXvaDl8p5tYW4nyxyQsIDSxT1kNHWJ7rBG8jnBG8kMQPEyOOiLB7gFY4ocFbxpJLHuQFIaePT1nOXtyE5HQ8psWSfh4lNE5veZxZJ4DuWdL4ZrEyvwKP126LGY11kqzvGMpeAuazEZwB2uT6gtlLIlFioS8v,eGDdDAcEAbnqejK2kZFzs1gUyrcu884q6oegIHKWD4jhCgbyDaR0PAJlcPp08DkU1esGHDrkYPlxigDjxNtfCZYlHOGvsDxlh6HrUvb8UBg4TNzOdatiSlaXarFA1dP0f3QvYhliQS3SsBvIFGzmU3shIkO5odWAeDHVffdwoyCnyJvGnXUPnUG9v085NlBlZFgOEQLiD5KU1o8vzv4H1ZOZrgEEruubVhSnbPVT4lYp2y6rwDuzzr3w8tiMKPEu,zbZP3m7R5wGq6aupBBwgyD92vURNX25G9OQNvXQ375KaDiugRi85qSifwpIHs00TDYO3ZDzTM0bgyRIcjq9JtdIGzmTFJtVcnQUks85Q8hNgpGm2i3QJ5PP5c4okVQZEexJhtVJFss8IeOMnbXWJA6lnIImc4N28e7JJohhiazhqy5fXPjKKuEfvRiyCgYf5Ea4pqosp7gn6VWGJaWulwOSaB9lY6Huk3W7AKpowLWQ89f6l8gPJ1MF3elUIO579,TzpiPYxbTNtkU2qq5ygksBPYNZmXkDG8W0GXDLRhzTwYWmXF05U32Gx0PCYGE04dRzPdnpI7rrdRPi4b4nSsdkGM0fX52nPJlz6AEswYxbqE7wVTD8gQCx2Xk9pZhUVNzQ21aqTLTvYo4gR6mnDTBJdmpHECk9b34OkkLshC1Ftle7RktbQGuNoqanlBMz3QCLR3KBzAxA0d91qxUcbrfLxwCla2kPbVPHjsfMEPihFsHknzqLrBeIwgTtWQhmmP,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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'
2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (1638,4 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
[ThaliCore] Session.startOutputStream(with:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
[ThaliCore] Session.startOutputStream(with:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
[ThaliCore] Session.startOutputStream(with:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [10, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (6529 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 10:56:18 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [11, 12]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:11 [12]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:12 []
,2017-07-21 10:56:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:62EDF300-F62B-48E1-984D-71A5F52E35C1
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58211
[ThaliCore] Session.disconnect() p,eer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6AA19F75-D6A3-4775-BB75-F9DD442CCAF5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "62EDF300-F62B-48E1-984D-71A5F52E35C1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7FD124B6-9004-4F01-855D-07531362FDF7
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:7FD124B6-9004-4F01-855D-07531362FDF7
[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C
,2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAd,vertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2802489A-F04F-493C-B788-CCEF365DA525
[ThaliCore] Browser.startListening
2017-07-21 10:56:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":true,"advertisingActive":true}'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:56:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
2017-07-21 10:56:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC583801","generation":0}'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C6E0D61B-5C67-46BA-BD6E-1062AC583801, (syncValue: R3ChkoX70HbSURfy5Zoh3bf72I2xzl91)'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC5,83801", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
2017-07-21 10:56:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","generation":0}'
2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
2017-07-21 10:56:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","generation":0}'
,2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","generation":0}'
2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C6,E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C6E0D61B-5C67-46BA-BD6E-1062AC583801", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"R3ChkoX70HbSURfy5Zoh3bf72I2xzl91","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'R3ChkoX70HbSURfy5Zoh3bf72I2xzl91', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 10:56:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC583801","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:25 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 10:56:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C6E0D61B-5C67-46BA-BD6E-1062AC58380,1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 10:56:25 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:25 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86 (syncValue: lQvDFGgvjrRhV49saQeF2GH,j5Wk8lIKy)'
2017-07-21 10:56:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F0C64DD8-128D-45A0-B3D4-36BE8,B3AAC86:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C6E0D61B-5C67-46BA-BD6E-1062AC583801:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F0,C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lQvDFGgvjrRhV49saQeF2GHj5Wk8lIKy","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lQvDFGgvjrRhV49saQeF2GHj5Wk8lIKy', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:28 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FDC5DDB-7B8C-46BB-9035-E7915D9CA128 (syncValue: jkbgTqq7dnToQCaKPw6DonHHeWI7Z1H3)'
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F0C64DD8-128D-45A0-B3D4-36BE8B3AAC86:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
[ThaliCore] Advertiser: session connected Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58233
2017-07-21 10:56:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jkbgTqq7dnToQCaKPw6DonHHeWI7Z1H3",,"error":null,"portNumber":58233}'
2017-07-21 10:56:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jkbgTqq7dnToQCaKPw6DonHHeWI7Z1H3', error: 'null', listeningPort: '58233''
,Connecting to the localhost:58233
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B state: connecting -> connected
,Connected to the localhost:58233
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
[ThaliCore] Session.startOutputStream(with:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 10:56:35 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:14 [13]
,2017-07-21 10:56:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58233
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4DCC7E8D-628B-41A5-9B46-C0A2FAFCD93C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jkbgTqq7dnToQCaKPw6DonHHeWI7Z1H3","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
,[ThaliCore] Session.deinit peer:45BB0A59-DDD2-4E70-A7A6-C155709B070B
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B
,2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84651C3B-9AC1-4BF8-B558-49D4721AB6C9
[ThaliCore] Browser.startList,ening
2017-07-21 10:56:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:56:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:56:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:839E6042-1808-4159-8923-FD521909AFE8:0
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9BD2EEC5-BC28-4301-8B46-0C2C7D945274 (syncValue: ScNPAwiod8TdIBxlDM6P44VwPzlRvqHd)'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9B,D2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","generation":0}'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"839E6042-1808-4159-8923-FD521909AFE8","generation":0}'
,2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F287E759-9DEE-41EC-A28C-0C2B4889AF65:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F287E759-9DEE-41EC-A28C-0C2B4889AF65", generation: 0)
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F287E759-9DEE-41EC-A28C-0C2B4889AF65","generation":0}'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,D2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9B,D2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9BD2EEC5-BC28-4301-8B46-0C2C7D945274", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:56:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ScNPAwiod8TdIBxlDM6P44VwPzlRvqHd","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ScNPAwiod8TdIBxlDM6P44VwPzlRvqHd', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:56:43 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9BD2EEC5-BC28-4301-8B46-0C2C7D945274","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3FDC5DDB-7B8C-46BB-9035-E7915D9CA128 (syncValue: KCj2NpbpKR5birjxJrzRk0R,aaEUHJFbx)'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915,D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:56:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9BD2EEC5-BC28-4301-8B46-0C2C7D945274:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,DC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
[ThaliCore] Advertiser: session connected Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Session.session(_:peer:,didChange:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
[ThaliCore] Session.startOutputStream(with:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [13, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> notConnected
2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
[ThaliCore] BrowserRelay.closeRelay() state:,connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F,DC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (426 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (23694 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received (25417 bytes):'
,2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 10:56:48 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,DC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,DC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3FDC5DDB-7B8C-46BB-9035-E7915D9CA128", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3FDC5DDB,-7B8C-46BB-9035-E7915D9CA128 error: max retries exceeded
2017-07-21 10:56:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KCj2NpbpKR5birjxJrzRk0RaaEUHJFbx","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 10:56:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KCj2NpbpKR5birjxJrzRk0RaaEUHJFbx', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 10:56:53 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3FDC5DDB-7B8C-46BB-9035-E7915D9CA128","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:56:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 839E6042-1808-4159-8923-FD521909AFE8 (syncValue: ZlZXmXT5KegwVTU3wIlRLem2ThgTJYnS)'
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3FDC5DDB-7B8C-46BB-9035-E7915D9CA128:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:56:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:839E6042-1808-4159-8923-FD521909AFE8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:839E6042-1808-4159-8923-FD521909AFE8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58255
,2017-07-21 10:56:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZlZXmXT5KegwVTU3wIlRLem2ThgTJYnS","error":null,"portNumber":58255}'
,2017-07-21 10:56:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZlZXmXT5KegwVTU3wIlRLem2ThgTJYnS', error: 'null', listeningPort: '58255''
,Connecting to the localhost:58255
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
,Connected to the localhost:58255
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [13, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:56:56 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 10:56:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 102 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:16 [13, 15]
,# teardown
,2017-07-21 10:56:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:839E6042-1808-4159-8923-FD521909AFE8
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58255
[ThaliCore] Session.disconnect() p,eer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0FDE9EDA-3925-4EEE-8C07-B82DDC023D3B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:839E6042-1808-4159-8923-FD521909AFE8:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] Session.deinit peer:1E7674A5-17B5-4B49-88C4-15FB4BEDF34A
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:56:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:56:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1
2017-07-21 1,0:57:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1FF19309-D3AE-4CF5-8B09-84B75BBD458A
[ThaliCore] Browser.startListening
2017-07,-,21 10:57:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:57:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:57:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06887905-6ACD-4B62-BBB9-4BB2FDAC62C3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06887905-6ACD-4B62-BBB9-4BB2FDAC62C3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49486435-1B49-404F-8A95-D65FB54627D3:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "49486435-1B49-404F-8A95-D65FB54627D3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:839E6042-1808-4159-8923-FD521909AFE8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "839E6042-1808-4159-8923-FD521909AFE8", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0D7C3221-280B-4FF5-8FC8-0F4B9059DAA1
,2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:57:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 10:57:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E08A6A3E-04D6-4E12-999D-ACE4C1E06134
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD9C0DAB-C6A4-4507-9103-2AFF19707AF1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD9C0DAB-C6A4-4507-9103-2AFF19707AF1
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 111 discoveryActive should be false
ok 112 advertisingActive should be tr,ue
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD9C0DAB-C6A4-4507-9103-2AFF19707AF1
,ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobi,leNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 10:57:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 10:57:06 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 10:57:07 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:b29e2ac6-86ef-41b0-a255-65aea2b75b76 error: startListeningNotActive
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J3hW8ROuaTI4yYxeOuuEEaVdCq1wmF71","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b29e2ac6-86ef-41b0-a255-65aea2b75b76","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b29e2ac6-86ef-41b0-a255-65aea2b75b76","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6C99420A-BA35-4799-AF84-CFA47ACD6158
[ThaliCore] Browser.startListening
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on star,ting
ok 134 Got null as expected
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aYh0KBaVWRYoalF85JjiLXtxcLKe0zpI","error":"Illegal peerID","portNumber":null}'
ok 135 Should only get called after multiConnect returned
ok 136 SyncValue matches
,ok 137 Got right error
ok 138 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 10:57:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:86CF16E2-EC81-459D-B1EF-B3C0E5D3B0FF
[ThaliCore] Browser.startListening
2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:57:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:5ccb2345-2a33-45c4-8e01-0a27def64059
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA
2017-07-21 1,0:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 143 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C4F4C6EC-1245-479D-9812-A32327ECFD8A
,[ThaliCore] Browser.startListening
,2017-07-21 10:57:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
2017-07-21 10:57:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","generation":0}'
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18A68881-1F66-4E2F-A9A0-409648231FCA (syncValue: ME5RpP5BfbbMXnMzHqRT0WkLbcqlDjlm)'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","generation":0}'
2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58262
2017-07-21 10:57:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ME5RpP5BfbbMXnMzHqRT0WkLbcqlDjlm",,"error":null,"portNumber":58262}'
2017-07-21 10:57:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ME5RpP5BfbbMXnMzHqRT0WkLbcqlDjlm', error: 'null', listeningPort: '58262''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
ok 145 Got null as expected
[ThaliCore] BrowserManager.co,nnectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) found active relay
,2017-07-21 10:57:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wt09rrypAm0UkpcciXvmOoFHzIz8pgzg","error":null,"portNumber":58262}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [13, 15, 17]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) found active relay
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:57:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HKa5VeezqXSlSczeGyppN0xOFLYScv8d","error":null,"portNumber":58262}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
[ThaliCore] Advertiser: session connected Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
[ThaliCore] Session.startOutputStream(with:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [13, 15, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 10:57:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeS,treams() vsID:18
57:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:18A68881-1F66-4E2F-A9A0-409648231FCA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58262
[ThaliCore] VirtualSocket.closeStr,eams() vsID:17
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [13, 15, 17]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] Session.disconnect() peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:17 [13, 15]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] Bro,wserRelay.deinit
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "49FFE25D-37F9-42F8-A3F5-EE8F17EC34AA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
,[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,[ThaliCore] Session.deinit peer:BD6C4CC2-84DF-43FC-8938-C7C49680F3EF
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 10:57:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 10:57:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 10:57:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:57:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'listening 58266'
,ok 151 Should throw
,# teardown
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:27 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58268'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58271'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'listening 58275'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 58280'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'listening 58284'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58288'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58292'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'listening 58296'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 10:57:30 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 10:57:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 58348'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'listening 58352'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 195 serversManager must not be null
ok 196 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 197 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 58355'
ok 198 port must be in range
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:33 - DEBUG createNativeListener: 'listening 58356'
ok 199 second start should return same port
,# teardown
,2017-07-21 10:57:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'listening 58358'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 200 we should be connected
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-07-21 10:57:34 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 58360
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:57:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:57:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06D0FB89-E071-47C1-A098-41347350B3A8
[ThaliCore] Browser.startListening
,2017-07-21 10:57:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:57:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,ok 211 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","generation":0}'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 18A68881-1F66-4E2F-A9A0-409648231FCA (syncValue: rxz8Dwz7uhc5oGQYtodrFqZ9lgTOyDB9)'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9","generation":0}'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
2017-07-21 10:57:35 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","generation":0}'
2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:35 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:57:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
2017-07-21 10:57:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","generation":0}'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F57FE8F-78CD-4184-9A0D-D2B4640C9ED9", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:18,A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,8A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "18A68881-1F66-4E2F-A9A0-409648231FCA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rxz8Dwz7uhc5oGQYtodrFqZ9lgTOyDB9","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rxz8Dwz7uhc5oGQYtodrFqZ9lgTOyDB9', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"18A68881-1F66-4E2F-A9A0-409648231FCA","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:40 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ACEDB61A-DE2E-4167-AED9-3A55C192CFAF (syncValue: tgzRhHnYMbP0mi21oTBtiA5,XLsjWfD9n)'
2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 10:57:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:18A68881-1F66-4E2F-A9A0-409648231FCA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232
[ThaliCore] Advertiser: session connected Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58370
2017-07-21 10:57:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tgzRhHnYMbP0mi21oTBtiA5XLsjWfD9n",,"error":null,"portNumber":58370}'
2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tgzRhHnYMbP0mi21oTBtiA5XLsjWfD9n', error: 'null', listeningPort: '58370''
,ok 212 should be equal
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7C3D7BAF-2475-406D-A529-BAFFF20512EB (syncValue: OwrdzWvsjZC1xwwr9GKlV268Trc6UV5N)'
,2017-07-21 10:57:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7C,3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
[ThaliCore] Advertiser: session connected Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232
,[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58374
,2017-07-21 10:57:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OwrdzWvsjZC1xwwr9GKlV268Trc6UV5N","error":null,"portNumber":58374}'
,2017-07-21 10:57:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OwrdzWvsjZC1xwwr9GKlV268Trc6UV5N', error: 'null', listeningPort: '58374''
,ok 213 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
,[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:57:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58370
,[ThaliCore] Session.disconnect() peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D538D25B-4837-4E0A-920D-A933F5A48F3B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.c,loseRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58374
[ThaliCore] Session.disconnect() peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] Browser: session notConnected fire notification for, Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB
2017-07-21 10:57:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
[ThaliCore] Session.session(_:peer:didChange:) peer:0D133F74-EC2E-4B96-A318-6FC3B07FF232 state: connected -> notConnected
[ThaliCore] Advertiser: session n,otConnected Peer(uuid: "ED6CFA85-1D6F-4A9C-AF83-CBE3587A10C3", generation: 0)
2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:D538D25B-4837-4E0A-920D-A933F5A48F3B
,# setup
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OwrdzWvsjZC1xwwr9GKlV268Trc6UV5N","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:57:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 58376
,ok 214 should be equal
,ok 215 should be equal
,ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:57:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:57:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:57:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5CF26575-49BF-4D5C-BE65-95FBD5115ED6
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:57:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4931A5EF-19CB-4D3A-ACD4-6195FBE307AC
,[ThaliCore] Browser.startListening
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:57:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:57:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
2017-07-21 10:57:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","generation":0}'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ACEDB61A-DE2E-4167-AED9-3A55C192CFAF, (syncValue: ymAYNRMShEqPkVFdvuz3H9Ern1dvDCLq)'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C19,2CFAF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7C3D7BAF-2475-406D-A529-BAFFF20512EB","generation":0}'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}'
,2017-07-21 10:57:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 10:57:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5CF26575-49BF-4D5C-BE65-95FBD5115ED6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AC,EDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,CEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7C3D7BAF-2475-406D-A529-BAFFF20512EB:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7C3D7BAF-2475-406D-A529-BAFFF20512EB", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AC,EDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,CEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ACEDB61A-DE2E-4167-AED9-3A55C192CFAF", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:57:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ymAYNRMShEqPkVFdvuz3H9Ern1dvDCLq","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:57:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ymAYNRMShEqPkVFdvuz3H9Ern1dvDCLq', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:57:57 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:57:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 10:57:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"ACEDB61A-DE2E-4167-AED9-3A55C192CFAF","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 10:57:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:57:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 10:57:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 86190841-1E2B-499E-89FF-674E5A3AF1A8 (syncValue: atm8HJvTckH7j3s38ULwXXW,zXqtv06j7)'
2017-07-21 10:57:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86190841-1E2B-499E-89FF-674E5,A3AF1A8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:57:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:ACEDB61A-DE2E-4167-AED9-3A55C192CFAF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58390
,2017-07-21 10:58:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"atm8HJvTckH7j3s38ULwXXWzXqtv06j7","error":null,"portNumber":58390}'
,2017-07-21 10:58:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'atm8HJvTckH7j3s38ULwXXWzXqtv06j7', error: 'null', listeningPort: '58390''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-07-21 10:58:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93A0D9D1-6F45-4D45-8431-EC83225FE394 (syncValue: tybd9VAxSlqCNVDQFv43CQPJiU7CHP7k)'
,2017-07-21 10:58:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
[ThaliCore] Advertiser: session connected Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
[ThaliCore] Advertiser: session connected Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58397
2017-07-21 10:58:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tybd9VAxSlqCNVDQFv43CQPJiU7CHP7k",,"error":null,"portNumber":58397}'
,2017-07-21 10:58:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tybd9VAxSlqCNVDQFv43CQPJiU7CHP7k', error: 'null', listeningPort: '58397''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77
,[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
,[ThaliCore] Session.session(_:peer:didChange:) peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,10:58:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5CF26575-49BF-4D5C-BE65-9,5FBD5115ED6
2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:86190841-1E2B-499E-89FF-674E5A3AF1A8
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58390
[ThaliCore] Session.disconnect() p,eer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:16C21EA8-3BB0-4713-BED4-74947C1BFD77 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "5CF26575-49BF-4D5C-BE65-95FBD5115ED6", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
,[ThaliCore] Session.deinit peer:86EE609A-CE7D-42B6-AA31-49F7E0E4812F
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:93A0D9D1-6F45-4D45-8431-EC83225FE394
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58397
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:58:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tybd9VAxSlqCNVDQFv43CQPJiU7CHP7k","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58401'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58402'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9F5FE4CC-7294-4EA0-B791-DF224430A933
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:86190841-1E2B-499E-89FF-674E5A3AF1A8:0
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86190841-1E2B-499E-89FF-674E5A3AF1A8", generation: 0)
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:11 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}]'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","generation":0}'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'listening 58403'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B21A21E-CDA3-4750-89A9-D578FAA83C3C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8B21A21E-CDA3-4750-89A9-D578FAA83C3C
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B21A21E-CDA3-4750-89A9-D578FAA83C3C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:8B21A21E-CDA3-4750-89A9-D578FAA83C3C
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B21A21E-CDA3-4750-89A9-D578FAA83C3C
,[ThaliCore] Advertiser.stopAdvertising() peerID:8B21A21E-CDA3-4750-89A9-D578FAA83C3C
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'listening 58406'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 238 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 10:58:13 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 243 specific error expected
,# teardown
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 58407'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B050AA4C-A355-4546-B06B-C28357852A35
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "214A561C-A0F3-4272-A9B4-30DDC408BDA1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:214A561C-A0F3-4272-A9B4-30DDC408BDA1
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:214A561C-A0F3-4272-A9B4-30DDC408BDA1
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'listening 58410'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70D1EF90-7921-411E-BE17-6C805E3B1BC6
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A97F5AB2-F5ED-402D-A313-3B9557A721B0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A97F5AB2-F5ED-402D-A313-3B9557A721B0
,2017-07-21 10:58:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 10:58:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A97F5AB2-F5ED-402D-A313-3B9557A721B0
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'listening 58412'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:79BC53CC-2B1D-485C-89C9-3A50FBE18BD9
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D32FABF5-8BDA-4EEB-97EA-760405C2BECC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,D32FABF5-8BDA-4EEB-97EA-760405C2BECC
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D32FABF5-8BDA-4EEB-97EA-760405C2BECC
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10,:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:15 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 10:58:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 10:58:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 10:58:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 10:58:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 10:58:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58415'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:41684F19-840B-44F2-94F5-FD2CBD22B5E2
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
2017-07-21 10:58:19 - DEBUG thaliMobileNat,iveWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 27,3 advertisingActive matches
2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58416'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EE881980-CA74-4E23-BBE6-9163FB287C65", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EE881980-CA74-4E23-BBE6-9163FB287C65
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 10:58:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EE881980-CA74-4E23-BBE6-9163FB287C65
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 276 discoveryActive matches
,ok 277 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'listening 58418'
,# teardown
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'listening 58419'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:56D12911-8D55-49D5-8E91-47EEFD3A27E0
[ThaliCore] Browser.st,artListening
2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45E7D383-8196-4EB7-945B-FA5CF0BF7F6A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45E7D383-8196-4EB7-945B-FA5CF0BF7F6A
,2017-07-21 10:58:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 279 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3", generation: 0)
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","generation":0}]'
2017-07-21 10:58:21 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:45E7D383-8196-4EB7-945B-FA5CF0BF7F6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "45E7D383-8196-4EB7-945B-FA5CF0BF7F6A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0718B333-9577-4BCF-9755-AE8E652E9BC9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0718B333-9577-4BCF-9755-AE8E652E9BC9", generation: 0)
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","generation":0}]'
2017-07-21 10:58:21 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","generation":0}'
,2017-07-21 10:58:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:45E7D383-8196-4EB7-945B-FA5CF0BF7F6A
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 10:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 284 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'listening 58421'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:71C3A9AE-75DD-4D87-AF39-0D0785A798F9
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:926130BD-656F-4D54-AF29-33CBA7483320
,2017-07-21 10:58:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 10:58:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
2017-07-21 10:58:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93A0D9D1-6F45-4D45-8431-EC83225FE39,4 (syncValue: ccKThqjKT7cXM3pilgF0fJMGpLqNwF11)'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC8322,5FE394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
2017-07-21 10:58:24 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}]'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","generation":0}'
,2017-07-21 10:58:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:24 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 10:58:24 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:926130BD-656F-4D54-AF29-33CBA7483320:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "926130BD-656F-4D54-AF29-33CBA7483320", generation: 0)
,2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
,2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}]'
2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","generation":0}'
,2017-07-21 10:58:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-21 10:58:26 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,A0D9D1-6F45-4D45-8431-EC83225FE394:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93A0D9D1-6F45-4D45-8431-EC83225FE394", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ccKThqjKT7cXM3pilgF0fJMGpLqNwF11","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 10:58:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ccKThqjKT7cXM3pilgF0fJMGpLqNwF11', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 10:58:27 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93A0D9D1-6F45-4D45-8431-EC83225FE394","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:93A0D9D1-6F45-4D45-8431-EC83225FE394
,2017-07-21 10:58:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 10:58:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73639C8-17E8-4A13-9D2F-6958AEDF8A1C (syncValue: k4Zdv7CZdf6kHX7kO5ZUUd6nd57u0R9r)'
,2017-07-21 10:58:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93A0D9D1-6F45-4D45-8431-EC83225FE394:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58428
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k4Zdv7CZdf6kHX7kO5ZUUd6nd57u0R9r","error":null,"portNumber":58428}'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'k4Zdv7CZdf6kHX7kO5ZUUd6nd57u0R9r', error: 'null', listeningPort: '58428''
,2017-07-21 10:58:30 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [13, 15, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:30 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:30 - DEBUG testUtils: 'Got end'
,ok 285 response body should match testData
,ok 286 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:926130BD-656F-4D54-AF29-33CBA7483320
2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 10:58:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 10:58:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-21 10:58:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:58428
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:19 [13, 15]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "B73639C8-17E8-4A13-9D2F-6958AEDF8A1C", generation: 0)
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k4Zdv7CZdf6kHX7kO5ZUUd6nd57u0R9r","error":"Session disconnected","portNumber":null}'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:B73639C8-17E8-4A13-9D2F-6958AEDF8A1C:0
,[ThaliCore] BrowserRelay.deinit
,# will fail bad PSK connection between peers
,ok 288 FIX ME, PLEASE!!!
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 290 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 10:58:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 291 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 10:58:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 10:58:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 292 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 293 specific error should be returned
,# teardown
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"86190841-1E2B-499E-89FF-674E5A3AF1A8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"82D348AA-5BD5-4D47-8814-DCA8EBEEF5A3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 10:58:33 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0718B333-9577-4BCF-9755-AE8E652E9BC9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 10:58:33 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B73639C8-17E8-4A13-9D2F-6958AEDF8A1C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'listening 58430'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 305 error should be null
,ok 306 error should be null
,# setup
,ok 307 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 58431'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C63E1538-5C04-4885-A9F6-57F258B28BB2
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
,ok 309 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
,ok 311 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 error should be null
,ok 313 error should be null
,# setup
,ok 314 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'listening 58432'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7B115725-9BC1-4463-BBB5-4EA31FA08681", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:7B115725-9BC1-4463-BBB5-4EA31FA08681
2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7B115725-9BC1-4463-BBB5-4EA31FA08681", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:7B115725-9BC1-4463-BBB5-4EA31FA08681
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 317 error should be null
ok 318 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7B115725-9BC1-4463-BBB5-4EA31FA08681
,[ThaliCore] Advertiser.stopAdvertising() peerID:7B115725-9BC1-4463-BBB5-4EA31FA08681
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-21 10:58:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 319 error should be null
,ok 320 error should be null
,# setup
,ok 321 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 58435'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 326 error should be null
,ok 327 error should be null
,# setup
,ok 328 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 10:58:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 329 This should not cause wifi to fail
,ok 330 native router should be bad
,# teardown
,ok 331 error should be null
,ok 332 error should be null
,# setup
,ok 333 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'listening 58436'
ok 334 first call should succeed
ok 335 first call should succeed
ok 336 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 337 error should be null
,ok 338 error should be null
,# setup
,ok 339 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 340 error should be null
ok 341 error should be null
,# setup
,ok 342 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 10:58:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 343 error should be null
ok 344 error should be null
,# setup
,ok 345 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7d843bbd-5de7-4778-9678-4e8bdee15ae8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 346 should be called once
ok 347 should not have been called more than once
,# teardown
,2017-07-21 10:58:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7d843bbd-5de7-4778-9678-4e8bdee15ae8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 348 error should be null
ok 349 error should be null
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
,2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6f49014c-d9a4-42e3-a320-81acfa3bbbfc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 356 peer should be available
,ok 357 cache contains native peer
,2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6f49014c-d9a4-42e3-a320-81acfa3bbbfc","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 358 peer should be unavailable
,ok 359 peer has been removed from cache
,# teardown
,ok 360 error should be null
,ok 361 error should be null
,# setup
,ok 362 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 363 we have not added peer to the cache yet
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a8281885-1825-462e-b9b2-ed3199f51ad6","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 364 peer should be available
ok 365 cache contains wifi peer
2017-07-21 10:58:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a8281885-1825-462e-b9b2-ed3199f51ad6","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 366 peer should be unavailable
,ok 367 peer has been removed from cache
,# teardown
,ok 368 error should be null
ok 369 error should be null
,# setup
,ok 370 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b6721de3-335d-4f11-ba0a-e160dd55804d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 371 first peer is a,vailable
2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb7b38f4-fb1e-4df6-880a-04be5a246b98","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 372 second, peer is available
ok 373 first and second peers are different
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b6721de3-335d-4f11-ba0a-e160dd55804d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bb7b38f4-fb1e-4df6-880a-04be5a246b98","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 374 error should be null
ok 375 error should be null
,# setup
,ok 376 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 377 should not be in cache at start
2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a5334c89-05b7-4827-8018-d852cefc73bb","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 378 peer is available
,# teardown
,2017-07-21 10:58:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a5334c89-05b7-4827-8018-d852cefc73bb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 379 error should be null
,ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 10:58:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 382 error should be null
ok 383 error should be null
,# setup
,ok 384 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 10:58:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 385 error should be null
ok 386 error should be null
,# setup
,ok 387 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c75c8fdf-fbfa-48ff-9c7a-a2745324da9b","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 388 peer should be ,available
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c75c8fdf-fbfa-48ff-9c7a-a2745324da9b","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 389 peer should be available
ok 390 should store correct generation
,# teardown
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c75c8fdf-fbfa-48ff-9c7a-a2745324da9b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 391 error should be null
ok 392 error should be null
,# setup
,ok 393 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 10:58:39 - DEBUG thaliMobileNativeWrapper: 'listening 58437'
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7df8d21b-23c5-4ddb-9a1a-fa70c49527e5","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,2017-07-21 10:58:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7df8d21b-23c5-4ddb-9a1a-fa70c49527e5","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7df8d21b-23c5-4ddb-9a1a-fa70c49527e5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 398 error should be null
,ok 399 error should be null
,# setup
,ok 400 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 58438'
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fe90fc8f-ccee-49db-9ab3-5ffbdb9a6d31","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 401 discovered available peer
,ok 402 peer is available
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fe90fc8f-ccee-49db-9ab3-5ffbdb9a6d31","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 403 error should be null
,ok 404 error should be null
,# setup
,ok 405 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f55a32bf-b93e-44de-bbaa-107c4dbba44b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 406 peer should be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f55a32bf-b93e-44de-bbaa-107c4dbba44b","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 407 peer should be unavailable
,ok 408 should be removed from cache
,# teardown
,ok 409 error should be null
,ok 410 error should be null
,# setup
,ok 411 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'listening 58439'
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f81b0276-4ba2-4063-891d-f46b7fc84ee3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 412 first peer is expected to be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b193b24b-73a4-43f6-a75f-7a0b87e2932d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 413 second peer is expected to be available
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b193b24b-73a4-43f6-a75f-7a0b87e2932d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 414 peer became unavailable
,ok 415 it was wifi peer
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b193b24b-73a4-43f6-a75f-7a0b87e2932d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 416 we found peer again
,ok 417 it was wifi peer
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b193b24b-73a4-43f6-a75f-7a0b87e2932d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 418 peer became unavailable
,ok 419 it was wifi peer
,# teardown
,2017-07-21 10:58:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f81b0276-4ba2-4063-891d-f46b7fc84ee3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 420 error should be null
,ok 421 error should be null
,# setup
,ok 422 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 10:58:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 423 error should be null
,ok 424 error should be null
,# setup
,ok 425 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'listening 58440'
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c43533ba-0eba-4ac3-bd09-5b149f02b6f0","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 426 first peer is expected to be available
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f1950f1a-8aac-4d6a-a630-4d80baffa0ae","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 427 second peer is expected to be available
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c43533ba-0eba-4ac3-bd09-5b149f02b6f0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 428 peer became unavailable
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f1950f1a-8aac-4d6a-a630-4d80baffa0ae","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 429 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 430 error should be null
,ok 431 error should be null
,# setup
,ok 432 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 433 error should be null
,ok 434 error should be null
,# setup
,ok 435 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 10:58:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 436 error should be null
ok 437 error should be null
,# setup
,ok 438 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05103a92-5a59-4683-a270-57ba1ddbc080","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 439 peer discovered ,first time does not have new address
2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05103a92-5a59-4683-a270-57ba1ddbc080","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 440 address has not been changed
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05103a92-5a59-4683-a270-57ba1ddbc080","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 441 new port handled correctly
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05103a92-5a59-4683-a270-57ba1ddbc080","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 442 new host handled correctly
,2017-07-21 10:58:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"05103a92-5a59-4683-a270-57ba1ddbc080","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 443 newAddressPort is null for unavailable peers
,# teardown
,ok 444 error should be null
,ok 445 error should be null
,# setup
,ok 446 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 10:58:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 450 NOT IMPLEMENTED # SKIP
,# teardown
,ok 451 error should be null
,ok 452 error should be null
,# setup
,ok 453 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 10:58:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 454 error should be null
,ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 457 should be equal
,# teardown
,ok 458 error should be null
,ok 459 error should be null
,# setup
,ok 460 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 10:58:43 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 461 error should be null
,ok 462 error should be null
,# setup
,ok 463 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 464 contains expected properties
,ok 465 the same hostAddress
,ok 466 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 467 error should be null
,ok 468 error should be null
,# setup
,ok 469 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 470 contains expected properties
,ok 471 the same hostAddress
,ok 472 the same portNumber
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 473 error should be null
,ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'listening 58441'
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4a3cbb02-b354-4fc1-af0d-82dcd4937967","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 476 Got specific error message
,# teardown
,2017-07-21 10:58:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4a3cbb02-b354-4fc1-af0d-82dcd4937967","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 477 error should be null
,ok 478 error should be null
,# setup
,ok 479 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'listening 58442'
,2017-07-21 10:58:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e920ac60-903c-432f-bf84-254dbd9eb303","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:e920ac60-903c-432f-bf84-254dbd9eb303
,ok 480 native wrapper `disconnect` called once
,ok 481 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 10:58:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e920ac60-903c-432f-bf84-254dbd9eb303","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 10:58:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 482 error should be null
,ok 483 error should be null
,# setup
,ok 484 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 485 error should be null
,ok 486 error should be null
,# setup
,ok 487 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 488 error should be null
ok 489 error should be null
,# setup
,ok 490 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 491 error should be null
,ok 492 error should be null
,# setup
,ok 493 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 10:58:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 494 error should be null
,ok 495 error should be null
,# setup
,ok 496 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 500 error should be null
,ok 501 error should be null
,# setup
,ok 502 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 10:58:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'listening 58443'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B9CC38B-6D29-410C-87C1-1ABD7BB6C18A
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a9ed4844-563a-4f07-8347-94c168d7b84d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"42219d41-3f8e-47de-b5dd-4a91c4285965","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 507 Peer availabilities has one entry for our connection type
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a9ed4844-563a-4f07-8347-94c168d7b84d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 10:58:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"42219d41-3f8e-47de-b5dd-4a91c4285965","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 10:58:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:58:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:58:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 508 No peers
,ok 509 No peers
,ok 510 No peers
,# teardown
,ok 511 error should be null
ok 512 error should be null
,# setup
,ok 513 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'listening 58444'
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1fe5e9c7-db4b-4108-87b0-da680e83149f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 514 1
,ok 515 2
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0f587266-9f9c-4891-8766-65473fa7c7fa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1fe5e9c7-db4b-4108-87b0-da680e83149f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:58:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0f587266-9f9c-4891-8766-65473fa7c7fa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 10:58:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 10:58:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 10:58:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 516 error should be null
,ok 517 error should be null
,# setup
,ok 518 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 10:58:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 519 error should be null
,ok 520 error should be null
,# setup
,ok 521 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'listening 58445'
ok 522 error should be null
ok 523 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "67A4F3A2-48D4-4914-A36B-20,CC0B58C4CA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 524 error should be null
ok 525 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D43E4AEB-4557-45D2-ABF7-C38AD8B139CF
,[ThaliCore] Browser.startListening
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 526 error should be null
,ok 527 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
2017-07-21 10:58:48 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:48 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for FED086A1-5F45-4FC0-ADED-825912AED435 (syncValue: 0)'
,2017-07-21 10:58:48 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA:0
2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4CDF9656-B658-49DA-B3,47-1BEC9558B984","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","generation":0}'
,2017-07-21 10:58:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 10:58:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
2017-07-21 10:58:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","generation":0}]'
2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","generation":0}'
,2017-07-21 10:58:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 10:58:50 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] Advertiser: session connected Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,D086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,ED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,D086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,ED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
,[ThaliCore] Session.session(_:peer:didChange:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
,[ThaliCore] Session.startOutputStream(with:) peer:51E6DCB2-5EEF-4DB9-B264-3A653DE8361E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [13, 15, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}]'
2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","generation":0}'
,2017-07-21 10:58:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-21 10:58:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FED086A1-5F45-4FC0-ADED-825912AED435:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,D086A1-5F45-4FC0-ADED-825912AED435:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,ED086A1-5F45-4FC0-ADED-825912AED435", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FED086A1-5F45-4FC0-ADED-825912AED435", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,1 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 10:58:56 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4CDF9656-B658-49DA-B347-1BEC9558B984 (syncValue: 1)'
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
[Thali,Core] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FED,086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:FED086A1-5F45-4FC0-ADED-825912AED435:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 10:58:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FED086A1-5F45-4FC0-ADED-825912AED435","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
[ThaliCore] Session.session(_:peer:didChange:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "67A4F3A2-48D4-4914-A36B-20CC0B58C4CA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "4CDF9656-B658-49DA-B347-1BEC9558B984", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58456
,2017-07-21 10:58:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":58456}'
,2017-07-21 10:58:59 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D (syncValue: 2)'
,2017-07-21 10:58:59 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4CDF9656-B658-49DA-B347-1BEC9558B984:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [13, 15, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:58:59 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:58:59 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
,[ThaliCore] Session.session(_:peer:didChange:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
,[ThaliCore] Session.startOutputStream(with:) peer:B365D1C2-555A-4A7A-BB92-990F524EE159
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [13, 15, 20, 21, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58462
,2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":58462}'
,[ThaliCore] BrowserManager.disconnect peer:FED086A1-5F45-4FC0-ADED-825912AED435
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [13, 15, 20, 21, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 10:59:02 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:59:02 - DEBUG testUtils: 'Got end'
,ok 528 received all uuids
,# teardown
,2017-07-21 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4CDF9656-B658-49DA-B347-1BEC9558B984","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 10:59:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6978E7D7-0C42-4D2A-9BFB-FE6FCF46417D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:67A4F3A2-48D4-4914-A36B-20CC0B58C4CA
2017-07-21 10:59:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
,2017-07-21 10:59:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 10:59:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 10:59:02 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 10:59:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 10:59:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeS,treams() vsID:20
ok 529 error should be null
ok 530 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeS,treams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [13, 15, 21, 22, 23]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [13, 15, 21, 23]
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
,[ThaliCore] VirtualSocket.deinit vsID:23 [13, 15, 21]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [13, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 10:59:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 532 error should be null
ok 533 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 534 getPeerIdentifier
,ok 535 getConnectionType
,ok 536 getActionType
,ok 537 getActionState
,ok 538 getPskIdentity
,ok 539 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 540 initial state
,ok 541 after start
,2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 542 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 10:59:04 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 548 agent's destroy should be called
,ok 549 agent's destroy should not be called again
ok 550 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 551 Entry counter must be 1
,ok 552 Entry exists
,ok 553 Size must be 1
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
,ok 564 Entry 1_1 does not exist
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
ok 584 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 585 Kill should be called once
,ok 586 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 587 is an agent
,ok 588 enqueue is fine
,ok 589 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 590 is an agent
,ok 591 first enqueue is fine
,ok 592 is an agent
,ok 593 second enqueue is fine
,ok 594 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 595 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 596 is an agent
,ok 597 good enqueue
,ok 598 Identity should match
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got response data'
,2017-07-21 10:59:09 - DEBUG testUtils: 'Got end'
,ok 599 Got expected response
,ok 600 Got psk call back
,# teardown
,2017-07-21 10:59:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 614 wrong arg type
,ok 615 wrong arg type
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
ok 620 we are in the pool
ok 621 We are out of the pool
ok 622 Action was killed
ok 623 The original kill was called too
ok 624 second item is still in queue
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
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 635 Got right error
ok 636 Start should not be called
ok 637 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 10:59:12 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:12 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 638 Got right error
,ok 639 Start should not be called
,ok 640 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 641 Got null
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 642 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 643 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 644 Got Null
,ok 645 Got another null
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 646 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 647 is an agent
,2017-07-21 10:59:13 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 648 Action 1 killed at least once
,ok 649 Action 1 went first
,ok 650 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 651 should have gotten null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 652 Should have stopped nicely
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 653 Still looking for null
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 654 Yup, another null
,ok 655 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 656 Null 1
,ok 657 (unnamed assert)
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 658 is an agent
,ok 659 Null 3
,ok 660 Replication not yet called
,ok 661 Notification 2 not yet called
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 662 is an agent
,ok 663 Notification went first
,ok 664 Notification 2 not called yet
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 665 is an agent
,ok 666 Notification finished
,ok 667 Replication finished
,2017-07-21 10:59:14 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 First does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 670 is an agent
,ok 671 Second does not throw
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 first ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 second ok
,ok 676 third ok
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 10:59:15 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 10:59:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 10:59:16 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 10:59:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 685 Response should be NETWORK_PROBLEM
,ok 686 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 10:59:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 687 Resolution should be BAD_PEER
ok 688 correct error message
,# teardown
,2017-07-21 10:59:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 689 Call start once
,ok 690 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 691 must return null after successful call.
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 692 Should be Killed
,ok 693 Start after killed
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 694 Should be KILLED
,ok 695 must return null after successful kill
,# teardown
,2017-07-21 10:59:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 696 Should be KILLED
,ok 697 must return null after successful kill
,# teardown
,2017-07-21 10:59:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 698 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 699 must return null after successful call
,# teardown
,2017-07-21 10:59:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 10:59:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 700 Should be NETWORK_PROBLEM caused closing server socket
,ok 701 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 702 Should be NETWORK_PROBLEM caused closing client socket
,ok 703 Should be Could not establish TCP connection
,# teardown
,2017-07-21 10:59:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 711 should be equal
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
,2017-07-21 10:59:30 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 721 should be equal
,ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 723 right number of calls to address book
,ok 724 good preAmble
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
ok 734 keys match
,ok 735 secrets match
,ok 736 We have an entry!
ok 737 keys match
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
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 10:59:33 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 747 notification peer dictionary contains exactly 1 peer
,2017-07-21 10:59:34 - WARN thaliNotificationClient: 'peer is not available'
,ok 748 notification peer dictionary does not contain any peers
,2017-07-21 10:59:34 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 749 entry exists
,ok 750 entry is resolved
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 751 Action should be KILLED
,ok 752 Peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 753 hostAddress must match
,ok 754 portNumber must match
,ok 755 suggestedTCPTimeout must match
,ok 756 connectionType must match
,ok 757 peerIDs must match
,# teardown
,2017-07-21 10:59:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 758 Correct error
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 759 hostAddress must match
,ok 760 portNumber must match
,ok 761 suggestedTCPTimeout must match
,ok 762 connectionType must match
,ok 763 peerIds must match
,# teardown
,2017-07-21 10:59:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 765 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:37 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 766 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 10:59:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 767 action should be resolved with NETWORK_PROBLEM error
ok 768 correct number of requests
ok 769 correct number of failures
ok 770 correct final peer state
,# teardown
,2017-07-21 10:59:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 10:59:40 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 10:59:40 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 771 peerDictionary should become empty
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 failed with expected error
,ok 773 peer state should be RESOLVED
,# teardown
,2017-07-21 10:59:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 10:59:41 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 774 First action failed
,ok 775 second action killed
# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 776 secrets are equal
,ok 777 Public key matches with the server key
,ok 778 hostAddress must match
,ok 779 portNumber must match
,ok 780 suggestedTCPTimeout must match
,ok 781 connectionType must match
,# teardown
,2017-07-21 10:59:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 782 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 783 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 10:59:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 785 All keys need to be available in the cache
,ok 786 All entries should be expired after 1 second
# teardown
,2017-07-21 10:59:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 787 Size of the cache should be 2
ok 788 Cache doesn't contain dictionary1
,ok 789 Size of the cache should be 1
ok 790 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 791 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 792 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,ok 794 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 795 no error
,ok 796 should be 204
,# teardown
,2017-07-21 10:59:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 797 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 798 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-21 10:59:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 806 error should be null
,ok 807 should be 204
,# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 808 should be 404
,# teardown
,2017-07-21 10:59:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 809 equal keys
ok 810 not equal connection type
ok 811 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 812 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 813 second cleared dictionary
,2017-07-21 10:59:52 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 10:59:53 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-21 10:59:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 10:59:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 10:59:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 849 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 10:59:54 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 850 right error
,# teardown
,2017-07-21 10:59:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 10:59:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 852 Got error as expected
,# teardown
,2017-07-21 10:59:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 10:59:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 853 Got error as expected
,# teardown
,2017-07-21 10:59:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 10:59:58 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 10:59:59 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:01 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
,ok 855 All tests passed!
,# teardown
,2017-07-21 11:00:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 11:00:03 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:04 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:06 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 856 should be equal
ok 857 All tests passed!
,# teardown
,2017-07-21 11:00:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 11:00:07 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:09 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 858 action should be killed
ok 859 Error should be timed out
,ok 860 No doc found
,# teardown
,2017-07-21 11:00:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 11:00:11 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 11:00:12 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 861 should be equal
,2017-07-21 11:00:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 11:00:13 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 862 action should be killed
ok 863 Error should be timed out
,# teardown
,2017-07-21 11:00:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 864 socket hung up
,# teardown
,2017-07-21 11:00:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 865 same getPeerAdvertisesDataForUs
,ok 866 Same pouchdB
,ok 867 same localDbName
,ok 868 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 11:00:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'listening 58589'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D2E652DD-3DA8-412A-A000-E4D619975F36
,[ThaliCore] Browser.startListening
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C6B4B658-9B6C-4365-A441-47A5119A6F4B
,2017-07-21 11:00:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Advertiser: session connected Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
2017-07-21 11:00:18 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","generation":0}]'
2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","generation":0}'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 11:00:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"667385B3-84B4-4AAD-A98D-31F23F247C31","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 667385B3-84B4-4AAD-A98D-31F23F247C31 (syncValue: 3)'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Advertiser: session connected Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","generation":0}]'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","generation":0}'
,2017-07-21 11:00:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 11:00:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A4194BA7-1EB2-4E58-9EE4-605A14B2387A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C6B4B658-9B6C-4365-A441-47A5119A6F4B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C6B4B658-9B6C-4365-A441-47A5119A6F4B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] Session.session(_:peer:didChange:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [13, 15, 24]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "667385B3-84B4-4AAD-A98D-31F23F247C31", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58593
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":58593}'
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A4194BA7-1EB2-4E58-9EE4-605A14B2387A (syncValue: 4)'
,2017-07-21 11:00:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [13, 15, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [13, 15, 25]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [13, 15, 25, 26]
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
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [13, 15, 25, 26, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [13, 15, 25, 26, 27, 28]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-07-21 11:00:21 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [13, 15, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [13, 15, 25, 26, 27, 28, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [13, 15, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [13, 15, 25, 26, 27, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [13, 15, 25, 26, 27, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:31 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,5 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [13, 15, 25, 26, 27, 28, 29, 30, 32, 33, 34, 35, 37]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient,.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:667385B3-84B4-4AAD-A98D-31F23F247C31:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] Session.startOutputStream(with:) peer:5162A00F-000D-4C6B-81D4-895631E0BC01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 38, 39, 40]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-21 11:00:22 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39, 40]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] Session.startOutputStream(with:) peer:D70C0246-53B9-45DE-9A1F-0F5509EBDD57
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39, 41, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [13, 15, 25, 26, 27, 28, 29, 30, 33, 34, 35, 37, 39, 41, 43]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputSt,ream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
[ThaliCore] TCPClient.socketDidDisconnect(_:withErro,r:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore], VirtualSocket.deinit vsID:26 [13, 15, 25, 27, 28, 29, 30, 33, 34, 35, 37, 39, 41, 43]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [13, 15, 25, 27, 29, 30, 33, 34, 35, 37, 39, 41, 43]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:30 [13, 15, 25, 27, 29, 33, 34, 35, 37, 39, 41, 43]
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [13, 15, 25, 27, 29, 33, 34, 37, 39, 41, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.soc,ketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A4194BA7-1EB2-4E58-9EE4-605A14B2387A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:58615
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 11:00:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:27 [13, 15, 25, 29, 33, 34, 37, 39, 41, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [13, 15, 25, 33, 34, 37, 39, 41, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [13, 15, 25, 34, 37, 39, 41, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:37 [13, 15, 25, 34, 39, 41, 43]
,2017-07-21 11:00:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":58615}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [13, 15, 25, 34, 39, 41, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] VirtualSocket.deinit vsID:44 [13, 15, 25, 34, 39, 41, 43]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [13, 15, 25, 34, 39, 41, 43, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 11:00:25 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [13, 15, 25, 34, 39, 41, 43, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
,[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:34 [13, 15, 25, 39, 41, 43, 45, 46]
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [13, 15, 25, 41, 43, 45, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect,(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [13, 15, 25, 43, 45, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:43 [13, 15, 25, 45, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [13, 15, 25, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [13, 15, 25, 45, 46, 47, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4194BA7-1EB2-4E58-9EE4-605A14B2387A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [13, 15, 25, 45, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:48 [13, 15, 25, 45, 46, 47, 49]
,2017-07-21 11:00:26 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 11:00:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 11:00:28 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [13, 15, 25, 46, 47, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [13, 15, 25, 47, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [13, 15, 25, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [13, 15, 25]
,2017-07-21 11:03:17 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 11:03:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:03:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:03:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:04:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:04:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:05:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:05:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:06:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:06:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:07:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:07:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:08:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:08:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:09:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:09:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 11:10:16 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 11:10:17 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-21 11:10:17 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 11:10:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 869 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 11:10:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:10:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:10:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:11:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:11:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:12:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:12:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4,965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:13:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:13:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 11:14:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-496,5-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 11:14:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/88651E98-7A9E-4965-88B5-ACC90BCE58AB/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
