#### Test 1374640318f8a044_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/9A54B412-9675-49E7-BD68-526C21017124/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9A54B412-9675-49E7-BD68-526C21017124/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59997"
,(lldb)     command script import "/tmp/9A54B412-9675-49E7-BD68-526C21017124/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:47:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F5AE6649-1F45-4859-B633-59DC1A918241", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F5AE6649-1F45-4859-B633-59DC1A918241
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2309C386-3CEA-45F2-818C-0896E4A055B1
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE33CB99-8B5A-4302-8603-3B29866E9444
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "385A7820-783C-4229-8625-7D8D8B9E2E88", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:385A7820-783C-4229-8625-7D8D8B9E2E88
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:385A7820-783C-4229-8625-7D8D8B9E2E88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "385A7820-783C-4229-8625-7D8D8B9E2E88", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-08-24 14:47:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.604836106300354
,2017-08-24 14:47:56 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-08-24 14:47:56 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:385A7820-783C-4229-8625-7D8D8B9E2E88:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "385A7820-783C-4229-8625-7D8D8B9E2E88", generation: 0)
,2017-08-24 14:47:59 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-24 14:48:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-24 14:48:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,2017-08-24 14:48:03 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-24 14:48:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:40 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-08-24 14:48:40 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-24 14:48:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-08-24 14:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-24 14:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-08-24 14:48:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-08-24 14:48:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-08-24 14:48:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-08-24 14:48:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-08-24 14:48:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 10 should be equal
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
,# teardown
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
,2017-08-24 14:48:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-08-24 14:48:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-08-24 14:48:58 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-08-24 14:49:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-24 14:49:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6E9945D8-B7C6-4B56-88DD-F9FD22CC08F5
[ThaliCore] Browser.startListening
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-24 14:49:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:453EF61A-6EB8-4199-B009-A79192AD0A30
[ThaliCore] Browser.startListening
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-24 14:49:03 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with tar,get ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stop,ped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:04 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "700835D9-A7A3-4D5F-A122-46A5EFF91AC8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:700835D9-A7A3-4D5F-A122-46A5EFF91AC8
2017-08-24 1,4:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:700835D9-A7A3-4D5F-A122-46A5EFF91AC8
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E9FD965-EC7F-4855-B0B3-4966A47CFE48", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7E9FD965-EC7F-4855-B0B3-4966A47CFE48
2017-08-24 1,4:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7E9FD965-EC7F-4855-B0B3-4966A47CFE48", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:7E9FD965-EC7F-4855-B0B3-4966A47CFE48
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7E9FD965-EC7F-4855-B0B3-4966A47CFE48
[ThaliCore] Advertiser.stopAdvertising() peerID:7E9FD965-EC7F-4855-B0B3-4966A47CFE48
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive",:false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A0607900-813D-4C11-B1D3-06B66F9F9C6D
2017-08-24 1,4:49:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:461D1799-FA43-4BA6-BB5B-E98263A13192
[ThaliCore] Browser.startListening
,2017-08-24 14:49:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A0607900-813D-4C11-B1D3-06B66F9F9C6D
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E3D14BF0-885E-42DE-AEF8-51DA6C19C621
2017-08-24 1,4:49:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A
[ThaliCore] Browser.startListening
2017-08-24 14:49:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-08-24 14:49:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FFA4D95-6464-4803-8737-E537C6B4DECB","generation":0}'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1FFA4D95-6464-4803-8737-E537C6B4DECB (syncValue: JfbHgV62L4oKWIQT41TVqHYa3Pnwnona)'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78","generation":0}'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55074
,2017-08-24 14:49:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JfbHgV62L4oKWIQT41TVqHYa3Pnwnona","error":null,"portNumber":55074}'
,2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JfbHgV62L4oKWIQT41TVqHYa3Pnwnona', error: 'null', listeningPort: '55074''
,2017-08-24 14:49:15 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-08-24 14:49:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:E3D14BF0-885E-42DE-AEF8-51DA6C19C621
2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14,:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1FFA4D95-6464-4803-8737-E537C6B4DECB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55074
[ThaliCore] Session.disconnect() p,eer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A
2017-08-24 1,4:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
[Thal,iCore] Browser.startListening
,2017-08-24 14:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-24 14:49:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FFA4D95-6464-4803-8737-E537C6B4DECB","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1FFA4D95-6464-4803-8737-E537C6B4DECB (syncValue: 2rNSrS6jVDc9yRxg0q9AXzklOOr5Hfgr)'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-,24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3374CEC-5CAF-4EC9-8F24-18B03362EC6D","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
2017-08-24 14:49:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3C2297-B546-4712-88B9-DA70154DC511","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,FA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,FA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1F,FA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1FFA4D95,-6464-4803-8737-E537C6B4DECB error: max retries exceeded
2017-08-24 14:49:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2rNSrS6jVDc9yRxg0q9AXzklOOr5Hfgr","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2rNSrS6jVDc9yRxg0q9AXzklOOr5Hfgr', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78 (syncValue: cAqpoulT8UNDtqL0keCLfbsAipJf1oTp)'
,2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2B2E31C8,-0CC3-4F27-8F27-FCADDBFCDA78 error: max retries exceeded
2017-08-24 14:49:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cAqpoulT8UNDtqL0keCLfbsAipJf1oTp","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cAqpoulT8UNDtqL0keCLfbsAipJf1oTp', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3374CEC-5CAF-4EC9-8F24-18B03362EC6D (syncValue: jKE94GAqm4o4Kb4TsFAemlJboJWjGnJJ)'
,2017-08-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
[ThaliCore] Advertiser: session connected Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8 state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55081
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jKE94GAqm4o4Kb4TsFAemlJboJWjGnJJ","error":null,"portNumber":55081}'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jKE94GAqm4o4Kb4TsFAemlJboJWjGnJJ', error: 'null', listeningPort: '55081''
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
[ThaliCore] Session.startOutputStream(with:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,Connecting to the localhost:55081
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,Connected to the localhost:55081
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
[ThaliCore] Session.startOutputStream(with:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
# teardown
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-24 14:49:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:49:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A4C1EAA2-78F8-4D2B-A7A8-6,D73185C810A
2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
[ThaliCore] BrowserManager.disconnect peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55081
[ThaliCore] Sessi,on.disconnect() peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:49113C2E-45AB-4903-A759-BC5216FA0D18
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:40409F35-D016-4907-82F5-3223812E2E18
,[ThaliCore] Browser.startListening
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
[ThaliCore] Session.deinit peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
2017-08-24 14:49:46 - INFO thaliMobile: ,'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
2017-08-24 14:49:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3374CEC-5CAF-4EC9-8F24-18B03362EC6D","generation":0}'
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3374CEC-5CAF-4EC9-8F24-18B03362EC6D, (syncValue: DnqgvFOy2LpQRJI7jllhJlKvodw4RtsF)'
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B0336,2EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
2017-08-24 14:49:46, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3C2297-B546-4712-88B9-DA70154DC511","generation":0}'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
2017-08-24 14:49:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A2F523B-551F-43F6-8F63-E9BA6B74AA01","generation":0}'
2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:47 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
2017-08-24 14:49:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD12190F-C11B-4D3D-90CA-E076C0040F6F","generation":0}'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:48 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B3374CEC,-5CAF-4EC9-8F24-18B03362EC6D error: max retries exceeded
2017-08-24 14:49:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DnqgvFOy2LpQRJI7jllhJlKvodw4RtsF","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DnqgvFOy2LpQRJI7jllhJlKvodw4RtsF', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF3C2297-B546-4712-88B9-DA70154DC511 (syncValue: 1WK13U5,ydWZuOq0TAjpKbvFsSiQha6cY)'
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF3C2297-B546,-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:CF3C2297,-B546-4712-88B9-DA70154DC511 error: max retries exceeded
2017-08-24 14:50:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1WK13U5ydWZuOq0TAjpKbvFsSiQha6cY","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1WK13U5ydWZuOq0TAjpKbvFsSiQha6cY', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A2F523B-551F-43F6-8F63-E9BA6B74AA01 (syncValue: P8HuUwQ,XGPZ4ZhqDJGN57gKUQg5U3VLQ)'
2017-08-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A2F523B-551F,-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55099
2017-08-24 14:50:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P8HuUwQXGPZ4ZhqDJGN57gKUQg5U3VLQ",,"error":null,"portNumber":55099}'
2017-08-24 14:50:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'P8HuUwQXGPZ4ZhqDJGN57gKUQg5U3VLQ', error: 'null', listeningPort: '55099''
,Connecting to the localhost:55099
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,Connecting to the localhost:55099
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,Connecting to the localhost:55099
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,Connected to the localhost:55099
,Connected to the localhost:55099
,Connected to the localhost:55099
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [1, 4, 5]
,ok 95 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 5]
,ok 96 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [1]
,# teardown
,2017-08-24 14:50:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:49113C2E-45AB-4903-A759-BC5216FA0D18
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14,:,50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55099
[ThaliCore] Session.disconnect() p,eer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A
,2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E
[ThaliCore] Browser.startListening
2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
,2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
2017-08-24 14:50:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3374CEC-5CAF-4EC9-8F24-18B03362EC6D","generation":0}'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3374CEC-5CAF-4EC9-8F24-18B03362EC6D, (syncValue: fsNgsOemue5Dgm6YJ2N2hUxTknltOfd3)'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B0336,2EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"CF3C2297-B546-4712-88B9-DA70154DC511","generation":0}'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88F25900-E82C-4806-BEBE-C7A0F07CDFEA","generation":0}'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
2017-08-24 14:50:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81E2C700-B307-4017-AC4A-E1CFD3A79A7E","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:50:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fsNgsOemue5Dgm6YJ2N2hUxTknltOfd3","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:50:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fsNgsOemue5Dgm6YJ2N2hUxTknltOfd3', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:50:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:50:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF3C2297-B546-4712-88B9-DA70154DC511 (syncValue: QoGyE0CzF5t10rVQMJWp429,zvKAzrWCJ)'
2017-08-24 14:50:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA701,54DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF3C2297-B546-4712-88B9-DA70154DC511:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:CF,3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,F3C2297-B546-4712-88B9-DA70154DC511", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:50:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QoGyE0CzF5t10rVQMJWp429zvKAzrWCJ","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:50:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QoGyE0CzF5t10rVQMJWp429zvKAzrWCJ', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:50:25 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:50:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88F25900-E82C-4806-BEBE-C7A0F07CDFEA (syncValue: MzouS9eoi7qh8aPiQyC4aC9,qS8gWEkKl)'
2017-08-24 14:50:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F,07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55110
2017-08-24 14:50:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MzouS9eoi7qh8aPiQyC4aC9qS8gWEkKl",,"error":null,"portNumber":55110}'
2017-08-24 14:50:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MzouS9eoi7qh8aPiQyC4aC9qS8gWEkKl', error: 'null', listeningPort: '55110''
,Connecting to the localhost:55110
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:55110
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
# teardown
,2017-08-24 14:50:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A
2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14,:,50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55110
[ThaliCore] Session.disconnect() p,eer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4D857E22-1043-4D59-866C-EE82BF5CE43B
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC216,3E90F
,[ThaliCore] Browser.startListening
2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
2017-08-24 14:50:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88F25900-E82C-4806-BEBE-C7A0F07CDFEA","generation":0}'
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88F25900-E82C-4806-BEBE-C7A0F07CDFEA (syncValue: Mum0tHvWOvSQbZw4cxBWAJaIu0js8wns)'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81E2C700-B307-4017-AC4A-E1CFD3A79A7E","generation":0}'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
2017-08-24 14:50:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}'
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:40 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,8F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,8F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:50:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Mum0tHvWOvSQbZw4cxBWAJaIu0js8wns","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:50:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Mum0tHvWOvSQbZw4cxBWAJaIu0js8wns', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:50:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-08-24 14:50:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81E2C700-B307-4017-AC4A-E1CFD3A79A7E (syncValue: cy4avUgPIQhVES804V0oBGizitIljc0t)'
,2017-08-24 14:50:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,1E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:81,E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:81E2C700,-B307-4017-AC4A-E1CFD3A79A7E error: max retries exceeded
2017-08-24 14:50:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cy4avUgPIQhVES804V0oBGizitIljc0t","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:50:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cy4avUgPIQhVES804V0oBGizitIljc0t', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:50:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3 (syncValue: cJf0gi4,p3gqUC0oYnIQv42w4PpzVTlCF)'
2017-08-24 14:50:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD334B3A-D5C0,-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55130
2017-08-24 14:50:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cJf0gi4p3gqUC0oYnIQv42w4PpzVTlCF",,"error":null,"portNumber":55130}'
2017-08-24 14:50:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cJf0gi4p3gqUC0oYnIQv42w4PpzVTlCF', error: 'null', listeningPort: '55130''
Connecting to the localhost:55130
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
Connected to the localhost:55130
2017-08-24 14:50:59 - DEBUG testThaliMob,ileNative: 'Client sends data (65536 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [1, 6]
,ok 102 got the same data back
,# teardown
,2017-08-24 14:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4D857E22-1043-4D59-866C-E,E82BF5CE43B
2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55130
[ThaliCore] Session.disconnect() p,eer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "786A2D40-BCD2-425E-B257-8DE7A40953F7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:786A2D40-BCD2-425E-B257-8DE7A40953F7
2017-08-24 1,4:51:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 103 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8937A94D-2DA1-4C97-9B29-9260AD28CEA9
[ThaliCore] Browser.startListening
2017-08,-24 14:51:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:51:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
ok 104 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:786A2D40-BCD2-425E-B257-8DE7A40953F7
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore,] BrowserManager.foundPeerHandler peer:Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
2017-08-24 14:51:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7-08-24 14:51:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret",:null,"networkType":null}})'
2017-08-24 14:51:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-08-24 14:51:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0777FB8B-2B41-4DD8-8F0E-07DD94707D4A
,[ThaliCore] Browser.startListening
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31839FA3-E4F9-41C8-983D-6C5ED5AE9094", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:31839FA3-E4F9-41C8-983D-6C5ED5AE9094
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:31839FA3-E4F9-41C8-983D-6C5ED5AE9094
,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
,ok 115 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-08-24 14:51:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-24 14:51:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 126 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 128 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:c1ca27cc-a5aa-4a5e-a85f-fc4f93bf1b91 error: startListeningNotActive
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cwGw8sKXwStyInZIbaZliHOB4MvT9Va4","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 129 Should only get called after multiConnect returned
,ok 130 SyncValue matches
,ok 131 Got right error
,ok 132 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4926DAA5-10C8-4407-A4B3-3DF469007DE5
[ThaliCore] Browser.startListening
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 No error on starting
ok 134 Got null as expected
2017-08-24 14:51:19 - DEB,UG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Hl8Gxxu16tvB1EManUhx63bOFikLKSSn","error":"Illegal peerID","portNumber":null}'
,ok 135 Should only get called after multiConnect returned
,ok 136 SyncValue matches
,ok 137 Got right error
,ok 138 listeningPort is null
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}]'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-08-24 14:51:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ACD58EBB-7E05-4BC8-AC3B-65B840B31621
,[ThaliCore] Browser.startListening
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 139 No error on starting
,ok 140 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 141 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:ac86a487-4425-4da3-b3a9-11659647071d
,ok 142 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:88D2FFB7-883E-4729-94D5-CE3958DDC824
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 143 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D
[ThaliCore] Browser.startListening
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
2017-08-24 14:51:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DED5FE0-F5D2-4C10-B30B-CB988DB7345D, (syncValue: 347nXUIiyJoBd6tD3aFY8bIq3cABPEJV)'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB,7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E9508C9A-F8A7-485A-9C73-CD057AF54A08","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88D,2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3B568BCD-8A56-4957-ABDA-851A732D225F","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-,24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,ED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,ED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,ED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"347nXUIiyJoBd6tD3aFY8bIq3cABPEJV","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:51:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '347nXUIiyJoBd6tD3aFY8bIq3cABPEJV', error: 'Peer is unavailable', listeningPort: '%s''
2017-08-24 14:51:30 - ERROR thaliMobileNativeTestUti,ls: 'Fatal connect error: 'Peer is unavailable''
,2017-08-24 14:51:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E9508C9A-F8A7-485A-9C73-CD057AF54A08 (syncValue: At2lSexlYrmZMQoR5NwMLpB4jevsdzcm)'
2017-08-24 14:51:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E950,8C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55144
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"At2lSexlYrmZMQoR5NwMLpB4jevsdzcm",,"error":null,"portNumber":55144}'
2017-08-24 14:51:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'At2lSexlYrmZMQoR5NwMLpB4jevsdzcm', error: 'null', listeningPort: '55144''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,ok 145 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) found active relay
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UUdZvRztrVe7FFwgxlBFjncNLxuFTDly","error":null,"portNumber":55144}'
,ok 146 No error
,ok 147 Ports equal
,ok 148 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) found active relay
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zFXNMp8lf1tzS1pankwyrn9Zs90lb33E","error":null,"portNumber":55144}'
,ok 149 No error
,ok 150 Ports equal
,# teardown
,2017-08-24 14:51:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:88D2FFB7-883E-4729-94D5-CE3958DDC824
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55144
,[ThaliCore] Session.disconnect() peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] TCPListener.deinit
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"At2lSexlYrmZMQoR5NwMLpB4jevsdzcm","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,# initial peer discovery
,2017-08-24 14:51:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-24 14:51:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-24 14:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-24 14:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-24 14:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-08-24 14:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'listening 55147'
,ok 151 Should throw
,# teardown
,2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55149'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 152 initial connection state should be CONNECTED
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 153 final connection state should be DISCONNECTED
,# teardown
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55152'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 154 tried to connect to right port
,ok 155 failed due to refused connection
,ok 156 routerPortConnectionFailed is emitted
,# teardown
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55156'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 157 Send/recvd #1 should be equal length
,ok 158 Send/recvd #1 should be same
,ok 159 Send/recvd #2 should be equal length
,ok 160 Send/recvd #2 should be same
,ok 161 Should be exactly 2 client sockets
,# teardown
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli,ent connection <-> Mux - 0 - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'listening 55161'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 162 socket shouldn't close until after stream
,ok 163 incoming remains open
,# teardown
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'listening 55165'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 164 we should not have gotten an error
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 165 socket shouldn't close until after incoming
,ok 166 incoming is cleaned up
,# teardown
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'listening 55169'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 167 stream was closed
,ok 168 incoming should survive
,ok 169 mux should have no streams
,# teardown
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 55173'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 170 we should not have gotten an error
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 171 Buffers are identical
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 172 native server is nulled out
,ok 173 native server should be closed
,ok 174 incoming has been removed
,ok 175 Incoming should be done
,ok 176 The mux object should be closed
,ok 177 The mux stream should be closed
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 55177'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 178 native server is nulled out
,ok 179 native server should be closed
,ok 180 incoming has been removed
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'listening 55229'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 181 we should not have gotten an error
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 182 Buffers are identical
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 183 server should be fine
,ok 184 server should be open
,ok 185 incoming has been removed
,ok 186 The mux object should be closed
,ok 187 The mux stream should be closed
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'listening 55233'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 188 we should not have gotten an error
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 189 Buffers are identical
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 190 server should be fine
,ok 191 server should be open
,ok 192 incoming has been removed
,ok 193 The mux object should be closed
,ok 194 The mux stream should be closed
,# teardown
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55236'
ok 198 port must be in range
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55237'
,ok 199 second start should return same port
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55239'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 200 we should be connected
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 201 now we are disconnected
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 202 Passed bogus id
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 203 Passed good id but bogus port
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 204 Passed right context
,ok 205 Right server
,ok 206 No error should be set
,ok 207 Retry should be false
,ok 208 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 55241
,ok 209 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3CB5059A-D11F-4536-8716-32BED6C97CD6
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 210 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559
[ThaliCore] Browser.startListening
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
2017-08-24 14:51:45 - INFO th,aliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 211 Can call startListeningForAdvertisements without error
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E9508C9A-F8A7-485A-9C73-CD057AF54A08","generation":0}'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E9508C9A-F8A7-485A-9C73-CD057AF54A08 (syncValue: g89jNtEt619jnNFozKanlTef51RrRIEH)'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD09023D-741D-467A-939B-EE587D2D88D6","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3AA7804-57E2-44E7-AC1A-8164EB411284","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E9,508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB
[ThaliCore] Advertiser: session connected Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E9,508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9,508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB
,[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C
[ThaliCore] Advertiser: session connected Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E9,508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E9508C9A,-F8A7-485A-9C73-CD057AF54A08 error: max retries exceeded
2017-08-24 14:51:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"g89jNtEt619jnNFozKanlTef51RrRIEH","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:51:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'g89jNtEt619jnNFozKanlTef51RrRIEH', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:51:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:51:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD09023D-741D-467A-939B-EE587D2D88D6 (syncValue: dRmISRP,Aj286nmK2lxgsC6up9PBUFiWZ)'
2017-08-24 14:51:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD09023D-741D,-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:55 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
,2017-08-24 14:51:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C
,[ThaliCore] Session.session(_:peer:didChange:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: connecting -> connected
[Thali,Core] Browser: session connected to Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55255,
2017-08-24 14:51:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dRmISRPAj286nmK2lxgsC6up9PBUFiWZ","error":null,"portNumber":55255}'
2017-08-24 14:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: ,'dRmISRPAj286nmK2lxgsC6up9PBUFiWZ', error: 'null', listeningPort: '55255''
,ok 212 should be equal
,2017-08-24 14:51:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3AA7804-57E2-44E7-AC1A-8164EB411284 (syncValue: mje0wW8knvXZ3NMQfZZADakz9ktBeN7w)'
,2017-08-24 14:51:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3,AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:51:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55259
2017-08-24 14:52:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mje0wW8knvXZ3NMQfZZADakz9ktBeN7w","error":null,"portN,umber":55259}'
,2017-08-24 14:52:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mje0wW8knvXZ3NMQfZZADakz9ktBeN7w', error: 'null', listeningPort: '55259''
,ok 213 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3CB5059A-D11F-4536-8716-32BED6C97CD6
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:FD09023D-741D-467A-939B-EE587D2D88D6
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55255
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:B3AA7804-57E2-44E7-AC1A-8164EB411284
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55259
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B054D716-015C-4B39-BA10-2E5A76273F7C
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:B054D716-015C-4B39-BA10-2E5A76273F7C
[ThaliCore] AdvertiserRelay.deinit
,# setup
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dRmISRPAj286nmK2lxgsC6up9PBUFiWZ","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 55261
,ok 214 should be equal
ok 215 should be equal
ok 216 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:01C1451B-604C-4664-8679-5A413158C4CD
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 217 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE095084-4180-45BE-B90B-84AF67A11861
[ThaliCore] Browser.startListening
2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 218 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
2017-08-24 14:52:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3AA7804-57E2-44E7-AC1A-8164EB411284","generation":0}'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3AA7804-57E2-44E7-AC1A-8164EB411284, (syncValue: oFSKBHSWjd7OE9GHBNZJdgWGWWxLhyYc)'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB4,11284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
2017-08-24 14:52:04, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD09023D-741D-467A-939B-EE587D2D88D6","generation":0}'
,2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
2017-08-24 14:52:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:52:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276
[ThaliCore] Advertiser: session connected Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
[ThaliCore] Advertiser: session connected Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B3AA7804,-57E2-44E7-AC1A-8164EB411284 error: max retries exceeded
[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.deinit
2017-08-24 14:52:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oF,SKBHSWjd7OE9GHBNZJdgWGWWxLhyYc","error":"Connection could not be established","portNumber":null}'
2017-08-24 14:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oFSKBHSWjd7OE9GHBNZJdgWGWWxLhyYc', error: 'Connection could n,o,t be established', listeningPort: '%s''
,2017-08-24 14:52:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:52:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB5CF9B6-91FF-458D-826A-E357F5135E10 (syncValue: r7Dto5AUrmVk2xDD5iMEbnKWkNNrFBhj)'
,2017-08-24 14:52:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-08-24 14:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
,[ThaliCore] Session.session(_:peer:didChange:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55279
2017-08-24 14:52:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"r7Dto5AUrmVk2xDD5iMEbnKWkNNrFBhj",,"error":null,"portNumber":55279}'
2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'r7Dto5AUrmVk2xDD5iMEbnKWkNNrFBhj', error: 'null', listeningPort: '55279''
,ok 219 should be equal
,ok 220 should be equal
,ok 221 should be equal
,2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4 (syncValue: huJeshy2bQSlefjbmipudLgo2MXWXP5U)'
,2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55285
2017-08-24 14:52:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"huJeshy2bQSlefjbmipudLgo2MXWXP5U",,"error":null,"portNumber":55285}'
2017-08-24 14:52:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'huJeshy2bQSlefjbmipudLgo2MXWXP5U', error: 'null', listeningPort: '55285''
,ok 222 should be equal
,ok 223 should be equal
,ok 224 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:01C1451B-604C-4664-8679-5A413158C4CD
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BB5CF9B6-91FF-458D-826A-E357F5135E10
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55279
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55285
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] Session.deinit peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"r7Dto5AUrmVk2xDD5iMEbnKWkNNrFBhj","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 227 specific error should be returned
,# teardown
,ok 228 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'listening 55289'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 231 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 55290'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA66C6E3-BEF9-41CD-B4AC-D19D98D5E698
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,ok 232 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 233 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,# teardown
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 234 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 55291'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBF57733-DF22-4C02-A1F5-C7F81683321D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DBF57733-DF22-4C02-A1F5-C7F81683321D
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DBF57733-DF22-4C02-A1F5-C7F81683321D", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:DBF57733-DF22-4C02-A1F5-C7F81683321D
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DBF57733-DF22-4C02-A1F5-C7F81683321D
,[ThaliCore] Advertiser.stopAdvertising() peerID:DBF57733-DF22-4C02-A1F5-C7F81683321D
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 237 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'listening 55294'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 238 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 239 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 241 network status should have certain non-empty properties
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-24 14:52:25 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 243 specific error expected
,# teardown
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 55295'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D54D1C56-000D-4540-AEAA-890EDBB4E539
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B29F20EB-5E7D-4AFC-B8C4-2477CD34EBC4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B29F20EB-5E7D-4AFC-B8C4-2477CD34EBC4
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B29F20EB-5E7D-4AFC-B8C4-2477CD34EBC4
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 55298'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1EE688A-D7E4-4C92-9BCC-EDC7970034CF
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD9E2212-F860-407B-A9CF-0BD89852F246", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FD9E2212-F860-407B-A9CF-0BD89852F246
2017-08-24 1,4:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 247 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD9E2212-F860-407B-A9CF-0BD89852F246
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-08-24 14:52:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 248 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'listening 55300'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1C34E83B-7CF7-4112-8319-615D6EFDDD7D
[ThaliCore] Browser.startListening
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1B2BFC1D-B0C9-47DE-AE08-5ADF01B65649", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1B2BFC1D-B0C9-47DE-AE08-5ADF01B65649
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1B2BFC1D-B0C9-47DE-AE08-5ADF01B65649
2017-08-2,4 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not m,atch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate, (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-24 14:52:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 249 is stopped after calling stop
,ok 250 connection should fail after stopping
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-24 14:52:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 253 error description matches
,# teardown
,ok 254 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-24 14:52:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 256 error description matches
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 258 IMPLEMENT ME!!!!!!
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 261 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-24 14:52:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 264 NOT IMPLEMENTED # SKIP
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 268 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-24 14:52:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 269 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55303'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7460D00-6054-4C81-9C0F-D0203DCDE67D
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55304'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1FE1785C-72B5-4E78-AC07-7696CC96CB10", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1FE1785C-72B5-4E78-AC07-7696CC96CB10
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1FE1785C-72B5-4E78-AC07-7696CC96CB10
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 276 discoveryActive matches
,ok 277 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55306'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'listening 55307'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D359FB51-F3EF-4861-8B69-797EA0895CE7
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BCA9029F-6CD7-44F2-BD36-3A3AB31178A9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BCA9029F-6CD7-44F2-BD36-3A3AB31178A9
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
2017-08-24 14:52:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-,4064-AB9D-571BC6BA42B4", generation: 0)
2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
ok 279 portNumber equal null
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BCA9029F-6CD7-44F2-BD36-3A3AB31178A9
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'listening 55309'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A21C39C3-4A3F-46BA-B16E-602CFA61B286
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB5CF9B6-91FF-458D-826A-E357F5135E10 (syncValue: rNC6xKyaKwmiz6am4nXua0u5jUv2GC94)'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:36 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
2017-08-24 14:52:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}]'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:52:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rNC6xKyaKwmiz6am4nXua0u5jUv2GC94","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rNC6xKyaKwmiz6am4nXua0u5jUv2GC94', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:52:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3304B754-50D5-4361-A23C-5327C08FA6E5 (syncValue: OHI26mOemFkbKTmDbRMyYD1,zlIH985tA)'
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3304B754-50D5-4361-A23C-5327C,08FA6E5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55315
2017-08-24 14:52:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"OHI26mOemFkbKTmDbRMyYD1zlIH985tA",,"error":null,"portNumber":55315}'
2017-08-24 14:52:40 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'OHI26mOemFkbKTmDbRMyYD1zlIH985tA', error: 'null', listeningPort: '55315''
,2017-08-24 14:52:40 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [1, 6, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:52:41 - DEBUG testUtils: 'Got response data'
2017-08-24 14:52:41 - DEBUG testUtils: 'Got end'
,ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8
[ThaliCore] Advertiser: session connected Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
[ThaliCore] Advertiser: session connected Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
,[ThaliCore] Session.session(_:peer:didChange:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
[ThaliCore] Session.startOutputStream(with:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [1, 6, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8
[ThaliCore] Session.startOutputStream(with:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 6, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A21C39C3-4A3F-46BA-B16E-602CFA61B286
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,2017-08-24 14:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:3304B754-50D5-4361-A23C-5327C08FA6E5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55315
[ThaliCore] VirtualSocket.closeStr,eams() vsID:8
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:9
[ThaliCore] Virtu,alSocket.closeStreams() vsID:9
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] Virt,ualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] Session.disconnect() peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 6, 9, 10]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [1, 6, 10]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 6]
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
[ThaliCore] Session.session(_:peer:didChange:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] ,AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
,[ThaliCore] Session.deinit peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
[ThaliCore] AdvertiserRelay.deinit
,# can still do HTTP requests between peers with coordinator
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 55319'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
2017-08-24 14:52:53 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}]'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 84CB1FE5-6959-4935-8218-C20EE2F08B52 (syncValue: VIcsxJHAFQqDVx,nHae47GnzVS90OztGJ)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.conn,ectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08,B52", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketD,isconnected:stoppedListening:)
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","generation":0}]'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","generation":0}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"28,3DB3E7-9F5D-4C43-8B90-8282EA781BA5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,4CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
2017-08-24 14:52:59 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
2017-08-24 14:52:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:52:59 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "84,CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:84,CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:84CB1FE5,-6959-4935-8218-C20EE2F08B52 error: max retries exceeded
2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VIcsxJHAFQqDVxnHae47GnzVS90OztGJ","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VIcsxJHAFQqDVxnHae47GnzVS90OztGJ', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:53:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 283DB3E7-9F5D-4C43-8B90-8282EA781BA5 (syncValue: 6qagZGx,tLnKO0GDPxvZSze96w7W1HCf1)'
2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:283DB3E7-9F5D,-4C43-8B90-8282EA781BA5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] Advertiser: session connected Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55333
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6qagZGxtLnKO0GDPxvZSze96w7W1HCf1",,"error":null,"portNumber":55333}'
2017-08-24 14:53:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6qagZGxtLnKO0GDPxvZSze96w7W1HCf1', error: 'null', listeningPort: '55333''
,2017-08-24 14:53:08 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [1, 6, 11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:53:08 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:53:08 - DEBUG testUtils: 'Got end'
,ok 284 response body should match testData
,ok 285 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] Session.startOutputStream(with:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [1, 6, 11, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-08-24 14:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55333
[ThaliCore] VirtualSocket.clos,eStreams() vsID:11
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeS,treams() vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 6, 11]
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:11 [1, 6]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6qagZGxtLnKO0GDPxvZSze96w7W1HCf1","error":"Session disconnected","portNumber":null}'
,# calls correct starts when network changes
,2017-08-24 14:53:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,[ThaliCore] Session.deinit peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] Session.deinit peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
[ThaliCore] BrowserRelay.deinit
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 288 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'listening 55336'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
[ThaliCore] Browser.st,artListening
2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:11 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:78AAC586-1402-4A0D-8C29-BFD492D2F632
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93922256-C7C8-4DB9-B61E-DC3CCB8151D5 (syncValue: 7CJhn0QesVgEr7HIHhDOcGM1wFSZa9dJ)'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","generation":0}]'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","generation":0}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9F56726-E546-46CD-B1A6-ABCA2203A872:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9F56726-E546-46CD-B1A6-ABCA2203A872", generation: 0)
2017-08-24 14:53:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}]'
2017-08-24 14:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}'
,2017-08-24 14:53:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:53:13 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:53:13 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:53:18 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:93,922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,3922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:53:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7CJhn0QesVgEr7HIHhDOcGM1wFSZa9dJ","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:53:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7CJhn0QesVgEr7HIHhDOcGM1wFSZa9dJ', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:53:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:53:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 089F34F7-2665-42AE-B516-FAD462A067E4 (syncValue: u3eaxdq9FtPZXeQRyV8GRLh,VDcXytsgR)'
2017-08-24 14:53:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:089F34F7-2665-42AE-B516-FAD46,2A067E4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55347
,2017-08-24 14:53:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u3eaxdq9FtPZXeQRyV8GRLhVDcXytsgR","error":null,"portNumber":55347}'
,2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'u3eaxdq9FtPZXeQRyV8GRLhVDcXytsgR', error: 'null', listeningPort: '55347''
,2017-08-24 14:53:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [1, 6, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B
[ThaliCore] Advertiser: session connected Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B state: notConnected -> connecting
,2017-08-24 14:53:22 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:53:22 - DEBUG testUtils: 'Got end'
ok 289 response body should match testData
,ok 290 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
[ThaliCore] Advertiser: session connected Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B
[ThaliCore] Session.startOutputStream(with:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [1, 6, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
,[ThaliCore] Session.session(_:peer:didChange:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
[ThaliCore] Session.startOutputStream(with:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [1, 6, 13, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:78AAC586-1402-4A0D-8C29-BFD492D2F632
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:53:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [1, 6, 13, 14]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [1, 6, 13]
,[ThaliCore] Session.session(_:peer:didChange:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
,[ThaliCore] Session.deinit peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
[ThaliCore] AdvertiserRelay.deinit
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [1, 6]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.disconnect peer:089F34F7-2665-42AE-B516-FAD462A067E4
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55347
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:089F34F7-2665-42AE-B516-FAD462A067E4:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"u3eaxdq9FtPZXeQRyV8GRLhVDcXytsgR","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
[ThaliCore] BrowserRelay.deinit
,# will fail bad PSK connection between peers
,ok 292 FIX ME, PLEASE!!!
,# teardown
,ok 293 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-08-24 14:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 294 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-24 14:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 295 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 296 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 297 specific error should be returned
,# teardown
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 298 error should be null
,ok 299 error should be null
,# setup
,ok 300 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 301 specific error should be returned
,# teardown
,ok 302 error should be null
,ok 303 error should be null
,# setup
,ok 304 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 55351'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 307 error should be null
,ok 308 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 309 error should be null
,ok 310 error should be null
,# setup
,ok 311 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 55352'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E0CF693F-3BDC-4ECC-B3E9-FC19ECC96246
[ThaliCore] Browser.st,artListening
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 312 error should be null
ok 313 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 314 error should be null
,ok 315 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 316 error should be null
,ok 317 error should be null
,# setup
,ok 318 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 55353'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
,ok 320 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 321 error should be null
,ok 322 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83
,[ThaliCore] Advertiser.stopAdvertising() peerID:9E733674-1F0D-4DF0-BE8E-3F22B8EEEF83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 323 error should be null
,ok 324 error should be null
,# setup
,ok 325 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 55356'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 326 error should be null
,ok 327 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 328 error should be null
,ok 329 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 330 error should be null
,ok 331 error should be null
,# setup
,ok 332 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-24 14:53:31 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 333 This should not cause wifi to fail
,ok 334 native router should be bad
,# teardown
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'listening 55357'
,ok 338 first call should succeed
,ok 339 first call should succeed
,ok 340 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
,ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-24 14:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 344 error should be null
,ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-24 14:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 347 error should be null
ok 348 error should be null
,# setup
,ok 349 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-24 14:53:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2fe31780-1c5a-4798-8b0c-e5a9a39465fa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 350 should be called once
ok 351 should not have been called more than once
,# teardown
,2017-08-24 14:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2fe31780-1c5a-4798-8b0c-e5a9a39465fa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 352 error should be null
,ok 353 error should be null
,# setup
,ok 354 ThaliMobile should be stopped
,# can get the network status
,ok 355 network status should have certain non-empty properties
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,2017-08-24 14:53:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-08-24 14:53:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-08-24 14:58:33 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER res,ult: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-08-24 14:58:33 - I,NFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: pa,ssed - enqueueAtTop and run backwards'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independent,l,y'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - peerAvailabilityChanged - peer added/removed to/from cache (native), error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/D3,2578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_m,odules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-08-24 14:58:33 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-08-24 14:58:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4,E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E2,1-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D32578AC-37D4-4E21-8A8D-C72215E5C426/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
