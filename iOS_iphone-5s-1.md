#### Test 132007755285fc7e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/59107C51-D784-4F3C-B2E4-FDA7580E8F0C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/59107C51-D784-4F3C-B2E4-FDA7580E8F0C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55600"
,(lldb)     command script import "/tmp/59107C51-D784-4F3C-B2E4-FDA7580E8F0C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
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
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:11:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests,.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "660A02D2-3722-43CA-BE12-BB0106648261", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:660A02D2-3722-43CA-BE12-BB0106648261
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AC984E9E-7EC3-4508-9F5E-6ADB86E3F7A4
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C1775505-,D61E-4292-89D6-2FDB369F452F
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F93BF92C-6A79-4F15-A33B-AE318F64EEAB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F93BF92C-6A79-4F15-A33B-AE318F64EEAB
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F93BF92C-6A79-4F15-A33B-AE318F64EEAB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F93BF92C-6A79-4F15-A33B-AE318F64EEAB", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-24 12:12:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
Total duration:  2.624120056629181
,2017-07-24 12:12:00 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-24 12:12:00 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F93BF92C-6A79-4F15-A33B-AE318F64EEAB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F93BF92C-6A79-4F15-A33B-AE318F64EEAB", generation: 0)
,2017-07-24 12:12:04 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 12:12:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 12:12:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 12:12:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 12:12:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 12:12:08 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 12:12:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:22 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-24 12:12:23 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 12:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-24 12:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 12:12:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-24 12:12:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-24 12:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-24 12:12:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 12:12:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 12:12:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 9 should be equal
,ok 10 should be equal
,ok 11 should be equal
,ok 12 should be equal
,ok 13 should be equal
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
,ok 30 testing promises
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
,2017-07-24 12:12:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-24 12:12:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-24 12:12:48 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-24 12:12:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:12:52 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 12:12:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:07228D2F-CF4D-4316-9A2F-1A9A0662B263
,[ThaliCore] Browser.startListening
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:707C7C01-EB08-4E18-9DDA-2835F4D56716
[ThaliCore] Browser.startListening
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35B3D213-C506-40FA-AA7B-FBA8091D5F29", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:35B3D213-C506-40FA-AA7B-FBA8091D5F29
2017-07-24 1,2:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:35B3D213-C506-40FA-AA7B-FBA8091D5F29
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F07E3653-CE26-4852-9B4F-6D60CDF18F14", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F07E3653-CE26-4852-9B4F-6D60CDF18F14
2017-07-24 1,2:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F07E3653-CE26-4852-9B4F-6D60CDF18F14", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:F07E3653-CE26-4852-9B4F-6D60CDF18F14
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F07E3653-CE26-4852-9B4F-6D60CDF18F14
,[ThaliCore] Advertiser.stopAdvertising() peerID:F07E3653-CE26-4852-9B4F-6D60CDF18F14
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:57 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A1C6AF78-FB94-4572-8639-B92FC61D9B96", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A1C6AF78-FB94-4572-8639-B92FC61D9B96
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:59, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
,2017-07-24 12:12:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.,init(serviceType:foundPeer:lostPeer:) peer:511EE597-5291-4EA8-BC6D-1A4359C21ACF
[ThaliCore] Browser.startListening
2017-07-24 12:12:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":t,rue}'
2017-07-24 12:12:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskId,ToSecret":null,"networkType":null}})'
2017-07-24 12:12:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AC440CA-971E-4F78-BB2F-BC94E406C8C1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AC440CA-971E-4F78-BB2F-BC94E406C8C1", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4B9B596-003C-4812-A751-BA727FF36A55:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E4B9B596-003C-4812-A751-BA727FF36A55", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A1C6AF78-FB94-4572-8639-B92FC61D9B96
2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7CD4A326-EA8C-4C7A-9109-4C3844A1A542
2017-07-24 1,2:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0B72AB8C-48DE-4B01-8934-F06A26A55C20
,[ThaliCore] Browser.startListening
2017-07-24 12:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
2017-07-24 12:13:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6E6B3997-56C8-4EBD-8540-DB22D429A7D1","generation":0}'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6E6B3997-56C8-4EBD-8540-DB22D429A7D1 (syncValue: OgFtLmzeNgeweggD4Ybl5S0IT9V24pn4)'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5149F07E-0275-4,E9E-AF1F-3A0611BA7CBA
[ThaliCore] Advertiser: session connected Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5149F07E-0275-4E9E-AF1F-3A06,11BA7CBA state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:compl,etion:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] Ses,sion.init(session:identifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F874D147-C68A-491B-866D-E7AF25C37560
[ThaliCore] Advertiser: session connected Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on,:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F874D147-C68A-491B-866D-E7AF25C37560 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"75DD76C5-36DA-429E-9B49-8B4F23A6900D","generation":0}'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5149F07E-0275-4E9E-AF1F-3A0611BA7CBA
,[ThaliCore] Session.session(_:peer:didChange:) peer:5149F07E-0275-4E9E-AF1F-3A0611BA7CBA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60934
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F874D147-C68A-491B-866D-E7AF25C37560
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OgFtLmzeNgeweggD4Ybl5S0IT9V24pn4","error":null,"portNumber":60934}'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OgFtLmzeNgeweggD4Ybl5S0IT9V24pn4', error: 'null', listeningPort: '60934''
,[ThaliCore] Session.session(_:peer:didChange:) peer:F874D147-C68A-491B-866D-E7AF25C37560 state: connecting -> connected
,2017-07-24 12:13:08 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-24 12:13:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:7CD4A326-EA8C-4C7A-9109-4C3844A1A542
2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12,:,13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1
,[ThaliCore] Session.session(_:peer:didChange:) peer:5149F07E-0275-4E9E-AF1F-3A0611BA7CBA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F874D147-C68A-491B-866D-E7AF25C37560
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60934
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:F874D147-C68A-491B-866D-E7AF25C37560
[ThaliCore] AdvertiserRelay.deinit
,# setup
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OgFtLmzeNgeweggD4Ybl5S0IT9V24pn4","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0
2017-07-24 1,2:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:735DEB32-1B38-4817-8CCF-B343AF28D0D1
[ThaliCore] Browser.startListe,ning
2017-07-24 12:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:13:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
2017-07-24 12:13:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6E6B3997-56C8-4EBD-8540-DB22D429A7D1","generation":0}'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6E6B3997-56C8-4EBD-8540-DB22D429A7D1, (syncValue: MfQ9IAjrLvBwjGHXM2H6ig3WbKLRB6NB)'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D42,9A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:870B7B74-771B-4859-AAB3-509F704123AD:0
2017-07-24 12:13:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21ED5147-420B-4877-B71D-3C4D9F498B8D","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
20,17-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"870B7B74-771B-4859-AAB3-509F704123AD","generation":0}'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
[ThaliCore] Advertiser: session connected Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1 error: max retries exceeded
2017-07-24 12:13:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MfQ9IAjrLvBwjGHXM2H6ig3WbKLRB6NB","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MfQ9IAjrLvBwjGHXM2H6ig3WbKLRB6NB', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:13:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21ED5147-420B-4877-B71D-3C4D9F498B8D (syncValue: 5tMSuznKGVEkyXi9SHtwd1mIm0VjtkD1)'
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21ED5147-420B,-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
,[ThaliCore] Session.session(_:peer:didChange:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
[ThaliCore] Session.startOutputStream(with:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60942
,2017-07-24 12:13:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5tMSuznKGVEkyXi9SHtwd1mIm0VjtkD1","error":null,"portNumber":60942}'
,2017-07-24 12:13:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5tMSuznKGVEkyXi9SHtwd1mIm0VjtkD1', error: 'null', listeningPort: '60942''
,Connecting to the localhost:60942
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,Connected to the localhost:60942
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 12:13:24 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 []
,ok 88 got the same data back
,# teardown
,2017-07-24 12:13:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:21ED5147-420B-4877-B71D-3C4D9F498B8D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60942
[ThaliCore] Session.disconnect() peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:65639090-B4AF-4DEF-914A-52E21168A9FB
2017-07-24 1,2:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[ThaliCore] Browser.startListening
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:870B7B74-771B-4859-AAB3-509F704123AD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
2017-07-24 12:13:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"870B7B74-771B-4859-AAB3-509F704123AD","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 870B7B74-771B-4859-AAB3-509F704123AD (syncValue: rCSRR0clLtw1k0FhxwL8z5L349FdznLP)'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21ED5147-420B-4877-B71D-3C4D9F498B8D","generation":0}'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
2017-07-24 12:13:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C05AD67-A1F8-454C-9056-1AD3142D948D","generation":0}'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D5997C9-1AFA-49E8-8859,-3D3CF8615E09:0
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D5997C9-1AFA-49E8-8859-3D3CF8615E09","generation":0}'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,70B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:870B7B74-771B-4859-AAB3-509F704123AD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:87,0B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,70B7B74-771B-4859-AAB3-509F704123AD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:13:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rCSRR0clLtw1k0FhxwL8z5L349FdznLP","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rCSRR0clLtw1k0FhxwL8z5L349FdznLP', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 12:13:32 - ERROR thaliMobileNativeTestUti,ls: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C05AD67-A1F8-454C-9056-1AD3142D948D (syncValue: EGFCaVOkT8aLscdrEcTmao3gLOV0Ictd)'
2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05,AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60950
2017-07-24 12:13:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EGFCaVOkT8aLscdrEcTmao3gLOV0Ictd",,"error":null,"portNumber":60950}'
2017-07-24 12:13:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EGFCaVOkT8aLscdrEcTmao3gLOV0Ictd', error: 'null', listeningPort: '60950''
,Connecting to the localhost:60950
Connecting to the localhost:60950
,Connecting to the localhost:60950
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] Session.startOutputStream(with:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,Connected to the localhost:60950
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
Connected to the localhost:60950
Connected to the localhost:60950
,ok 91 correct string length
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 95 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:5 [3, 4]
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] Advertiser: session connected Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] Session.startOutputStream(with:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] Session.startOutputStream(with:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] Session.startOutputStream(with:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 4, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (13140 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received all data: CmHuMJd1JR6XZkTdAKYIaRXgOAnnq5hyl44mWfaKKbXMcOKTSLd7HccZd7Rd1930A5dlcjESc4WVvWbyufSQG5S1IwADMtrkpwu2fzTtGhDMUMCb7c1IWzlfPA1GnMGZM83l3DEkAIxLYhammhcRePdeGneahkVYbZb1JKcr9c92ePeJpW,sB3uZ2J31iUn9ymSYb6dOiupjAyZYCGVq30n5NrQPN21SwRv4QRLtT2WV1YJ8eRh0qUyuSXHcCiqzCbnIadjhNAbQaONNBXyRk0ZaNS32jzdx2286olm4ZK97LlGfCXEePNoeiEmsjeL6JRquJMhXsNgmbU0rIOV6X0Iud4XO4tx3Bc0UlcoFoRF3JVtT7qNfTnTYbDKoQgdbbASseipa94h1ima1TL5ekBjSy89inUSsvwQb6BGBAocWNPz6JeJ,mikdR4ZHnx6Dn26ExL3WeUldHW8UjR8dq3DIHwthSFHEY7bMgieYG80JMKxxt135mytSJVkocvV4BYS3XtGyDE57ty56kLxebI3DWNSZpOIz35ATtGT8RGxSxRfTLN8maNmFCpAFsaYXDhlngC0ng4I6dH0R78gX6khkpvD9U0ity5cHV1Fe8G92c3XJrXZQkNp6zGe3qXGF7Q3kVs6ROTPPc5PyQdwaArR1BOJgYR14AbaLBoMaeqt14IyJPxuO,sNGY7FOfZF76l6CWTsm5N0XPcOKaMdtfRfIIgxhhb4iKesh1gZqoZkXOqBZoMfr9HLRpp9U2oBgpW7M9dBRZW0PGDYvp0E5GAilDHvkgBRyRF5RlFpB0V8O4MyPvxMJenfYAWhNziMoXkKyNLgVQx4i2ef00HM3ZYB9nyUevcsnwenWL20L0mgK9iKn3HpenYemXwroTN7ipTYyOwXxs7FPooiZ7a9NzsfHQjnUIYMJvSoJ81DnHnJrghEydXcAe,at5arJd9TMuVX2joYtX0PwDFBVSQTtXERuI7jPi7bVpDWJfTirGUO9O8zH0BIEW1hRnLqJCjAZiEA5PTSlL4Uuisj5AkGlKitsryDAgrzxk8ez9RzJT9E85yczY5aLGWMcjdCjZTFsz4tRh4LQ4WqwRKUf5Ieqruf8qSREFGekTPhhTDosktqm7FxVRr2vla8VYWHyLdzHQubNXx0ogjRWtikH5uEYGZ09WkD5upjHM0aKkm5iSO7bRZkf1NgVvt,ButOekyEGTrg16s7LPMfasQ90pUwzqbJvz6fmioi58itRbJrwNtVrTCJ0s3tGKpsEbkH64MXSiRPbTe1X5c8KLAg3YMMtAiMwGojrWlHmo8hXQSfIzEnaqi21TUnIJlEYYU1l58nyhg0MGmU8e4cu7o6p09w4Tg4gtgMFX2WNROG7Q09wBEoKv6kFiXU2tZDkmSNorPTufuxEiFiUMCJnk7IhkQdHIDrpvoUrLg2Xco1BXOnGMMPLE2ufHEuygoW,uY5ouHmLUuTD2T77WcoKGGPlyFaDlcp5bUijirS1JJAMjkj7dNDzxNNmYyvJ8Wd8ZWmvJo4WQmGOoSu5qjQ1fLPCDCYiNFb9uPkX9dmQZuDu6Utos2FgPDg542rkbp2nGp1N1qH9CXsiitcZZgcP0jush0MHdCXKjEkq3umloSqlZllQqlErZ6GzXDhaS3dzdSOD40EGtCVluKQ82YVWOv8IH2vZNBRkHvBsaGqFK3hQpxNusJe0BRfC23TG33de,6E9eyK7rXEfSlbmmuiCXfngq2abMcOh7L9twS8HtbTxTobhGoWJvv87rfQlDH4lBYSkfCaiKO4NxdvwtRl8W0LR11eYfs3GDVJJu4reqc1lHzJ3H1ssU3gvg8qchTRUHw5yL3Q015b4BnlCjsuyMmGuWDnypFfuDqADPNBEtr9kkxEgA5sK91NEl6KwLqEeeNAGzHmv4rVLfZeMKd0v0iwt9gUk5U8oQboPu56awxGd4XuGkHVpqeajaHgpzbWjC,gyrtZe7Iw8qN45rqLmMy8iPSXORaqt7pLoOc4B3gMkJED7jMEE6oaCFrA27aF2ZGVwzlboA9OYIcehvdhDik203E5SWuBZMgOP0lOu2eERK6BltDfZoWiCtUwmYsgigwkIZpc1yHbCn4Hklp8teMhHCAaSc9c0mPFHJgYPpGhE3mCFxmmuepijCcHuA6uxt2c3pnBQK6JnLC97Wle9euZ4asdtDf8QRjq6lUIPAJfHT68ocWGlK7z4xn5fT5dSfa,lvQyzwQ917UgHnE0vmJxRdatpWIE6T0l5yZI3wogAPdnqLjVogXqkP1fIVnzlcCaw4ybCweQTZTEsGEGp9qC52GeOpml6aUjZaSI3pjOu6358ORFI9aLjnY4kjVS9Z0EdUAg2WqPNnbta4syPm3abiGwQSTl3Jczx5asNcphrC8hCyCAbHR7dDsp3AcmtngFMfzTmwTwjqXLSCMr3aUB7lDktbkHS6M9L9tGhf0QEmaicfOFE5m8GC1Xai1801fi,JUyvNhUEoKRsKmgaE0aT2VqtbuaotuwMz76PjzsltFV3zqXHxwGgZqnmwfAYQuuk4iF4aBzUosDlLyx4xexsjiUZDXnU5Fe9dSuIwHwpMeRnF1wgk5Xw9UkRBhFsPrDMibhMbPcnkj7HN4CZabCNDKPfOm9ZmCIAVpfAZ66AwKpnQoHaxDdvvLhnwAADpUuaWY7EAp0s6Fp3vrOZTa449RaPMEXOJfyFhtIdIJGNPuDjZ7zmYQguwliQI4vdKfzo,5sDsif8HqmXegKnOz29HH0R9rAjHhFx9qRcpaXgOGH5BGKvxg3Mxr4UtGAtfgE0fuC91AX4nyjf7KPHHVSXjtMO4cQUFlsYiBVDeGjXzZ2NcFveF538EEtfgstdZT8rAB209E59nzBO2KYLY3Kta0Ws9lfB7c6OQM1Xf5IOfjD2MYlHSVcnpzOc254M1CfngBqr4SGnyIq1HKSKQSsd4mXEl3S49XtT8o8QbhnmVew7bSiEZWXwEtnd1jYE7J5Zp,8iAxdvb0DAqnE8O36A5vh79YQgd8WaLnj0k6lzkIuAELkFrYuChojBmkV80dpPWjFVbEMvnzamzOCS8toAfhSIDPoszgR8sM70Pcqcsdx4HziHKFEH8FOeteUdztbhAALB9O1S24L4OU6RQzutOmM8nRo1q8UBT1dsBOXCF5E5qylTX3pBXV2f5okKWr68KfhUZnA1tAWZmvQ5GDZ97NKMXvRS6hLcnC1hZ5rIFygS7LAAs5ti6ToyYF2Slw3Dw1,dV10fvdkNSeCw7Kq9FV3AlbnlKhazMEh4Kzfu3Fm0aIyekrYP74SDjwO1jh7Ynb8Wlg3Kr9GxuIsizbeKa1OdKpLmpUOWUDXBuPEDguLaKiwm72Bcx2NupabdfbddUujGTmNIlMJ4uqo18GTaDeeIqMfZQVQuOTMtLQOwNO6vP8etkFffZMlZuSfPNbcYOMJZVnEY3yrJ55PFWDVlExi72NF7qJTehRaNJlCZAUeRBR0WsN0dLysddFoY191mKdm,2Jh3tQK9UzUZnYZP8cIjCXQyaqHft8sz2VQflftDGEmZdgT2R9LrcUuNNKEgMJ7rZaINkDQPb06S4MUgSsfP0qi081AWSEZWGaMbInwwhQTIzzouDESN6A8IbWGVU0GNU3crYRyLuFHRq8S9UXNWmZqg41Cs8r973E0XQHYnZ6Ozq0ocLYDpE8hmV3PGJisSd4aOz5zAetP6joalLSetjhAt7tU8l0UmRY9Fi8XtYfALer79eD2XCDB8pvHfnpTz,aEnuNKl8i4mofLaNi9NXMElQXLTNFkUJMGMyJrC1l2H7mK1FVaKhIsHpXwUP67bsB97rcTCw41eZnCPuaSs7YUxSdIDLKKjXqUVaix3294UAHTSN1j34LeKiagS1m572rACbNn1B6NUI5dF4OKlNfMtPRPVShVlXd5DWd7QNSsKsgl23bFvw2x3pPCAwmEZNxfZ5CbpneqE8iYx3E0bPIQUWvVfdoeurnbFXkMDodgjs99dnjEcObR6oJYXIE4Kp,f076GadXvMN0uukUPtoelVGfVI0BZjzvL91WaabI7vG4NgEO02Lfwxp6UkGMwc3Dl7DIvbCex4TZzlffu2sjwYIyvfs1to4GXojysEWbHsutgvdhFFBj2Lphen5W9duKlbQtjC7KDYKltlGo8ToiYHVfEmbuKy1Q9YChYVrf1vRPDWzAENyuqgScxe75YhYoHCSzQPlQrQcB0Lxo69JbkxeHGAX7y7HXWBxWh9hRJR8wIRNzQ0dCwaASBEkuEqiq,72Vj6jnS88gYyPLXzRjsdJ1wrdgLgTo8jXRzm6rWVxbCD7rb61fs62MeOQSv31YqhF7ohHjSuEHvCUUjjgChTd3FVpb8xmLRg0dSGqLF25t30ESx6uc4pV3vEgvaADJX7L5O9DMB6vcDvlVx9xBZYWGm8QcDXz9GncdsA9Dax1CIjkAWfNNdIZHpG1wkywFrU1E6wkvsPg4Xpq9OQJu6WWfDtkuscXQscIsSzSC2HCVRVgKaMkRg7zbo704SSfMs,2EWLXPThRQWID4oM7FO6uet3TEUD2vHSp48g4PIbvZOdA97vGtCnnMkLRjrQ1YbiV0RslhKWQFvRiKEq8IXWdGU7s6YP4qS3gO2sjoXhJmVpc7bcfd6AmvO5u8iCn35hmUNSFqHXVl4nimNIVlNvvbzf2epp6bAtAcv0G3XhY4XO6MwRXGzhxqBoAzT4qftwVtL5GDu6LIdgEWfVc5ivOQsYgSZmozcWFNG1AwULbNJWbciz1QbG7YXWMr3LONwW,yI5e9HxlkQ81VoWs8U4RAMb9nd3KmWwdP1CSMyNy5lcOY6TjKdHDEQVzKkGUSnsNtRG1qXFxrDvLk8u4ngJVT2MYdOzaSuuUzYzLfrfyVd3UNtXx53awaGMFsSQ6Z2BEmCZf1q0g2tpMixhdz2xazdBXP4DjJXpXChaYkNijwWvMl82mGKBdx7BnStw3UT9pP1BKwpu3GzUHEzyvPasfJBLXqCFItFXfHG8ChrYz2anJ2oHLhxVp6FHptoR3ZnWB,nru5PrWHl7lvxQfETqc6cLzbNlZWQzhs63fUAtJ9wf0RGKSi7c6zaCuhonkceWAS1oOhN4j9Aoi5wpHVvLOHK66J5WGaRDUPUNPhL3Apq27Rl5HYpehqixYSt1PhI6p3s01A5BAyVFJuExqeNJoxjOiiNn4fshIlpcr5bjy4s75JsqaKSHkPGJToTD4VeQ4ppJoj908fBv5Z8hg8B6ScOoCjCzsJHXicIhapK7SbbrMKm7icPLXlN7mA1AdGtMWp,pGiR4bhFWpPrLj9un7gAIrToRoa6ObYLEUqHXvNgVcKAVd2uhv8ntIqAB4Zg4EbIC5eKiOp2AEa5fogXNIUbHsCULKmQZUvdYEYTnakifmFgYldF3F7UemjjIhPkrKEBcwL7oarZAE3oMnme8n4TqBr2cEy4Y4Ca5ZErAvnlWVw5MGmB9fl57qHWDlszQghglOkGZb29anTIIoUcvjOSgbdhjTizEejpAuMo6lreszwLgVGgI4JDVSxeK7tPUxVi,5Qve2JAjtZTe2ULquU0LjZgfpIdxyvmUey3mqe5AH5EhhCBmrrrH872Xttg6ynaIAVSNKSULaXwA6bZiTJlIQztVN5MlBmWF6SWQtXyp1F3MLBUPGQbjRyxDuGmpCNTO2GPlZNRgo7jijDQSaUTad4uM7Ug80FCQZxeIaMmUdo40TVNALNzY576lkJR15cwQ4sTD7Xa7D34BwbHaSBVQnDr7iAmyjtpoTu8NBhKGuXexMn45HK8EGr4h8yFWBQBl,S2sDscnmeg3NBd3gPZ4mC8TsQgPWt35G3TO3nXO6c9DxK7lhxpKpbQbMaDabHLtfdbZdga1yaUJgxk58E1RsUtcoAIETpcHEkZJujKDcoYteMSvQB7nBvjslRDCWGshbrqXuZ7ephAzUvvqIqpdRL8lZxKiqfbvAqNrTx1qljknoxca8LbGu9pbtOJ3ssMHGjYFOo5r7VpA2R0ZcB5oiDbi4ZJSe8C7OGCW6Y2UPMjVYYxbXwVwNxevNJ7MovIos,1KjmSRf8dRV057OL8DvCj8Ar30z0WljL1R0UliXOSn1I4NFvIgqSHY2hVan6RyOAqE6wdFwwZI7nUjzBWx7aVfcwUg4pZTdFzUz57nxhJqrONMrp9lZ5s5nNuIXjaPxdMAA8UFR87cTEHXgSNrmyw2loF4NhX9Z5Eyish1yJTpcGgFRuY8jXJHw7Rxs7fZY5XnYB7wfaFO7ZfQER1trv1AUwuMxHHajRqOjYliAmHyn6hjZ80CnMr4Q9Bm2eRCUH,sRgBHaOvQdhZi229Xkz69DuRhjDncyVOozqz2dKXLlz6RjqBA6miMh2vnw95WqO53GjJ5JkbYLVGcdj7lFxcw1y5f7g0hUaDxAbWrZCdZm6UvC6jiElThzxUY63aQTAI6F6GcCXmAZ2qA96cEkb6PhMWMxBDCevf7V6KVk0m1Uk37J2wqZFOuW8CiGcGL4xNA7xc81YsWavkx7K76jxJ0zVFgpi94cvN2NBVBRyhnpOZG6JMGgWgaY1tIqax0ZTg,KsJFPvjOzf9qupVhM8yW6Gt4PM1V2w8VppHWXf1ecbo4785uwxxKPkMFN9JW8WEKpHJodA5axYl8Jl0oizAag4Jp6e1B8GVJuOIoGe6Qz1YfqX3OLUMvKw53aavKRmWwCImbimgAphPuyalUllgxeUUNOGf2lXycZkHG4NJYajrwlEajsiFSZv2QyI9Jlvr9o9nI7f0duX30DAIYwLAw11MN6iwf1bh2DQuwC67h1m0QbpIBF09sSU6RTmyHxHUZ,qoDOuO4tUNxT9YjWOnnUMfzEN4m77seWdDLY6MSOFdMMldllMmXKRmRI8CbxVKJgtJb2NXvy753u4nLECqb2f0Un6Wvhs7KN7ekmDe0KhdVsTCkjR8TmB6rcJnpadXnpRo07qOaw5ycLCDqLfSh2im42mZGNTm5lwkn3otEyWFA3OwqpJtm6da7cbKwwLVbMUD37pPSTBkzTyEm3BEtn7FLFze3MlM6VkyEYhcZKqfP0qzTXH96avPGo2wDPkCxQ,68AcMnyzuxRLDvLkkMLd1LlU7V6MXqw8SqVJt227Q4RkztqWnsjjvwaFj0EfssbwVyZvhgWNkchrF2MjqHpeFjcw4ORkNovMKZ3kvBcrehotDcCsKfGpKIa9NyZ1kbNbOtrM7LcCHVzDtrvpCTyGBw2lLT0Ts9n4aepCpL3WYuAl4iuyYjE77OFdX79zw3xTaJlqnA61yn7yuxz5UojGHidWDLiY2yr6snDLBlCWEO3W8a4VMXLrKgFlk8fG5Q11,KDcU2F9Q7ZGNEdcGFRfnXQln0OoGVlpf2acaxghA53wsYDAVEIYC6rkoJuH1KKQSOWiYZQEPxhEIhwP8Si5dHImcTJCPoBmOpzwp5uMlPw4GR6SpUkOeXVROczSTMOd83oOFeFOILyWp5YJnXMmP3z7uynw32J7yzv26fC3iaJA8yUPjelXHNto2ztQV0FsFhfoweYQXtglNpla4rjQ85Fu5qbrp9jn8YaWKY6ZEpunXJ3boODxnh41d0g2y7FcX,x6BKRD7NbysMVOOIIm5W5hwURAlPvZxdNVntCrs7XF5JOZCdkG49H6adjRT6fKgBtNR7Xew8s3uAojR5iyw2oZZmELjkCMuihywKbb2uaLYdT6Pxwd8KVQGMf0wX9S40sZNxR2HnCuHPpbLq79etp54a7HjWJ1BLr5Ulqfnz7vsEDHq38t72AlEqw9PcoEGeoWofkR4or08sjrJmYXW4oQ29c1uPIA4bsC4M29rj8hmzg5Q4pQOQ4GyapVyvUimx,kjzzecpgU1ZPELwJTxz3OecQi5vxeETYyCjVnshJGhlXjbyZaD0jNhaehJ2JQ4QjYhqlUIsPQrXaYATUR32Ry1KFqFkgDeQKLi59b69b7xOAgkOEtR5wIAqCfqN8pfDgB2Ow1u36oaeVCRaMtql3wFv8JBu5VKbONoHa17zGL7U8tjQtUDWGry7ywa45VuvWlODwNP4wesf8uEVZoA5wn9pdMsHFpEvSMTO4E1KjVAUOcRewDrvhg6NixZb7NGA0,SZApeh0ntAjoaoXbmtO8pQdRBzEhZyA99NlIQLA6P5RvDHRC77ce5k3FqE8L74MNLCYBQTFPiEQdxq0uNBe8FEXJw77013Geh1LZJM8VBofEuuRfbLU8driGAaJSWj8ndqEEbwqJzv0rjAFg1cAhdkBZra3cxRuZpGkMF7NEGtIBQpT9yuqGaSy5Aha0WGQzC6ip9eiqMSvo2KjRDBwpKWgZBKgLL0dcea052XEr6CpWIVPlEK3lTv6HqoR3OBWD,qzt89isNEvkRvAy5TOknUB1yOmruWgIIW2GXC4wJS12lWg8eNxtlaQV5drzFDvZHr7E4VFCLBthtMisZTmMhI5aK3VP7HAc2lNoVlxHTM8Fpk4DVeDKwEIMTECI00y0apxnfXkBK2DajYGd5tjcucdXauS4rQwHYHHCm8vDzFdh4w9bu1Ikrrr5N7ODv4RHBalZfknIj8d8wXhHWKUlWsEuMLgSWh1ZaUUz4d1cTwAqk09RyHmOxTAAmTv8sMFfa,j3JTBNOFuHYkKmwId8A3c5TYAehLDWv9shj95h07a7mh2mAQUpRhVdQ6S4NbjhDBOjD7VRHoSDs4BlxLx9yhtuqvkaa7hJPdiSWAi28WlFVOGcspF6iLTWR3ZBCe5TOTavVg0ip2iF1SpDMbjwf3v4HSF0KwYPXbhwtWEgMtl8yZVdWWGYctltiQztAfWiT1kuEGlCHnzIzrCl3YeSqZpFlpZcglTU2YAzIxco4rUvTXYkdweJ44TCqQ9MgMXfsg,CGHyPOVtTAa1b1CRerP1DJIOwbanxxh276HMhIXEmGFonaKAYMAedcS8gwLgd5o3jSTUeSUyKxRdrb6aN1EjPeaeLRRDpZbFqPf2IysQJSL4aW9O6CWO100DYZbXpogZoAN1yphvnMF3RRjY1hX2JLnZTuyk9VEwxaoJ8J0ost7sAIQgk69Pq7hDMTsuad7eqDE2TBKKGh3ZDAmSxILQyQKF7202umpNedK8qYx2hmfITBJINpqv8TjIImc8P7dN,B0GEZBJjwpgkmOBhf606eV85xlKRwXenj3rYyg2i6TnvIpsaShjS1y5xDn0zLFMNDVZHtgrVOsdpGvBF3JMEJ3A0D39O9Fhat32k55R9hpthGk6X6ApTUvD1Q2iddQNhUbf5fxAoZ1aWOuCykc31f3vn0FboP4VIoJX4DHZQjWhjvgvZreGVm2aUNgtsPvWGis6mgJTxOIrVv6HGlW2bKPG7ky6kUMg0aX0T4qLdzU9oWNy1JKsHmYFJODantuau,o11ma8ggQEOUzhoHixbC7lTkC2nmjawVtnaGhEfCWMSfwuWmN6tzrJIxxUtnIonlN350PBALj0DSkAM4DedN76eEBdBl3diwHv9CZE0GGXsJ5NfW85LYLg2wxSef43ceJUz6KhTtPu6H51HVwqgfzMA8s3EGP50Z8s2XUfFW7qKRPiaqicW5KdcKWElZFsv4Fkh1LEsxXimjHVROHu5PZICxOu3t5aSyw90mJHb4JzL9oWnu0ozmaT9lXlVYcVhC,NtYSfdNOeLfuk0TiGFcv8RoQvLcpTYBd9ev6Rjr0mlpV6xv4BVBfM4QXfU4Hy5xgRx2eMABqem8ZvZieLmx3P1owbVthXOzBFNhk9D1vuFLppqYUsdkZVbT9tGIF0rg4szaOHphca0zPFRT6bXRexXT0VxrXNQa3KjDvDDwsJy0L50BVTtvZOWokYuRTB8KEWUQy0Dd7j2u8FEwmFZXMWAqwKcYCoMVatXAksknATgI49igc8iQVDzGU06pAa46a,LQui72OmWc9XvMA6PwGZtF9iSLLsEk9sEjTa18LH2uvG0wPDQE2efhWAeTUBans77cpdYO9XyuXx4eGkhHQ7bB2HUMcu0YPcenqBYa19cf7iGITuKZ7XGkPTh5PZpg5oRXmsFtnzoWR1UXkGrpUsEXZks54qhIM0Wb4DBUnRRFLBzNsfWDWOPz79QCBg6uLLzXh8JxogAmF5rbwJZq9wWFo77tvLuXJz5dVo4jJ9x7UnXacwdZt42SbvF2Pz2mHp,aOnCUvt29jV12I2xC5ZrXiu94Er4U3LMDiV2erjAeAVstnxidkJBvfzjdXUmQldKyLm6az1ir8wH8xbvPkIl01FsrAGITbYBPsyIfNQ271M3WBUKp5rQPxAYmXe3ibJRQsbgi3669qyP2EI8kIOk8Vn09Ns5EUEc2etQHpiPw7ufll9RQ9i45VHln3vrc0LFes5N3Q1RR6sNzg9RotAwlJwggCIFBMTmkTtSUa4UM6QEDjdXGFwqigQRPGzF4zaj,8kbUPeO8Ga3yTqanYa8Oxeyo3OYOEvNroDG3zGpKnNxbjlGRDIGicM7AbVP2KSdNSfDoX5ehBTMM4Zok1wSUmKqymnXe5kP90fHgbuuWsSnaHQ9kUWuHl7zL2vYBTttkf3awRb4KwubmoGMFl0pdzvbYiPySMUe8Q2CtT1Q4ZBxEhi2Bp4HqDunNH6xuucgUf2K7ZXwX5eKRwhaPOzMftWh6imsya5J1bLNUk1QX7k58WmX1Uuju16GSm7LkBThA,DzAk1yCD6cR0wjBLyK2Wrurym5IL3X9jh5T4NOkKacbdqLBI5MSF7SxRUbn2FaBDFMeE71wNUHDmy2imBtnCBALqXTfDLPztDnWFqy3bvRInEpA4vFt3HZAOeskDe4d72zi2KcVMtcx0ZwsgT1tId6xLjX70voY2NzAq3Tdjo1K8nKDsLgFhdHxwv6KNSJACx9vHsZYfnbRwb99oRVqYsNqxocPa122yLGZcDr2U44rVaLR8CzugkFEg8FywewMo,mDVmzbjLC0aL6oB7HqiSaFtGyGpxzdF4ISGLiCdLFslA9hx4h2WMl7PBFaI3rnYVVxyGde9TK6HcGtC9OEfyf383bkzZUb1lrhMQYkf84XvCmtLONfDrSsSc4QJcXNVqMJRiRnoHZHsfvmC2F8FD2VB1EOotDCyjX20eQzH9bWjwOWCvXojwq5iUJIjW5rBly3HH0GUd6G4JkilK1KAQBWDscUzV7vDbvqt4D5aqfwYYmQ00iV2wacNDQ4lVx0if,apMgp6IquImmAIf6JjlBJBsT4QNkRfUKvCvD32r9A5CXVgGPW52z7btbz8CkEcEUAgMBhajsY9bEOTF5IpTqskCfasdDmGyxICwFjG99X4EGpcVB9dH2M324wtFrrkA1DHPfprPhMdfY79epHmgD6US7AJGEslURP4OQvrE3kMPGu3YTizMBVu1EnQ2h87Xf9pVmO0tL3JjtkdpDXZhMy7eJPZopm95DwhCWQCU7P9fA0tOmcpXAmUuxpv82ikGX,p9q13W55PnfdHyJO17VDC7nR5bzhKCtw7fpCYbx7iO8SttXcS1MEi0sJJ8DpiGBKiAYa2u3T9pY80MaGlTiyHeDNL1yshGxrX2UdvqCmZnVrlPNRfPT36CTbBd9ujZF9lgJtTT7meQonCYNBIFyPsAhxqErPGzY50bpt49yAPmQTgH6Iz97XTLc59pGUITVXlXhSanpKtf64jaTLMKyA5JlZ0PugHWMiSnteFo0B3SUgq5Fn1v6KYHkJ0NerXsf7,ixvz0xiUpr1XQEtLRM0pnnOUq5XMiuO6RkGjYEPnUlVatG7fHVuGlKCmwZ3orESCSY3KeGeA3Nn7qCcjcOJBGuvEGSVzAIBqH9jYcFSfa0mhcOTqkarTBaqSSiD7wAeRlXdU6NdjEbWT1Q5rnSB8EFEKfGpeaKoNweAIinqgSkk2sbWIqdfbhMuDjLAvXWuNMMySrSScO9VgpLCm9YmTfBwVjtTCsfuQcKPr0lDohYCyY7sDJUAWgHwxz8ghpgyb,EbBSzHzcRTpBZaAuVtRCVdhQGOGOqdD7itXU9Jwf5JZ8hrGjM7ZUUDjvVgKLp0mPFrruyR4PDsAfsX5uR87BhuHmlm6k0MSIQAhTE10bNhA8SEBLdQawvu4PNMcuiqKjphDi0rfcvoN6nQnN4VxarKPZGDOdxnmSWcAFPQbQ9WG1zLAkQ4SCJOs4rV9W6OY19Ks5MzDl6BsIMoqgRrnac7EKNPUSpFQq5IdBpH6rx1olKuDtsOIGw8mzrBf4z2Z6,Ef759U8rE9aZS4ig23tM3Gz7XeJaZRhNgZK8tWgDF3L3U7ilHwIpeUfdMqrcBKdIMQiFXCkEATJZaDeZSbkRPJraYGbNz0L1ZbTikKnVJArNA3hpcw5RfNYs3JRPgJg2dhmoYD1X82Qy3PlDROD67J3ruPJqBBvv5c2amsAsQMNRLYOwhbDfa48DImJEnpJwDWKYsKF7Ks6vhaxFRidBwv0zV0rvGiBrUXN4clRPlpqzlo0yxCNn6qzhovnGO7P9,e9BGWyTJpu6Q4eBp7ndxS3fO5efNnDZsGzsC6RZyE0hV4vqbSZFya88fARbLkGpZDCsujVqL6lwo7zvUSU9o5nPCTubwdnT36UkzufAhY2MwybrW9wtj6qDYVZR8siM60hQJgRY5aJRhV1J4sXwFtfxxSrslO8HXfpOO8rBlHwNJzJIItViaabzJtv0yV2JgufukFJLUGSksgSERGXmKZq5t8LuGX0QLWqQ8Mb7p64lQBZ74ysfaz7BS60nXgOM6,w0qvti9Hpe3gtRqmQ6muoeddoXmbtYaGA6VhXQw32JEaXm3TKJ3LF2exfAeU5uvLh76DaCuNPnS1yzpqJkABKXbo2Er5pGQKzqDjvtlJbknIlcD6mtG03qXARVz3O7nAN94C2ImzP6Z70v48tgiVJh99k1XmabjoXBSO9YR9aCq9DMlYmcf3B8iSMGi6XxC6Le7fHXQhhTunQ8YiU2tknkMNhl2BBgn8klFoyvrPptJDMXxiruH2hSP9gyTjWLvx,aHby1HRpa9a7bTY9rW1KQxpGMzXs3ttV8Ohrkpa9esh11y1kuTc2hYgGnpu9C1EsMy5j2musGxNlWArLqfrKBe9ROaO3KXje9rrx7tbMKkDC01nIY59SMKAioPvXOX7tudqUwEAs5TbZYdAQHzmn4TbTTQS9xD8DRLkfbam0uHu3a3jjnk6x6K9OFZSFLnq0nI1gIsxVGyKLzBXy1t2AKLyUhNoLDGCJQmckTVb3Nvij523a8GAjJiExh8mxltWQ,jxotqCiFDkvR4wBmWcZuxagEdbY2y4GNTjCbE33aQ2WrsQwHUZ14f1sYVzR0O8quhmN5zHLiqD20xngpU9xqzNUYOL829HHlDNu58aDASWVXc7STFR4oRjNUCBz0iSt9qgdfNcsFnogTN0C9Cy9DuHrGL4D1zC5VuTXaYknzC3pqv3cEbV0hdspK5P6XxIXgmhug9F07yKAWAxhYOzDY2UG6wxPtG56Cbu5XbE48wDWyj8Mx6MREbogjS0BGndSx,Huak9miK1xyKiSxfa4D0enaVgFk8JtdlJ1zpD160hWCyN4z0GsPXS2KZZgkLB43PVYTLuyFugydFBwvSj7gxBJ9yQ3yFJUQ1xdEogm7AaVD6DM5AzPzupq4RDDHT9Tvgq35SbKxa4VWT4q4m1royNubmqZZJG0aYxrcmtw3DHWOPFBkWEPRDoWcPM3AhgfLESwFsqSUmvPwhoJUWO8xulyPtnt2pTAGnEjKcJUokq7kcDcEzgwQJxjFPfozJcokV,i3qzODWane33A2evVnrpeC2YGPd75EcCAc7O2a4He0WI0hUcJfruWEop2bo62Mz1B4vmuzXnlpMB1WXmUKM4OCTGPlYUFiAR2C8opMPA2ZKDvWdLDzVx9DYEWFfb2NkVYBT5IfNVjZg58Yp43bEDdxdUsRfVHcRQzQBn9S7gfTDPW6Cf03vMWRpKjrU6GyJtZIE1S9Cw3MsnK7ReTmz3z3p6guKP2pezg7c5lpLfRWj9mGpaVfXFWPVFxXdvzKcr,Dl9z3bciyiYzg5hgGo6XyCzIz7SNx90eDqZOssksRv79vAzBOU8rooTBTMZBibKRGSZqevTIPNkQxE9SK1j8YduGiCdlJ0osNjFSrcuAJuXkzhew3nGxmlcB3IGyUXbTmigH5CHUs4hM0clebg0AoH50bxNwaglZp4ZU7qA1B9CThPkJo8QbXZGRRevQeAbfdiWHTWE5OUkL76MH2qG7srPBxqpDXpAQsmvH0AqevCTKYBa6pqi1gUndkpf9dCE1,X6KxF3gbJE2UtcekREw99sC9mAdLrC9JTJcI01cljQZIi0bB37sFGMYVbmdaueLb3PDPjS4yNy5HbZ5NCzxkpTyShQHGYPKzS8GfcWNrQNhd9CtT1g0q95T2Ln745JtbfCWbf8WiuEZDL9YGO8T95jMjkm4bGke31XdptVWBx002n0XrsPmrjKSrI9GNpP1Mn2lxLEMTRDRom37XH4QrR8wq030s3u4XMrLg44IWcY8mhwt0xIBrtyl7fpXr66Gn,a3gpFyNEp4ZQE9umHvzrXBQ4BcsUi90doH4gZqSFoLQMQmXe3JGz8gFfDsgNUjz6OrsG06NCVggvdpj7mTzuADsn8eaU5WS8C1xIt3QrUX0ghF2Tbp3p6KYmOMZ0Xjqau1Rw6hGHfsDgmkB7QFg4Ai7WJCB2Nhmva4255zfN2XvntSvDFBxP28BlKuaLE5MN6kYyVjDbmHUFKOXKBoN4b3Wqt6M4XL3ikJfKWBbB2rYwDYlVqj42lcH1GjH1eDRq,ExrcI695nZAuNBXy6eynDdxpzeKa2Dbs4RxuiQ0HtWgBikQ0pZEgCtS5QIGexXLPnThJGbXONkJsylHf8GBNR1dzbWyvA3tXSD6SyjLekmJREU8eFLyXcyW82OcPFsuhzqZXEACTxB64FTnW9ETlD2gWcbiR4tXBzcurfQfbNBBAPWyXDciRo7GVkfA1JQccHIa2MDK2mM6uYsbJ5jOUa1oJp9NWu2tCUFdPUNX2p5y9c2nGy730Jw45Dnc7iADK,ALTzaxWDWzYl7qIR4v6wqRImxn9osyeY5oR8k9RXwCumbZaO1tLNfzY8hghIjr0VhXRHDT77qtABMp6AKtA24BhtUfPngcMOK8A4TG8wGT34VLOKuGDHAa48Ua3XIgs1zySkLRmG3O9XpeXcv8Nr3iznbC5QYIXTM5yjM3Uzxf9e7p5dyCMjueln69wDfvlWh3899gmhKjgThXs5ZneF1XPq0Z6Oa5pTaOd2COSEIxVy0CVIrqgdrMM1iiCeRDi7,1ZYk6FdgQCq2IT73W16EOzmjPr1aQK3kiGnv06tYBCRTqjcQ3c8Pjb1EZbY0iS96Lx3zqPgupa3aWyvdJ9lPlHrIa8zEk6yIfo2FKJHWy3LFCeyaAIRlAmI8HHPiX1OsS1u1hX5Ojpa1u8nz0GF3BBN5Egq3ZGKY0zAc99K7z6ZR6AWIGoNvgykGMuwwRMlXOshpDcYva6jZ5x4CmZiwllcoMDOADv9ODeMYjgE4wJF5ZKSHS7fBLFESrRiuNDTq,dY85F12kuwILTd3UlvDyX1kJZdmHFGGAgGbsk9Zhn5WyTRybCkMSIPUa4ChUDE234OWJyv1Cfn4PlDOKOZRnZpJx0LwUe4PWwfPbTOPZhQzdnPl0QaRVUW4Tw1D6ddInYveShee7rvRJz3J3KkSMmUyE8O4XsSUQHBF25aOz9Kl6LuDw1cPyaHwHacVIRprBXmm8sfNt9mvn2wXEfMNB32G43d6lc3RpTGp0LVmAuVagnVQRuwGBbqRUaxNSwTr9,S9ObQfyvwZAZEqTGssAiIO5c8RQDAkKIMOj8w5SYhsamThbVCTWSQouNQd4P13aGrDeepGlfYixetlOdRBBDoe5OgsohGxFghoLrCSDgwqEIFA7IB2jAD6re3hHyNdN0KEYNhbtk5px6a1df7gEHQAq5Nn0F0t7ldztR9harim2G86KnD3zwT3DIVJkeTYOzX2Zh242DkOHSeHUEL6E0AmyGmGjCLNwjRgfnpM4QqxYzbJsTjcGENqPk3QB5tGof,pM3cWlcO4wZGHBpIZsaR7fxqc1Bqv3yoSA997ZSALJuzLETyePj7kVrCruzwgi7klfdNWCHmcxlNpcZMcE2hfrTxZHwzwTld3xavuSGlSKpWJ9nlveHTH2zoCmeOSTqSQuQdGu6saJlzaY7FntxbYCZyAwu4VW1b4NSVcLTTdrw7hmn1Fkx0PSuAWcduTo7FLFT949SfR66LWgPFdKw6UTYofRkx6VESR9QpxyyJt16eOjHhv3ySJCLrXDxaWOfq,xS8XiWVOYxczqhLkxZcEwum0B6pibaIzwoFZf44NgQd8cA8RUg6a4ckByz9JDPo13jx8ICnnMbwQxh'
2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [3, 4, 6, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (14235 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 4, 8]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [3, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client di,sconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:13:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:65639090-B4AF-4DEF-914A-52E21168A9FB
,[ThaliCore] Session.session(_:peer:didChange:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6C05AD67-A1F8-454C-9056-1AD3142D948D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60950
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EGFCaVOkT8aLscdrEcTmao3gLOV0Ictd","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D00BC9A6-5676-4EAE-B32C-0930BC0FF439
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
[ThaliCore] Browser.startListe,ning
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C05AD67-A1F8-454C-9056-1AD3142D94,8D","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C05AD67-A1F8-454C-9056-1AD3142D948D, (syncValue: Lsziy9SHv9KNVk9VryxqADqCe3OkINq5)'
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D5997C9-1AFA-49E8-8859-3D3CF8615E09","generation":0}'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FCE18425-0E52-4D6C-8613-24BC52DDA992","generation":0}'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,05AD67-A1F8-454C-9056-1AD3142D948D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Lsziy9SHv9KNVk9VryxqADqCe3OkINq5","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Lsziy9SHv9KNVk9VryxqADqCe3OkINq5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5D5997C9-1AFA-49E8-8859-3D3CF8615E09 (syncValue: C8RhqkKnoi6e8dWyof1D86K,ZfuXQHsez)'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D5997C9-1AFA-49E8-8859-3D3CF,8615E09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:26187934-C455-4945-8564-1D51ABED97B4
[ThaliCore] Session.session(_:peer:didChange:) peer:26187934-C455-4945-8564-1D51ABED97B4 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:26187934-C455-4945-8564-1D51ABED97B4
,[ThaliCore] Session.session(_:peer:didChange:) peer:26187934-C455-4945-8564-1D51ABED97B4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:26187934-C455-4945-8564-1D51ABED97B4
[ThaliCore] Session.startOutputStream(with:) peer:26187934-C455-4945-8564-1D51ABED97B4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [3, 4, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] VirtualSocket.closeSt,reams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3, 4]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5D,5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"C8RhqkKnoi6e8dWyof1D86KZfuXQHsez","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'C8RhqkKnoi6e8dWyof1D86KZfuXQHsez', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 53598C96-6AC0-493D-B665-40226186CD36 (syncValue: z4efXtx5zbF11sjG0VFwPG0,m8OmUwX4D)'
2017-07-24 12:14:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226,186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:14:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60974
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"z4efXtx5zbF11sjG0VFwPG0m8OmUwX4D",,"error":null,"portNumber":60974}'
2017-07-24 12:14:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'z4efXtx5zbF11sjG0VFwPG0m8OmUwX4D', error: 'null', listeningPort: '60974''
,Connecting to the localhost:60974
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 4, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:60974
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
# teardown
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [3, 4]
,2017-07-24 12:14:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D00BC9A6-5676-4EAE-B32C-0930BC0FF439
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:53598C96-6AC0-493D-B665-40226186CD36
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60974
[ThaliCore] Session.disconnect() p,eer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:26187934-C455-4945-8564-1D51ABED97B4 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:26187934-C455-4945-8564-1D51ABED97B4
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:12 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:26187934-C455-4945-8564-1D51ABED97B4
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:453E9D44-4CC9-41AA-81C6-484AB3F7CC29
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:737E56A2-2A45-4574-AF5C-F65E503621CA
[ThaliCore] Browser.startList,ening
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
2017-07-24 12:14:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 53598C96-6AC0-493D-B665-40226186CD36, (syncValue: oaOmp5jaguv0xbyRQ8MzLvMCd0HRSGe6)'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "53598C96-6AC0-493D-B665-4022618,6CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
2017-07-24 12:14:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FCE18425-0E52-4D6C-8613-24BC52DDA992","generation":0}'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B315A267-2416-4D99-838E-75A6F373469D","generation":0}'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,3598C96-6AC0-493D-B665-40226186CD36", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:53598C96-6AC0-493D-B665-40226186CD36:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:53,598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:53598C96,-6AC0-493D-B665-40226186CD36 error: max retries exceeded
2017-07-24 12:14:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oaOmp5jaguv0xbyRQ8MzLvMCd0HRSGe6","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oaOmp5jaguv0xbyRQ8MzLvMCd0HRSGe6', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:14:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FCE18425-0E52-4D6C-8613-24BC52DDA992 (syncValue: 0FN8qaC,UQRgWhLjmV2Xh5IOm06kAVESp)'
2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FCE18425-0E52,-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FC,E18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,CE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FC,E18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,CE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FC,E18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,CE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0FN8qaCUQRgWhLjmV2Xh5IOm06kAVESp","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0FN8qaCUQRgWhLjmV2Xh5IOm06kAVESp', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8182CC2F-9EF8-4D77-B70E-B56490A7A0EF (syncValue: 1iOw6OyuYpt9XOfJAU4uWPa,Y8m72HAAZ)'
2017-07-24 12:14:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8182CC2F-9EF8-4D77-B70E-B5649,0A7A0EF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
2017-07-24 12:14:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
2017-07-24 12:14:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60996
2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1iOw6OyuYpt9XOfJAU4uWPaY8m72HAAZ",,"error":null,"portNumber":60996}'
2017-07-24 12:14:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1iOw6OyuYpt9XOfJAU4uWPaY8m72HAAZ', error: 'null', listeningPort: '60996''
,Connecting to the localhost:60996
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,Connected to the localhost:60996
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 4, 11]
,2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-24 12:14:36 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3, 4]
,ok 102 got the same data back
,# teardown
,2017-07-24 12:14:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:14:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:14:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:453E9D44-4CC9-41AA-81C6-484AB3F7CC29
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60996
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] Session.deinit peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3064CC08-2B33-48B0-AF57-FE957084B221
[ThaliCore] Browser.startListening
2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:14:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start ,listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "62A427F4-39CB-44D6-8DAF-F8C47295B57B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:62A427F4-39CB-44D6-8DAF-F8C47295B57B
2017-07-24 1,2:14:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}]'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"53598C96-6AC0-493D-B665-40226186CD36","generation":0}'
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}]'
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62A427F4-39CB-44D6-8DAF-F8C47295B57B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62A427F4-39CB-44D6-8DAF-F8C47295B57B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
2017-07-24 12:14:39 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D63D92FE-3772-48E1-B182-B4E7084DA19C","generation":0}]'
2017-07-24 12:14:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D63D92FE-3772-48E1-B182-B4E7084DA19C","generation":0}'
2017-07-24 12:14:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,12:14:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:62A427F4-39CB-44D6-8DAF-F,8C47295B57B
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-24 12:14:43 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1DA5DC70-EFC8-40DC-AD41-6848DDEE97A1
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44E0B5A9-84B6-4BA1-8838-5240A51B370B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:44E0B5A9-84B6-4BA1-8838-5240A51B370B
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:44E0B5A9-84B6-4BA1-8838-5240A51B370B
ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 12:14:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 12:14:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 12:14:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9a0d8263-8087-4a21-9f4a-04605d6af263 error: startListeningNotActive
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"vjIpHITbdaWLqEk0CgHIxSuujSaohfBD","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:46 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92343401-AEBC-4527-B4FC-B85EDF15C214
,[ThaliCore] Browser.startListening
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JytMhLwVJWPEQFy49Hd1yV6gT9AW1GAp","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"D63D92FE-3772-48E1-B182-B4E7084DA19C","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D63D92FE-3772-48E1-B182-B4E7084DA19C","generation":0}'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}]'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 12:14:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4F38090-D7FB-4259-AF01-AA68A5EDC6E7
,[ThaliCore] Browser.startListening
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:e46980a6-bff0-4221-8ea0-47c26e11004a
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B11581D3-CDC4-4C93-A560-BD4A6375972C
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
[ThaliCore] Browser.startListening
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D63D92FE-3772-48E1-B182-B4E7084DA19C","generation":0}'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D63D92FE-3772-48E1-B182-B4E7084DA19C (syncValue: IoEeamsByZwLyDUOaIOABRYCgCUbzwYN)'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA
[ThaliCore] Advertiser: session connected Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E62C46C-7157-4AC0-8447-5248FCCDBD3C","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"782C8DC0-393C-431F-B729-125C1A096E99","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,3D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA
,[ThaliCore] Session.session(_:peer:didChange:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA
[ThaliCore] Session.startOutputStream(with:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 4, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D6,3D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[ThaliCore] Advertiser: session connected Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IoEeamsByZwLyDUOaIOABRYCgCUbzwYN","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IoEeamsByZwLyDUOaIOABRYCgCUbzwYN', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8E62C46C-7157-4AC0-8447-5248FCCDBD3C (syncValue: H0bZlCWSX19NuvsfYRg4uZ8aT2sSA5BP)'
,2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[ThaliCore] Session.startOutputStream(with:) peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [3, 4, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61012
2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H0bZlCWSX19NuvsfYRg4uZ8aT2sSA5BP","error":null,"portNumber":61012}'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'H0bZlCWSX19NuvsfYRg4uZ8aT2sSA5BP', error: 'null', listeningPort: '61012''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) found active relay
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IKXXIZQyCn6ZLh6KTgt39KDKKmxwAP3R","error":null,"portNumber":61012}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [3, 4, 12, 13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) found active relay
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YK008vsuAyCHs6cVykVgslxwxxck3IH4","error":null,"portNumber":61012}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,2017-07-24 12:15:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [3, 4, 13, 14]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [3, 4, 14]
,2017-07-24 12:15:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:15:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B11581D3-CDC4-4C93-A560-BD4A6375972C
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61012
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:14 [3, 4]
[ThaliCore] Session.disconnect() peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[ThaliCore] Sessio,n.deinit peer:AFE4AF79-A6E3-437E-9F0F-E3EE269535CF
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"H0bZlCWSX19NuvsfYRg4uZ8aT2sSA5BP","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
,[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 12:15:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 12:15:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 12:15:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61015'
ok 149 Should throw
,# teardown
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61017'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61020'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 61024'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 61029'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 61033'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 61037'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 61041'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 61045'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-24 12:15:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 12:15:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 61097'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 61101'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:10 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 61104'
,ok 196 port must be in range
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 61105'
,ok 197 second start should return same port
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'listening 61107'
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61109
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
[ThaliCore] Browser.startListening
2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:782C8DC0-393C-431F-B729-125C1A096E99:0
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E62C46C-7157-4AC0-8447-5248FCCDBD,3C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8E62C46C-7157-4AC0-8447-5248FCCDBD3C, (syncValue: EPiomyN5Ty7whYRKLk3GUCqDhESP7KSh)'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"782C8DC0-393C-431F-B729-125C1A096E99","generation":0}'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2","generation":0}'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E4D774A-7882-49FA-98A2-2FB6F737A46A","generation":0}'
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8E,62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EPiomyN5Ty7whYRKLk3GUCqDhESP7KSh","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EPiomyN5Ty7whYRKLk3GUCqDhESP7KSh', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 782C8DC0-393C-431F-B729-125C1A096E99 (syncValue: y2EHmMooqY8IOeKLMKLnT4D,N7d30qqsc)'
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:782C8DC0-393C-431F-B729-125C1,A096E99:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90
[ThaliCore] Advertiser: session connected Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90
,[ThaliCore] Session.session(_:peer:didChange:) peer:782C8DC0-393C-431F-B729-125C1A096E99:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:782C8DC0-393C-431F-B729-125C1A096E99:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: connecting -> connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:782C8DC0-393C-431F-B729-125C1A096E99:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066
[ThaliCore] Advertiser: session connected Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:782C8DC0-393C-431F-B729-125C1A096E99:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:78,2C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,82C8DC0-393C-431F-B729-125C1A096E99", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y2EHmMooqY8IOeKLMKLnT4DN7d30qqsc","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y2EHmMooqY8IOeKLMKLnT4DN7d30qqsc', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2 (syncValue: a82pSzFi0eUuz3SlBFcGhfk,cuouzU7rV)'
2017-07-24 12:15:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6,222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61123
,2017-07-24 12:15:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a82pSzFi0eUuz3SlBFcGhfkcuouzU7rV","error":null,"portNumber":61123}'
,2017-07-24 12:15:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a82pSzFi0eUuz3SlBFcGhfkcuouzU7rV', error: 'null', listeningPort: '61123''
,ok 210 should be equal
,2017-07-24 12:15:28 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E4D774A-7882-49FA-98A2-2FB6F737A46A (syncValue: BbTI3rSn5VYUTAKhgrtROzEpw4jDzMrT)'
,2017-07-24 12:15:28 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61127
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BbTI3rSn5VYUTAKhgrtROzEpw4jDzMrT",,"error":null,"portNumber":61127}'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BbTI3rSn5VYUTAKhgrtROzEpw4jDzMrT', error: 'null', listeningPort: '61127''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61123
[ThaliCore] Session.disconnect() p,eer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2F4A4E81-4725-4348-9DB6-439977FBC066
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61127
,[ThaliCore] Session.disconnect() peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A
2017-07-24 12:15:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BbTI3rSn5VYUTAKhgrtROzEpw4jDzMrT","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:2F4A4E81-4725-4348-9DB6-439977FBC066
[ThaliCore] AdvertiserRelay.deinit
,# Multiple local http requests
,listening on 61129
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:15:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24, 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:161D7F1C-A29F-4896-AC9A-D46CC97A4B88
2017-07-24 1,2:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
[ThaliCore] Browser.startListening
2017-07-24 12:15:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-07-24 12:15:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 12:15:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.foundPeer,Handler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2 (syncValue: U63JJa39AioLuhgx56rVecBbHndqEFRW)'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E4D774A-7882-49FA-98A2-2FB6F737A46A","generation":0}'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9C,47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9B88E045-E289-49A1-A686-335529ED42F5
[ThaliCore] Advertiser: session connected Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U63JJa39AioLuhgx56rVecBbHndqEFRW","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U63JJa39AioLuhgx56rVecBbHndqEFRW', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D9B3E1DE-3AB4-4E08-AD80-781C08B55D07 (syncValue: fxJVgUa5nhvtzv0rXSovomW,7iLAUQJ3W)'
2017-07-24 12:15:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9B88E045-E289-49A1-A686-335529ED42F5
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61145
,2017-07-24 12:15:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fxJVgUa5nhvtzv0rXSovomW7iLAUQJ3W","error":null,"portNumber":61145}'
,2017-07-24 12:15:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fxJVgUa5nhvtzv0rXSovomW7iLAUQJ3W', error: 'null', listeningPort: '61145''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-24 12:15:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7B6BF29-41D3-42E8-899C-68B2A3229814 (syncValue: xVN2iRD6s7eMCuvUcPL8ibpFVnvSNagI)'
,2017-07-24 12:15:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61151
,2017-07-24 12:15:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xVN2iRD6s7eMCuvUcPL8ibpFVnvSNagI","error":null,"portNumber":61151}'
,2017-07-24 12:15:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xVN2iRD6s7eMCuvUcPL8ibpFVnvSNagI', error: 'null', listeningPort: '61151''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
[ThaliCore] Advertiser: session connected Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9B88E045-E289-49A1-A686-335529ED42F5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] Session.s,ession(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61151
[ThaliCore], Session.disconnect() peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'mul,tiConnectResolved: {"syncValue":"xVN2iRD6s7eMCuvUcPL8ibpFVnvSNagI","error":"Session disconnected","portNumber":null}'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] Session.deinit peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,12:15:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:161D7F1C-A29F-4896-AC9A-D46CC97A4B88
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61145
[ThaliCore] Session.disconnect() peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:A7B6BF29-41D3-42E8-899C-68B2A3229814
,2017-07-24 12:15:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:15:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:00 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'listening 61155'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 61156'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3A5FA4F-B9D5-46DD-AFCB-8B11BAD5DC46
,[ThaliCore] Browser.startListening
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActiv,e":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 61157'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BB5D8E6-80A6-4F49-B005-2652B6361EEA", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:0BB5D8E6-80A6-4F49-B005-2652B6361EEA
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:1,6:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0BB5D8E6-80A6-4F49-B005-2652B6361EEA", gen,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:0BB5D8E6-80A6-4F49-B005-2652B6361EEA
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0BB5D8E6-80A6-4F49-B005-2652B6361EEA
,[ThaliCore] Advertiser.stopAdvertising() peerID:0BB5D8E6-80A6-4F49-B005-2652B6361EEA
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'listening 61160'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 12:16:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'listening 61161'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA12015A-CADA-46A1-AD09-EABF5B44FAED
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A91C600-FB51-46C7-81B4-00EF2F76B86E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9A91C600-FB51-46C7-81B4-00EF2F76B86E
2017-07-24 1,2:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9A91C600-FB51-46C7-81B4-00EF2F76B86E
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-24 12:16:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertis,ingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:04, - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'listening 61164'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:861173DF-EC8A-471F-BD32-75A3AE4168C7
[ThaliCore] Browser.startListening
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A29BFD25-93EA-4C3E-83C3-DE4493007BBA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A29BFD25-93EA-4C3E-83C3-DE4493007BBA
2017-07-24 12:16:04 - DEBUG thaliM,o,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started",:false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A29BFD25-93EA-4C3E-83C3-DE4493007BBA
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'listening 61166'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F7D91543-254D-49DF-A46B-73EA14CF4D8A
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7F14AC5A-E7A7-4F02-9B91-69A70F991993", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7F14AC5A-E7A7-4F02-9B91-69A70F991993
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7F14AC5A-E7A7-4F02-9B91-69A70F991993
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-24 12:16:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:05 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 12:16:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 12:16:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 12:16:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 12:16:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 12:16:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 12:16:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 12:16:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 12:16:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 12:16:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'listening 61169'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE5D4DC7-2423-40E5-9803-F68A1E1C41E9
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 61170'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1EEF88B4-98E7-4E90-AB50-C1B62BC652D7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1EEF88B4-98E7-4E90-AB50-C1B62BC652D7
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1EEF88B4-98E7-4E90-AB50-C1B62BC652D7
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 61172'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'listening 61173'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20C39E06-6E57-4412-A15F-096B7D5F51C3
[ThaliCore] Browser.startListening
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9906C66-2D3F-4A8F-9855-5956FF1755D0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9906C66-2D3F-4A8F-9855-5956FF1755D0
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD,80-781C08B55D07","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-4,1D3-42E8-899C-68B2A3229814","generation":0}]'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E9906C66-2D3F-4A8F-9855-5956FF1755D0
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:13 - I,NFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":,null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:13 - DEBUG thaliMob,ileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:13 - DEBUG mak,eIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'listening 61175'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:43207632-8028-448D-889D-1C62D213765D
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native, layer [{"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D9B3E1DE-3,AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7B6BF29-41D3-42E8-899C-68B2A3229814 (syncValue: eztYIm85iHfiSkEA91RkLFAQNUc9I4wZ)'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:14 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7,B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7,B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
,2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:16:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A7,B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eztYIm85iHfiSkEA91RkLFAQNUc9I4wZ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eztYIm85iHfiSkEA91RkLFAQNUc9I4wZ', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D9B3E1DE-3AB4-4E08-AD80-781C08B55D07 (syncValue: 6nAMLVigomFoLZrjnhGQIaD,tc41Hu3Bk)'
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D9B3E1DE-3AB4-4E08-AD80-781C0,8B55D07:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}]'
,2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","generation":0}'
,2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:16:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9B3E1DE-3AB4-4E08-AD80-781C08B55D07","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
[ThaliCore] Advertiser: session connected Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D9,B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:16:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6nAMLVigomFoLZrjnhGQIaDtc41Hu3Bk","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:16:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6nAMLVigomFoLZrjnhGQIaDtc41Hu3Bk', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C4D10B98-F43F-4736-BE2A-F1793B701211 (syncValue: pHcicdArFCUJs3K6xjCWiYI,sORHMuXDx)'
2017-07-24 12:16:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793,B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
,[ThaliCore] Session.startOutputStream(with:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 4, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61188
2017-07-24 12:16:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pHcicdArFCUJs3K6xjCWiYIsORHMuXDx",,"error":null,"portNumber":61188}'
2017-07-24 12:16:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pHcicdArFCUJs3K6xjCWiYIsORHMuXDx', error: 'null', listeningPort: '61188''
2017-07-24 12:16:27 - WARN thaliMobileNativeTestUti,ls: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 4, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:28 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:16:28 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:43207632-8028-448D-889D-1C62D213765D
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 281 must be stopped
[ThaliCore] ,B,rowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHan,dler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserManager.disconnect peer:C4D10B98-F43F-4736-BE2A-F1793B701211
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61188
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:,15 [3, 4, 16]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] Session.disconnect() peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [3, 4,]
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
[ThaliCore] AdvertiserRelay.deinit
,# setup
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pHcicdArFCUJs3K6xjCWiYIsORHMuXDx","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,# can still do HTTP requests between peers with coordinator
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'listening 61190'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A3D6730E-18BC-403B-BDA5-19249F3CDCE0
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C4D10B98-F43F-4736-BE2A-F1793B701211 (syncValue: 2cQXqu3xgAyKsOipijdMHOBoZTgNWCGo)'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4,D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}]'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
2017-07-24 12:16:31 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}]'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
2017-07-24 12:16:36 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
2017-07-24 12:16:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:36 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
2017-07-24 12:16:39 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}]'
2017-07-24 12:16:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","generation":0}'
,2017-07-24 12:16:39 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:16:39 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C4D10B98-F43F-4736-BE2A-F1793B701211","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C4,D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C4D10B98,-F43F-4736-BE2A-F1793B701211 error: max retries exceeded
2017-07-24 12:16:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2cQXqu3xgAyKsOipijdMHOBoZTgNWCGo","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2cQXqu3xgAyKsOipijdMHOBoZTgNWCGo', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:16:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F5668ED9-ED3C-4A98-9698-3926B9298543 (syncValue: jawYgb4,sKasDNgAuM1Rz9qrflp4uMXNF)'
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F5668ED9-ED3C,-4A98-9698-3926B9298543:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] Advertiser: session connected Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61203
2017-07-24 12:16:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jawYgb4sKasDNgAuM1Rz9qrflp4uMXNF",,"error":null,"portNumber":61203}'
2017-07-24 12:16:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jawYgb4sKasDNgAuM1Rz9qrflp4uMXNF', error: 'null', listeningPort: '61203''
2017-07-24 12:16:44 - WARN thaliMobileNativeTestUti,ls: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 4, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:44 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:16:44 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
,[ThaliCore] Session.session(_:peer:didChange:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] Session.startOutputStream(with:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [3, 4, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
2017-07-24 12:16:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertis,ingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Session.session(_:peer:didChange:) peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474 state: connected -> notConnected
[ThaliCore] Advertise,r: session notConnected Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] BrowserManager.disconnect peer:F5668ED9-ED3C-4A98-9698-,3926B9298543
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocali,zedDescription=Socket closed by remote peer})
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:18,
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61203
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disco,nnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDis,connect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket.handleEventOnInputStream streams are closed
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [3, 4, 17]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] Session.disconnect() peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:17 [3, 4]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:564F3E34-1A3E-48E6-8FCA-DFB7221CB474
[ThaliCore] Session.deinit peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-24 12:16:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'listening 61206'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
2017-07-24 12:16:49 - INFO th,aliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7146B875-BFA5-464A-88ED-B177AA3D7C16
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7F5CBA13-5171-4B86-A630-E05A6F334A94 (syncValue: lbKcC7YcSWkKu1RpI3nUnJnNPEhJQw4G)'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2E80740-826A-40B4-B83A-A8A5E1CA7D0A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2E80740-826A-40B4-B83A-A8A5E1CA7D0A", generation: 0)
2017-07-24 12:16:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","generation":0}]'
2017-07-24 12:16:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","generation":0}'
,2017-07-24 12:16:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:50 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:50 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
[ThaliCore] Advertiser: session connected Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7F,5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7F5CBA13,-5171-4B86-A630-E05A6F334A94 error: max retries exceeded
2017-07-24 12:17:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lbKcC7YcSWkKu1RpI3nUnJnNPEhJQw4G","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:17:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lbKcC7YcSWkKu1RpI3nUnJnNPEhJQw4G', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:17:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 12:17:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4 (syncValue: K01oEECVvmlaA8SMtGUxWSQjWleO6Uu0)'
,2017-07-24 12:17:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
,[ThaliCore] Session.session(_:peer:didChange:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
,[ThaliCore] Session.startOutputStream(with:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 4, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61221
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K01oEECVvmlaA8SMtGUxWSQjWleO6Uu0",,"error":null,"portNumber":61221}'
2017-07-24 12:17:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'K01oEECVvmlaA8SMtGUxWSQjWleO6Uu0', error: 'null', listeningPort: '61221''
,2017-07-24 12:17:03 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 4, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:03 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:17:03 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7146B875-BFA5-464A-88ED-B177AA3D7C16
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61221
[ThaliCore] VirtualSocket.closeStr,eams() vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLo,calizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHand,ler removed virtual socket vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] Session.disconnect() peer:,B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:20 [3, 4, 19]
[ThaliCore] TCPListener.deinit,
,[ThaliCore] Session.deinit peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [3, 4]
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
[ThaliCore] AdvertiserRelay.deinit
,# setup
,# will fail bad PSK connection between peers
,ok 290 FIX ME, PLEASE!!!
,# teardown
,[ThaliCore] Session.deinit peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:17:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 12:17:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 292 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 12:17:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 293 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 294 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 295 specific error should be returned
,# teardown
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7F5CBA13-5171-4B86-A630-E05A6F334A94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 296 error should be null
,ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 299 specific error should be returned
,# teardown
,ok 300 error should be null
ok 301 error should be null
,# setup
,ok 302 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'listening 61223'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 303 error should be null
ok 304 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 307 error should be null
,ok 308 error should be null
,# setup
,ok 309 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 61224'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F3445788-B26A-4BE6-98A1-ED1F3C3AFA0D
[ThaliCore] Browser.st,artListening
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 310 error should be null
ok 311 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
,ok 313 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 61225'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E736436B-4CF6-4728-9D32-578A77C18152", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E736436B-4CF6-4728-9D32-578A77C18152
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 317 error should be null
,ok 318 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E736436B-4CF6-4728-9D32-578A77C18152", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:E736436B-4CF6-4728-9D32-578A77C18152
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
,ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E736436B-4CF6-4728-9D32-578A77C18152
[ThaliCore] Advertiser.stopAdvertising() peerID:E736436B-4CF6-4728-9D32-578A77C18152
2017-07-24 12:17:06 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
,ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 61228'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 326 error should be null
,ok 327 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 328 error should be null
,ok 329 error should be null
,# setup
,ok 330 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 12:17:07 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 331 This should not cause wifi to fail
ok 332 native router should be bad
,# teardown
,ok 333 error should be null
ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 12:17:08 - DEBUG thaliMobileNativeWrapper: 'listening 61229'
,ok 336 first call should succeed
,ok 337 first call should succeed
,ok 338 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 339 error should be null
,ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 12:17:08 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 342 error should be null
,ok 343 error should be null
,# setup
,ok 344 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 12:17:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 345 error should be null
,ok 346 error should be null
,# setup
,ok 347 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 12:17:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"74da62d4-36fa-4952-b75e-02cad0895a67","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 348 should be called once
ok 349 should not have been called more than once
,# teardown
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"74da62d4-36fa-4952-b75e-02cad0895a67","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 350 error should be null
,ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# can get the network status
,ok 353 network status should have certain non-empty properties
,# teardown
,ok 354 error should be null
,ok 355 error should be null
,# setup
,ok 356 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 357 we have not added peer to the cache yet
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"515e2499-2215-4eb3-9175-a9febaae47bd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 358 peer should be available
,ok 359 cache contains native peer
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"515e2499-2215-4eb3-9175-a9febaae47bd","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 360 peer should be unavailable
,ok 361 peer has been removed from cache
,# teardown
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 365 we have not added peer to the cache yet
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49bd323f-fb1f-4b2a-8857-dac2896a1d23","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 366 peer should be available
ok 367 cache contains wifi peer
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49bd323f-fb1f-4b2a-8857-dac2896a1d23","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 368 peer should be unavailable
,ok 369 peer has been removed from cache
,# teardown
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"004ed77e-66de-42ae-80ef-9cae8490b1cc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 373 first peer is available
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ffb9291f-74da-474b-8f9b-f6173cfa4aeb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 second peer is available
,ok 375 first and second peers are different
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"004ed77e-66de-42ae-80ef-9cae8490b1cc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ffb9291f-74da-474b-8f9b-f6173cfa4aeb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 376 error should be null
ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 379 should not be in cache at start
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"319893bb-e7e5-4cc7-9aa5-0f0fe9b9ab40","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 380 peer is available
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"319893bb-e7e5-4cc7-9aa5-0f0fe9b9ab40","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 12:17:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 384 error should be null
ok 385 error should be null
,# setup
,ok 386 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 12:17:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 387 error should be null
,ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fd7e61db-92b3-4d5f-881f-5bfef3db689f","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 peer should be available
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fd7e61db-92b3-4d5f-881f-5bfef3db689f","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 391 peer should be available
,ok 392 should store correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fd7e61db-92b3-4d5f-881f-5bfef3db689f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 393 error should be null
,ok 394 error should be null
,# setup
,ok 395 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 61230'
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c11c6ec-6652-4f5a-8527-a44504662af4","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4c11c6ec-6652-4f5a-8527-a44504662af4","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 398 discovered correct peer
,ok 399 got correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4c11c6ec-6652-4f5a-8527-a44504662af4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 400 error should be null
,ok 401 error should be null
,# setup
,ok 402 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 61231'
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"af36e7bd-03ef-4b5c-a56f-42c23952a712","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 403 discovered available peer
,ok 404 peer is available
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"af36e7bd-03ef-4b5c-a56f-42c23952a712","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f294b7e-b149-4c48-ae1d-32282c01c631","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 peer should be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f294b7e-b149-4c48-ae1d-32282c01c631","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 409 peer should be unavailable
,ok 410 should be removed from cache
,# teardown
,ok 411 error should be null
,ok 412 error should be null
,# setup
,ok 413 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'listening 61232'
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"00836a81-62ca-4b2d-a027-e9cf399b9185","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 first peer is expected to be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da6f00ff-f565-4555-af4b-791c13a16118","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 415 second peer is expected to be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da6f00ff-f565-4555-af4b-791c13a16118","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"da6f00ff-f565-4555-af4b-791c13a16118","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 we found peer again
,ok 419 it was wifi peer
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"da6f00ff-f565-4555-af4b-791c13a16118","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 peer became unavailable
,ok 421 it was wifi peer
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"00836a81-62ca-4b2d-a027-e9cf399b9185","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 422 error should be null
,ok 423 error should be null
,# setup
,ok 424 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 12:17:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 425 error should be null
,ok 426 error should be null
,# setup
,ok 427 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'listening 61233'
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fdfcb5b6-75f5-4162-b0c5-9010fcdf0889","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 428 first peer is expected to be available
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"402a14da-55a2-4ae2-8b6e-6d9de4317711","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 429 second peer is expected to be available
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"fdfcb5b6-75f5-4162-b0c5-9010fcdf0889","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 430 peer became unavailable
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"402a14da-55a2-4ae2-8b6e-6d9de4317711","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 431 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 432 error should be null
,ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 12:17:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 435 error should be null
,ok 436 error should be null
,# setup
,ok 437 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 12:17:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 438 error should be null
,ok 439 error should be null
,# setup
,ok 440 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"429f817d-5432-42b9-8032-0d1f9009b97e","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 441 peer discovered first time does not have new address
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"429f817d-5432-42b9-8032-0d1f9009b97e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 442 address has not been changed
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"429f817d-5432-42b9-8032-0d1f9009b97e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 443 new port handled correctly
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"429f817d-5432-42b9-8032-0d1f9009b97e","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 444 new host handled correctly
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"429f817d-5432-42b9-8032-0d1f9009b97e","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 445 newAddressPort is null for unavailable peers
,# teardown
,ok 446 error should be null
,ok 447 error should be null
,# setup
,ok 448 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 12:17:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 449 error should be null
ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 452 NOT IMPLEMENTED # SKIP
,# teardown
,ok 453 error should be null
,ok 454 error should be null
,# setup
,ok 455 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-24 12:17:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 459 should be equal
,# teardown
,ok 460 error should be null
,ok 461 error should be null
,# setup
,ok 462 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-24 12:17:15 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
,ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 contains expected properties
,ok 473 the same hostAddress
,ok 474 the same portNumber
,# teardown
,2017-07-24 12:17:15 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 61234'
2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"29d2179e-1bc5-4e22-83de-a846c27573e4","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 478 Got specific error message
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"29d2179e-1bc5-4e22-83de-a846c27573e4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 479 error should be null
,ok 480 error should be null
,# setup
,ok 481 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 61235'
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"db2e2f35-6e80-46f8-bacb-f421b437af62","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:db2e2f35-6e80-46f8-bacb-f421b437af62
,ok 482 native wrapper `disconnect` called once
,ok 483 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"db2e2f35-6e80-46f8-bacb-f421b437af62","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 484 error should be null
,ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 12:17:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 490 error should be null
,ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 493 error should be null
,ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 12:17:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 12:17:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 502 error should be null
ok 503 error should be null
,# setup
,ok 504 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 12:17:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 505 error should be null
ok 506 error should be null
,# setup
,ok 507 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'listening 61236'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:605C37ED-00D4-427B-B50F-D35479A30010
,[ThaliCore] Browser.startListening
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b190ee60-7ed7-4540-a773-30aea95fa01e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 508 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2e927022-e661-415c-baa3-5de55c2993cf","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 509 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b190ee60-7ed7-4540-a773-30aea95fa01e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2e927022-e661-415c-baa3-5de55c2993cf","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}]'
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}'
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 510 No peers
,ok 511 No peers
,ok 512 No peers
,# teardown
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'listening 61237'
2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"564c62c8-d29e-4119-80c3-4d2c3225b8d5","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 516 1
ok 517 2
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9bfe3521-2b92-4630-9b55-166cb0a01d66","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"564c62c8-d29e-4119-80c3-4d2c3225b8d5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9bfe3521-2b92-4630-9b55-166cb0a01d66","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 12:17:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 521 error should be null
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'listening 61238'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 526 error should be null
,ok 527 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
,[ThaliCore] Browser.startListening
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,ok 528 error should be null
ok 529 error should be null
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}]'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:17:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4 (syncValue: 0)'
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Advertiser: session connected Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
2017-07-24 12:17:22 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","generation":0}]'
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","peerAvail,able":true,"generation":0,"portNumber":null}'
2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,2017-07-24 12:17:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}]'
,2017-07-24 12:17:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","generation":0}'
,2017-07-24 12:17:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:17:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] Advertiser: session connected Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F894B066-A1FC-4515-99B1-1CE0256E1FEC (syncValue: 1)'
2017-07-24 12:17:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
,[ThaliCore] Session.session(_:peer:didChange:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] Session.startOutputStream(with:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [3, 4, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61247
,2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":61247}'
,2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 2)'
,2017-07-24 12:17:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 4, 21, 22]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:31 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:17:31 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connecting -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [3, 4, 22]
,[ThaliCore] Session.deinit peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Advertiser: session connected Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61251
,2017-07-24 12:17:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":61251}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [3, 4, 22, 23]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:36 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:17:36 - DEBUG testUtils: 'Got end'
,ok 530 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [3, 4, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F894B066-A1FC-4515-99B1-1CE0256E1FEC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4
2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-24 12:17:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 12:,17:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" ,UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSoc,ket.deinit vsID:24 [3, 4, 22, 23]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
,[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:22 [3, 4, 23]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 error should be null
,ok 532 error should be null
,# setup
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 533 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 12:17:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 534 error should be null
ok 535 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 536 getPeerIdentifier
ok 537 getConnectionType
ok 538 getActionType
ok 539 getActionState
ok 540 getPskIdentity
ok 541 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 542 initial state
,ok 543 after start
,2017-07-24 12:17:57 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 544 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 545 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 12:17:58 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 546 clean kill
,ok 547 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 548 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 549 forever agent should have it's own destroy method
,ok 550 agent's destroy should be called
,ok 551 agent's destroy should not be called again
,ok 552 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 553 Entry counter must be 1
,ok 554 Entry exists
,ok 555 Size must be 1
,ok 556 Entry counter must be 2
,ok 557 Entry exists
,ok 558 Size must be 2
,ok 559 Entry counter must be 1
,ok 560 Entry exists
,ok 561 Size must be 3
,ok 562 Entry counter must be 2
,ok 563 Entry exists
,ok 564 Size must be 4
,ok 565 Entry 1_1 should not be found
,ok 566 Entry 1_1 does not exist
,ok 567 Size must be 3
,ok 568 Entry 1_2 should not be found
,ok 569 Entry 1_2 does not exist
,ok 570 Size must be 2
,ok 571 should be equal
,ok 572 Entry 2_1 should not be found
,ok 573 Entry 2_2 should not be found
,ok 574 Entry 2_1 does not exist
,ok 575 Entry 2_2 does not exist
,ok 576 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 577 Size must be100
,ok 578 Entries between 20 and MAXSIZE + 20 should exist
,ok 579 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 580 Entries between 6 and MAXSIZE + 4 should exist
,ok 581 Size should be MAXSIZE
,ok 582 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 583 WAITING state entry should not be removed
,ok 584 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 585 Size should be MAXSIZE
,ok 586 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 587 Kill should be called once
,ok 588 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 589 is an agent
,ok 590 enqueue is fine
,ok 591 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 592 is an agent
ok 593 first enqueue is fine
ok 594 is an agent
ok 595 second enqueue is fine
ok 596 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 597 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 598 is an agent
,ok 599 good enqueue
,ok 600 Identity should match
,2017-07-24 12:18:03 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:18:03 - DEBUG testUtils: 'Got end'
,ok 601 Got expected response
,ok 602 Got psk call back
,# teardown
,2017-07-24 12:18:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 603 is an agent
,ok 604 enqueue worked
,ok 605 is an agent
,ok 606 enqueue 2 worked
,ok 607 enqueue is not available when stopped
,ok 608 start action is killed
,ok 609 killed action is still killed
,ok 610 enqueued action when stopped is killed
,ok 611 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 612 good start
,ok 613 good enqueue
,ok 614 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 615 null arg
ok 616 wrong arg type
ok 617 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 618 good enqueue
,ok 619 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 620 good enqueue
ok 621 2nd good enqueue
ok 622 we are in the pool
,ok 623 We are out of the pool
ok 624 Action was killed
ok 625 The original kill was called too
ok 626 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 627 good enqueue
ok 628 first kill
ok 629 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 630 1st good enqueue
ok 631 2nd good enqueue
ok 632 1st action is in the pool
ok 633 2nd action is in the pool
ok 634 1st action is out of the pool
ok 635 2st action is out of the pool
ok 636 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 12:18:05 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got right error
,ok 638 Start should not be called
,ok 639 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 12:18:06 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 640 Got right error
,ok 641 Start should not be called
,ok 642 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 643 Got null
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 644 is an agent
2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 645 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 646 Got Null
,ok 647 Got another null
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 648 is an agent
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 649 is an agent
,2017-07-24 12:18:06 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 650 Action 1 killed at least once
,ok 651 Action 1 went first
,ok 652 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 653 should have gotten null
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 654 Should have stopped nicely
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 655 Still looking for null
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 656 Yup, another null
,ok 657 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 658 Null 1
,ok 659 (unnamed assert)
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 660 is an agent
,ok 661 Null 3
,ok 662 Replication not yet called
,ok 663 Notification 2 not yet called
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 664 is an agent
,ok 665 Notification went first
,ok 666 Notification 2 not called yet
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 667 is an agent
,ok 668 Notification finished
,ok 669 Replication finished
,2017-07-24 12:18:07 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 670 is an agent
ok 671 First does, not throw
2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 672 is an agent
ok 673 Second does not throw
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
,2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 first ok
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 676 is an agent
,ok 677 second ok
,ok 678 third ok
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 12:18:09 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'listening 61256'
,ok 679 error should be null
,ok 680 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:836E24B5-833B-49F1-B94E-975EDDFDC93D
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,[ThaliCore] Browser.startListening
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:18:09 - INFO testThaliNotification: 'startListeningForAdvertisements'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
2017-07-24 12:18:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 3)'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) found active relay
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":61251}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","generation":0}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [3, 4, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [3, 4]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9217F548-C7E8-4106-A99F-8C3D222B81B7 (syncValue: 4)'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:18:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
[ThaliCore] Advertiser: session connected Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE state: notConnected -> connecting
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F,513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [3, 4, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:26
,[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [3, 4]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Advertiser: session connected Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport,:61261
,2017-07-24 12:18:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":61261}'
,2017-07-24 12:18:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6EE1358B-49C1-44F9-AE2B-8B17E5A90B39 (syncValue: 5)'
,2017-07-24 12:18:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [3, 4, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:18:14 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 61261,9217F548-C7E8-4106-A99F-8C3D222B81B7'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [3, 4]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9217F548-C7E8,-4106-A99F-8C3D222B81B7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [3, 4, 28]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
,[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [3, 4]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] Session.startOutputStream(with:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [3, 4, 29]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] Session.startOutputStream(with:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [3, 4, 29, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandl,er disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [3, 4, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0 state: notConnected -> connecting
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:30
[ThaliCore] VirtualSocket.closeS,treams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] Session.startOutputStream(with:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [3, 4, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Session.startOutputStream(with:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,2 [3, 4, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [3, 4, 30, 32]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:), client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [3, 4, 30]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61270
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":61270}'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 6)'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) found active relay
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":61251}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [3, 4, 30, 33]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [3, 4, 30, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [3, 4, 30, 33]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [3, 4, 30, 33, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [3, 4, 30, 33]
,2017-07-24 12:18:17 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 61270,6EE1358B-49C1-44F9-AE2B-8B17E5A90B39'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [3, 4, 30]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [3, 4, 30, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[Th,aliCore] VirtualSocket.deinit vsID:36 [3, 4, 30]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 7)'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,7 [3, 4, 30, 37]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [3, 4, 30]
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) found active relay
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":61251}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [3, 4, 30, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:,38 [3, 4, 30]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61251
[ThaliCore] Session.disconnect() peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:18:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:18:17 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Session.startOutputStream(with:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,9 [3, 4, 30, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDes,cription=Operation not permitted, NSLocalizedFailureReason=Error in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:39
[Th,aliCore] VirtualSocket.closeStreams() vsID:39
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [3, 4, 30]
,[ThaliCore] Session.session(_:peer:didChange:) peer:F513D266-4360-4A67-8F33-8053B564FDAC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F513D266-4360-4A67-8F33-8053B564FDAC
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:F513D266-4360-4A67-8F33-8053B564FDAC
,ok 681 Peer made successful https requests to all peers
ok 682 Peer received right amount of https requests
ok 683 HTTPS server received zero PSK Identities. Count:0
# teardown
,2017-07-24 12:18:20 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
2017-07-24 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C,3D222B81B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6EE1358B-49C1-44F9-AE2B-8B17E5A90B39,","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:836E24B5-833B-49F1-B94E-975EDDFDC93D
2017-07-24 12:18:20 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:18:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({",s,tarted":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdve,rtisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:18:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [3, 4]
,# setup
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 684 peerIdentifier should match
,ok 685 generation should match
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 good beacon
,ok 688 good preAmble
,ok 689 public keys match!
,ok 690 must return null after successful call
,ok 691 Once start returns the action should be in KILLED state
,# teardown
,2017-07-24 12:18:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 692 Response should be HTTP_BAD_RESPONSE
,ok 693 must return null after successful call
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 694 Response should be NETWORK_PROBLEM
,ok 695 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 696 Resolution should be BAD_PEER
,ok 697 correct error message
,# teardown
,2017-07-24 12:18:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 698 Call start once
,ok 699 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 700 must return null after successful call.
,# teardown
,2017-07-24 12:18:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 701 Should be Killed
ok 702 Start after killed
,# teardown
,2017-07-24 12:18:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 703 Should be KILLED
,ok 704 must return null after successful kill
,# teardown
,2017-07-24 12:18:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 705 Should be KILLED
ok 706 must return null after successful kill
,# teardown
,2017-07-24 12:18:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 707 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 708 must return null after successful call
,# teardown
,2017-07-24 12:18:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 12:18:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 709 Should be NETWORK_PROBLEM caused closing server socket
,ok 710 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 711 Should be NETWORK_PROBLEM caused closing client socket
ok 712 Should be Could not establish TCP connection
,# teardown
,2017-07-24 12:18:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 713 publicKeysToNotify cannot be null
,ok 714 ecdh for local device cannot be null
,ok 715 milliseconds cannot be less than 0
,ok 716 milliseconds cannot be 0
,ok 717 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 718 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 719 should be equal
ok 720 should be equal
,ok 721 (unnamed assert)
,ok 722 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 723 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 724 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 725 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 726 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 727 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 728 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 729 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,ok 730 should be equal
,ok 731 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 732 should be equal
,ok 733 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 734 right number of calls to address book
,ok 735 good preAmble
,ok 736 good unencryptedKeyId
,ok 737 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 738 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 739 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 740 Matching numbers
,ok 741 We have an entry!
,ok 742 keys match
,ok 743 secrets match
,ok 744 We have an entry!
,ok 745 keys match
,ok 746 secrets match
,ok 747 We have an entry!
,ok 748 keys match
,ok 749 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 750 Streams have same length
,ok 751 matching size
,ok 752 keys match
,ok 753 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 754 should be equal
,ok 755 peerDictionalty contains 2 peers
,ok 756 bluetooth peer's notification has correct connection type
,ok 757 tcp peer's notification has correct connection type
,2017-07-24 12:18:43 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-24 12:18:43 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 12:18:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 758 notification peer dictionary contains exactly 1 peer
,2017-07-24 12:18:44 - WARN thaliNotificationClient: 'peer is not available'
,ok 759 notification peer dictionary does not contain any peers
,2017-07-24 12:18:44 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 12:18:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 760 entry exists
,ok 761 entry is resolved
,# teardown
,2017-07-24 12:18:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 762 Action should be KILLED
,ok 763 Peer state should be RESOLVED
,# teardown
,2017-07-24 12:18:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 764 hostAddress must match
,ok 765 portNumber must match
,ok 766 suggestedTCPTimeout must match
,ok 767 connectionType must match
,ok 768 peerIDs must match
,# teardown
,2017-07-24 12:18:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 769 Correct error
,# teardown
,2017-07-24 12:18:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 770 hostAddress must match
,ok 771 portNumber must match
,ok 772 suggestedTCPTimeout must match
,ok 773 connectionType must match
,ok 774 peerIds must match
,# teardown
,2017-07-24 12:18:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 775 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 776 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 777 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:50 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 778 action should be resolved with NETWORK_PROBLEM error
ok 779 correct number of requests
ok 780 correct number of failures
ok 781 correct final peer state
,# teardown
,2017-07-24 12:18:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 12:18:53 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-24 12:18:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 782 peerDictionary should become empty
,# teardown
,2017-07-24 12:18:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 12:18:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 783 failed with expected error
ok 784 peer state should be RESOLVED
,# teardown
,2017-07-24 12:18:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 12:18:54 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 785 First action failed
,ok 786 second action killed
# teardown
,2017-07-24 12:18:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 787 secrets are equal
,ok 788 Public key matches with the server key
,ok 789 hostAddress must match
,ok 790 portNumber must match
,ok 791 suggestedTCPTimeout must match
,ok 792 connectionType must match
,# teardown
,2017-07-24 12:18:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 793 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 794 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 795 All entries should be expired after 1 second
# teardown
,2017-07-24 12:18:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 796 All keys need to be available in the cache
,ok 797 All entries should be expired after 1 second
# teardown
,2017-07-24 12:18:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 798 Size of the cache should be 2
ok 799 Cache doesn't contain dictionary1
,ok 800 Size of the cache should be 1
,ok 801 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
,2017-07-24 12:19:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 802 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 803 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 12:19:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 804 StartUpdateAdvertisingAndListening should not be called
,ok 805 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 806 no error
,ok 807 should be 204
,# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 808 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 809 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 12:19:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 810 no error
ok 811 should be 200
,ok 812 should be equal
,ok 813 should be equal
,ok 814 (unnamed assert)
,ok 815 no error
ok 816 should be 204
,# teardown
,2017-07-24 12:19:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 817 error should be null
,ok 818 should be 204
,# teardown
,2017-07-24 12:19:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 819 should be 404
,# teardown
,2017-07-24 12:19:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 820 equal keys
,ok 821 not equal connection type
,ok 822 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 12:19:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 823 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 824 second cleared dictionary
,2017-07-24 12:19:07 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 825 First start and on called correctly
,ok 826 First stop and removeListener called correctly
,ok 827 first action kill called
,ok 828 second action kill called
,ok 829 first cleared dictionary
,ok 830 first cleared pool
,ok 831 second cleared dictionary
,ok 832 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 833 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-24 12:19:08 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 834 listener has been set
,ok 835 peer dictionary has expected number of entries
,ok 836 Dictionary and pool have same action
,ok 837 ads match
,ok 838 PouchDB matches
,ok 839 DB Names match
,ok 840 public keys match
,ok 841 peer dictionary has expected number of entries
,ok 842 Dictionary and pool have same action
,ok 843 ads match
,ok 844 PouchDB matches
,ok 845 DB Names match
,ok 846 public keys match
,2017-07-24 12:19:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 847 start called once
,ok 848 One entry left
,ok 849 Dictionary and pool have same action
,ok 850 Start never called
,ok 851 Kill called once
,ok 852 no entries left
,ok 853 Third action is dead
,ok 854 peer dictionary has expected number of entries
,ok 855 Dictionary and pool have same action
,ok 856 ads match
,ok 857 PouchDB matches
,ok 858 DB Names match
,ok 859 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-24 12:19:10 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'listening 61328'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Browser.startListening
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9586F70-5B36-4872-8956-BF5C544C75F6
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
2017-07-24 12:19:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","generation":0}]'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:), found peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - E,mitting {"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:19:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:19:11 - ,DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 560FF751-846E-4A58-8A52-A4E2B97186CC (syncValue: 8)'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "56,0FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","generation":0}]'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","generation":0}'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:19:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B358F577-9A2C-4F71-9BC2-6A69E0B99696","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Advertiser: session connected Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Advertiser: session connected Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:19:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61332
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":61332}'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for B358F577-9A2C-4F71-9BC2-6A69E0B99696 (syncValue: 9)'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [3, 4, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [3, 4]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [3, 4, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:14 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [3, 4, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [3, 4, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [3, 4, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [3, 4, 41, 42, 43, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [3, 4, 41, 42, 43, 45]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [3, 4, 41, 42, 43, 45, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] VirtualSocket.deinit vsID:46 [3, 4, 41, 42, 43, 45]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [3, 4, 41, 42, 43, 45, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [3, 4, 41, 42, 43, 47]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [3, 4, 41, 42, 43, 47, 48]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:47 [3, 4, 41, 42, 43, 48]
,2017-07-24 12:19:16 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [3, 4, 41, 42, 43, 48, 49]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [3, 4, 41, 42, 43, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:wit,hError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [3, 4, 41, 42, 43, 48, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] Session.session(_:peer:didChange:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [3, 4, 41, 42, 43, 48, 50, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
,[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [3, 4, 41, 42, 43, 48, 50]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,2 [3, 4, 41, 42, 43, 48, 50, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [3, 4, 41, 42, 43, 48, 50, 52, 53]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61349
,2017-07-24 12:19:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":61349}'
,2017-07-24 12:19:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 10)'
,2017-07-24 12:19:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [3, 4, 41, 42, 43, 48, 50, 52, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [3, 4, 41, 42, 43, 48, 50, 52, 53]
,2017-07-24 12:19:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[Th,aliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 57]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,9 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 57, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 57, 58, 59, 60]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 57, 58, 59, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
,[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 60, 61]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] VirtualSocket.deinit vsID:60 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,3 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 63]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 63, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
[ThaliCore] Session.startOutputStream(with:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 63, 64, 65]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Th,aliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [3, 4, 41, 42, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 12:19:18 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:42 [3, 4, 41, 43, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65, 66]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [3, 4, 41, 48, 50, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65, 66]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:48 [3, 4, 41, 50, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65, 66]
,2017-07-24 12:19:19 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,61DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[Thali,Core] VirtualSocket exited RunLoop vsID:50
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:50 [3, 4, 41, 52, 53, 55, 56, 58, 59, 61, 62, 64, 65, 66]
[ThaliCore] TCPClient.socketDi,dDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [3, 4, 41, 52, 55, 56, 58, 59, 61, 62, 64, 65, 66]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [3, 4, 41, 52, 55, 56, 58, 61, 62, 64, 65, 66]
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [3, 4, 41, 52, 55, 58, 61, 62, 64, 65, 66]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 12:19:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 12:19:20 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:55 [3, 4, 41, 52, 58, 61, 62, 64, 65, 66]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [3, 4, 41, 52, 58, 62, 64, 65, 66]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [3, 4, 41, 52, 58, 62, 65, 66]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:66 [3, 4, 41, 52, 58, 62, 65]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [3, 4, 41, 58, 62, 65]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [3, 4, 41, 62, 65]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withErr,or:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:65
,[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [3, 4, 41, 65]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
[ThaliCore] VirtualSocket.deinit vsID:65 [3, 4, 41]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,61DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
2017-07-24 12:19:25 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 stat,e: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] Browser: session notConnected retry count #2 ,for Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
[ThaliCore] Browser,.,inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,2017-07-24 12:19:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:19:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:19:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:19:25 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 12:19:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 12:19:25 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:22:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 12:22:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 12:29:09 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 12:29:09 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-24 12:,29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-24 12:29:09 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request coordinated'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated pull replication from notification test, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F,-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-24 12:29:09 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 12:29:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 860 failed with TimeoutError
,  ---
,    operator: fail
,  ...
,# teardown
,2017-07-24 12:29:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-4,39F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439,F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/63EC84C1-E3BC-439F-9F04-287EDAA05526/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
