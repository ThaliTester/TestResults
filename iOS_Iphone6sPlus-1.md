#### Test 1374640318f8a044_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F863240E-5FE6-49B3-B794-66E318D68F5C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/F863240E-5FE6-49B3-B794-66E318D68F5C/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59989"
,(lldb)     command script import "/tmp/F863240E-5FE6-49B3-B794-66E318D68F5C/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:46:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "41AE7A8B-9936-4C4F-9DAF-82CFAAAB28B4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:41AE7A8B-9936-4C4F-9DAF-82CFAAAB28B4
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FE58390F-DA55-46A8-BCEB-AE85744ECC4C
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:78D4E5CF-5438-49A2-AD18-DD27F3BDA6B6
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "24F0836C-CB08-49E2-A699-31C81886490D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:24F0836C-CB08-49E2-A699-31C81886490D
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:24F0836C-CB08-49E2-A699-31C81886490D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "24F0836C-CB08-49E2-A699-31C81886490D", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-08-24 14:46:05 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.357788860797882
,2017-08-24 14:46:05 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-08-24 14:46:05 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:24F0836C-CB08-49E2-A699-31C81886490D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "24F0836C-CB08-49E2-A699-31C81886490D", generation: 0)
,2017-08-24 14:46:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-24 14:46:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-24 14:46:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-24 14:46:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-24 14:46:08 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-24 14:46:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:46:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:46:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:47:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:47:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4,675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-08-24 14:48:37 - DEBUG CoordinatedClient: 'connected to the test server'
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
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-08-24 14:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
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
,2017-08-24 14:48:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-08-24 14:48:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
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
,2017-08-24 14:49:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:01 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-08-24 14:49:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D0ED9632-589D-419E-9FEE-04184A04BC87
[ThaliCore] Browser.startListening
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:49:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3420DFF0-75B8-491C-B540-FCA60C16F2AF
[ThaliCore] Browser.startListening
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24, 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:05 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A65C8798-DCAB-42A8-98D3-F34D7D904CD4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A65C8798-DCAB-42A8-98D3-F34D7D904CD4
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising(,)
[ThaliCore] Advertiser.stopAdvertising() peerID:A65C8798-DCAB-42A8-98D3-F34D7D904CD4
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05, - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "33C51DDD-4DEE-40F3-9037-E2B221C7890C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:33C51DDD-4DEE-40F3-9037-E2B221C7890C
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "33C51DDD-4DEE-40F3-9037-E2B221C7890C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:33C51DDD-4DEE-40F3-9037-E2B221C7890C
2017-08-24 1,4:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:4,9:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:33C51DDD-4DEE-40F3-9037-E2B221C7890C
[ThaliCore] Advertiser.s,topAdvertising() peerID:33C51DDD-4DEE-40F3-9037-E2B221C7890C
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:06 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0CEB9198-C417-4D4F-901C-D334A7FD5AF8
,2017-08-24 14:49:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:414FDD50-91E6-4606-86AD-A9580C9B0,437
[ThaliCore] Browser.startListening
2017-08-24 14:49:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:09 - INFO thaliMobile: 'Received state ({"discovery,A,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:09 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
ok 76 peers must be an array
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0CEB9198-C417-4D4F-901C-D,334A7FD5AF8
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:11 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42BA428F-605E-484E-AD76-070619DC0473
[ThaliCore] Browser.startListening
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0607900-813D-4C11-B1D3-06B66F9F9C6D","generation":0}'
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A0607900-813D-4C11-B1D3-06B66F9F9C6D (syncValue: iao6ya0NRSTpYLCuU0y7jBAR5tQLXVfG)'
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FFA4D95-6464-4803-8737-E537C6B4DECB","generation":0}'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E3D14BF0-885E-42DE-AEF8-51DA6C19C621","generation":0}'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A0,607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:49:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iao6ya0NRSTpYLCuU0y7jBAR5tQLXVfG","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iao6ya0NRSTpYLCuU0y7jBAR5tQLXVfG', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:49:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1FFA4D95-6464-4803-8737-E537C6B4DECB (syncValue: KWsA5RtEo3uJFBTGWXo977T,3y9oGDLbR)'
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1FFA4D95-6464-4803-8737-E537C,6B4DECB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892
[ThaliCore] Advertiser: session connected Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54930
2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KWsA5RtEo3uJFBTGWXo977T3y9oGDLbR","error":null,"portN,umber":54930}'
2017-08-24 14:49:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KWsA5RtEo3uJFBTGWXo977T3y9oGDLbR', error: 'null', listeningPort: '54930''
,2017-08-24 14:49:18 - INFO testThaliMobileNative: ''
ok 83 Must have listeningPort
ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-08-24 14:49:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78
2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:1FFA4D95-6464-4803-8737-E537C6B4DECB
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54930
[ThaliCore] Session.disconnect() peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4A5D4407-7425-41D9-94AF-6EE52E81E892
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4A5D4407-7425-41D9-94AF-6EE52E81E892
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CF3C2297-B546-4712-88B9-DA70154DC511
,2017-08-24 14:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CD220B91-3711-48B7-AA0B-716EED0F,01D0
[ThaliCore] Browser.startListening
2017-08-24 14:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:19 - INFO thaliMobi,le: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
2017-08-24 14:49:19 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1FFA4D95-6464-4803-8737-E537C6B4DECB","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1FFA4D95-6464-4803-8737-E537C6B4DECB, (syncValue: zAadxyrtrAnAs82T013E1C14HPVtr9g6)'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B,4DECB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621,", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailabl,e":true,"peerIdentifier":"E3D14BF0-885E-42DE-AEF8-51DA6C19C621","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3374CEC-5CAF-4EC9-8F24-18B03362EC6D","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
2017-08-24 14:49:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
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
2017-08-24 14:49:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zAadxyrtrAnAs82T013E1C14HPVtr9g6","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zAadxyrtrAnAs82T013E1C14HPVtr9g6', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E3D14BF0-885E-42DE-AEF8-51DA6C19C621 (syncValue: 7uApkY3,DyncpyOTojXLHRzFwo6BwvSx2)'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3D14BF0-885E,-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E3,D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:49:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7uApkY3DyncpyOTojXLHRzFwo6BwvSx2","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:49:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7uApkY3DyncpyOTojXLHRzFwo6BwvSx2', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:49:33 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:49:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3374CEC-5CAF-4EC9-8F24-18B03362EC6D (syncValue: gQHybuepbs9K7EvOwkkSGBY,zWPK8y8mG)'
2017-08-24 14:49:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03,362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 ,1,4:49:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54937
2017-08-24 14:49:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gQHybuepbs9K7EvOwkkSGBYzWPK8y8mG",,"error":null,"portNumber":54937}'
2017-08-24 14:49:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gQHybuepbs9K7EvOwkkSGBYzWPK8y8mG', error: 'null', listeningPort: '54937''
,Connecting to the localhost:54937
,Connected to the localhost:54937
2017-08-24 14:49:35 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-08-24 14:49:35 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,2017-08-24 14:49:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:CF3C2297-B546-4712-88B9-DA70154DC511
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54937
[ThaliCore] Session.disconnect,() peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1A2F523B-551F-43F6-8F63-E9BA6B74AA01
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:18D49381-D1C1-4D8C-84B7-C71E493F,7B6B
[ThaliCore] Browser.startListening
2017-08-24 14:49:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:46 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3374CEC-5CAF-4EC9-8F24-18B03362EC,6D","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3374CEC-5CAF-4EC9-8F24-18B03362EC6D (syncValue: 1HZw1fpdFG2dNvFPIeVWbnRMGklo2Uml)'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3,374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A","generation":0}'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
2017-08-24 14:49:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD12190F-C11B-4D3D-90CA-E076C0040F6F","generation":0}'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:48 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", g,eneration: 0)
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running ,t,est!'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B3374CEC,-5CAF-4EC9-8F24-18B03362EC6D error: max retries exceeded
2017-08-24 14:49:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1HZw1fpdFG2dNvFPIeVWbnRMGklo2Uml","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1HZw1fpdFG2dNvFPIeVWbnRMGklo2Uml', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD12190F-C11B-4D3D-90CA-E076C0040F6F (syncValue: 0WcBQv9,4mPt9mkt9KjZI2uadcdYBna5D)'
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD12190F-C11B,-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
[ThaliCore] Advertiser: session connected Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
,[ThaliCore] Session.session(_:peer:didChange:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
[ThaliCore] Session.startOutputStream(with:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
[ThaliCore] Session.startOutputStream(with:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
[ThaliCore] Session.startOutputStream(with:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [1, 2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (10240 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (3954 bytes):'
2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (8760 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received (7624 bytes):'
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54956
,2017-08-24 14:50:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0WcBQv94mPt9mkt9KjZI2uadcdYBna5D","error":null,"portNumber":54956}'
,2017-08-24 14:50:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '0WcBQv94mPt9mkt9KjZI2uadcdYBna5D', error: 'null', listeningPort: '54956''
,Connecting to the localhost:54956
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,Connecting to the localhost:54956
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,Connecting to the localhost:54956
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [1, 2, 3, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:54956
,Connected to the localhost:54956
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [1, 2, 3, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
Connected to the localhost:54956
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [1, 2, 3, 4, 5, 6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3, 4, 5, 6, 7]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [1, 3, 5, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) ,client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,ok 91 correct string length
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [1, 3, 6, 7]
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [1, 3, 6]
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] Advertiser: session connected Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:40409F35-D016-4907-82F5-3223812E2E18 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40409F35-D016-4907-82F5-3223812E2E18
,[ThaliCore] Session.session(_:peer:didChange:) peer:40409F35-D016-4907-82F5-3223812E2E18 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] Session.startOutputStream(with:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [1, 3, 6, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] Sess,ion.startOutputStream(with:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [1, 3, 6, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] Session.startOutputStream(with:) peer:40409F35-D016-4907-82F5-3223812E2E18
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [1, 3, 6, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (213 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received all data: pA8fMg1kAm,4GsFu7LGuVFcK0X2esYQyHkLlkWcVB2lAyTyDXG9XgeFvdiMtYOEcZ0iT6XYw11Qyz7deRPYwQvS57Tfs7IBmjyA62bgup4S4sqUxJpcTlx1qrkyrINAAwGQDg6M3S5PykMMHtwdaFye7gikuPQqURLW2TmPIVOqCxiLMUOF82lPoUc0Mk8aNhN5jjXANccVwIEEkdTPyUQkK1NRnKZ0VnCP1pW9tPMMHlMQ3m4aAVpxYPfy7bDjRHSpezzFyoVL,9FvKZQZBRJUb5WqikbAizOj1RDtl7g4vAibozmKLJ5Bf9JNu8E8mseFHhEleyKKP1XJR4FUBpOuYQX7OyLnPaN1uCnmajddAo6xTok7n2sKR2WiCixhvh4Ri85y3sOkdwdQrHoK5UvOjxTPq1Ybg8MfL4518BaAdj0AkycqaASyXIHlj9MW7f4WQBapgmsDltHFVEAJEKlCGTMD6KBjAcDp2CwEkhVoMLzX0QrcN8GJvzX5nHDETnnRIex1Zv6dX,VKgjxHveRcX0LpVkPWdzwHeQwFjD7bu5Q8vRjbOQdFRTu2ZtKlswZf15DcpPPBlQ55XLq1VWJq876DhgVbP8qTxBREzQCnVesX5NUUbaiFoACnb8UR96oFjOAAotmNBeJNDWNURIjBUaiUdwe3SPvRGaea2ySCbQ5hxCWJw9fvfpe7uML0QrU1WJwmZpitlmQI1XiZBksl0pXnwlzyM2bcWZgal8AGocIUAFnlvCi51yeXdzOOmE5Lfv8yQ11mO,t,5xiVPdzze0KAWI7l5L9B8DtRoNc00pMWTf3MHXTace2aq9y4PA39PbtfLGDtriu1sUm309iE92c3rtfrlbbGs3wde2SFPEQ9nasOOoOIe44IhCQTFN6zIFWu49Hz6V0BxnfY5NlDIIW1wInmi1uCUIOzggUD90a4AbSpisyGyBxJI7ZZONWYOqrQbq1hwD1IPXhoLMILQjhAh0fqw2usr22GHkCsykrst7OO2cpFLEoVD2kUMZxAY71AyAeW3fhk,imHLqvzXkCu3rcqJ3Un6AgfD6OCTDPkJNYclRGoRBhHvk0gnTy4f5ITex2Ys8B14kR2se4RhzShD0mwSRrfTTWet8Bhyc5Us4gdkkxOEWz7iunhjzSrGLqjQ5S3M9L9vCL5lnvutGy9nrwcgreKdIY2kv81Gjo6MMn9oYlhRhHsPjJe1g10j3f0n64PQUQpUzhFOIxEvgbwjl72sSXflU6bYZfnSaF7thH7ZEnO0Mr9UhI2iD4oCV9nG5slnh8vf,HY40GHyqqPICPIxU6tXeRv1u7c9uOVNNwvyGoRg4dkDG5qot7uVfSLRBlBcGNmNiBZ9FzXTfRZdj0vYQ0Zkq7k9uWlEZnQGgLqbANDpQpRlp42dYNW7l41V64r8CtxHUSlOS1j6rTILDmcGyUve6oIDzlV7P15YFv4BTcuD4wdEZJNA84IV3eO67RXuHWewJWb506mESTH2nK0M08LDJu0DSbR2Z3IO5Lb8ICNaxVoeJ29vPgAACPvY62788KDW8,QpZOrNmU0EGrueUF4J0TtiggSUIgRNdYGh1WQ857kSJrw2xmo2L40hPZdAwwFpzveF0ZpINAAAPuFuOohsbPQq7h9N0wmOiUnXSbhhaWeS7uJuOtvOe1FuyNeoHPYeEBkR91be0ixst6rQcTB4jXwzYnl3TEAm4HbZb0t5SS6E66vNyW0TCK9UOcvTlMmNtLCe8SoDJ9MOSjNZmePt87JQDZq9sOlnNww6OzqTTGxLw4kZA3GpdVuW68dgYm4zy,D,Xo2fA4BfIi484lNtnNZFUaGX3RsditZFRc2v8PHI1KIMTHIenJqyL2zyEkZaObUFCGIOw2rM6UveStoBuosqaAY3lhnggngjOojPzS2AMbDW4b61AhgiEIXlk96MtEtCOOkVksdNrsyBE9K3gOWMbzm1V6STss6gI7XkdWjohqsBFSB1PZgzmj8bzKnMozMt0kY4LSSC0WfJrwcMyPpIRGBv8vWZ47Nbhm6L1vKykZMA5FV4SXXgE3RQJ2Uxq2dv,xaWSyZLS6u5sTcZfeYjGNl589uwcpy408qLcANWopH8HIzsPEYNR8Q24r172Z6TDkKSVn0HDTfxpcnriES3095Wn2gtsgUwb7Aoh0JKvVjentNHk8dpCwhzW66LNKDVckh3KGx7wYiuquJcRCsjdvvxob4hD2KY6TEtdQF0MrMuzLfUMpe5FvT3xaDwmQUjpg80xB2Rn36elkSbrXEfTO73xqcB1sFlVsqmX6LOoyPNHg2WRbL7uadXX52ks3Mqr,w1cUevNj5nN37uhaNGM1kjOQi1zRowCtKOurwfVKiKdarxqgLyDsY9ZyUVeDrrywQwxaVxZzQcdRbtlHY5eGlNjNauX7vXa8TH2M1jdTL913kF1EygmFsSN1TqPIJd1WsTizZSnvlXTkha0XMhToxIdntNCLcsHWhFzt7okB1uesWTMo3aM4HECncdwNWuVmQ7kFRv5pKIZfWzIlj51AAUjbORpRbQUrNUumj5aqHtcuwO7zgEBfhY838eLyIyat,tiMXPkjqa6sgmwk55nOAZnx4zxIsiMcZLPvT2yAjosDbURGpWwh8Qlga4rNGlwYdiYoSPUdLb2WuyHvL5U2evpt2efP82TR5DxSbfmkT88DZ7AWbULetVRk5L6gLdCCTOxv5HMONW5tYEpmxNXW2NARhxHcBtUZK7JHRJ0TqFQz83rXwpK1Cb2TAyob9lqmTMW8Ll94PwE7Z1IX4rJX1V6i8HUAeaMZO0oJEsHnfimN9hqVR9gwQWR18XunFtxb,9,7YFszGiBQ0eFU6iOssGxTmQ1ldX792z94WLfB14i22gSAYhMz2zbvg9pCajBHWHQIGtgyrl15JfHB3xc71oGwqeoFEVOefiEAdiMl4mTvDbz0YHt5gMdlHYqOMx1JITEdDJgRSu3fbsUec2KiBKIbxG3lQD5RNAXIDk7fsMX2fkK4Tz4YaHuppjAPzRjSyuW7o697bsnBUqMMMEQyc6WaBTvwKduIXc3X6HhUt8cpYJW6hPR8e2pbKT9HcCbN4X3,4N8kdpbVNppgI2BRT0bHCFlWtjYYoDg2lSgjPfHKJ7IvJPFzm33jPJYgrb6gEmqN3pOLGHJvnWM3eFZS2xm0GYY9ox5ynxDb4nIMTvi3uj4s6XaCv3ENZyFMKgtake7WNDc951KxlUxxGUDzIkfZdaA34N8TxLertap6cGiJ6dv40B8noo00d3RIOnTAFah7dv3T4JW6vF2Yz2mbwlIs2T08Z2cfrb8bnNta6TvzmTl2XgrLUTcorGE0HW2DrAie,pNx7kKK2HJ777Al0kCQRAyX4uR8hwiBpAeTmiXdUYFpmHxoeHkx5IdPmGt22tC1cG9zysCPozhVpdPDmuW69c1lGa488S9s3atH2NNvnPvz5yrBT56JUtI0AD0JNFTyMTQpw9fDBpwUTP1Fm93ar7uQqCh16Y7AiWFs1zO0YwfO4sOrucJDb7ANxil7Pl8Xa3KlgIpTmedoDFk9pRhUo36kbbYJY1Ky6PyideTc8o4NwOCq0bgdcSrdec9tf1g4I,xowCFNVwTw3eIYsG8qBSW3p9EVMTEUNrSsfamWZCacfTtbyNa6yYSPVGR0BIlBZ5q7w9WImqSxkLpxx6zoGl2lbWRnz9HT8zxODk2sn9fTKIN7kwzELKzdGZ8UQohqRe4aArl3IItShHwMdr2Cz2qto9fBEyKP1tpcJqWbjWAongBLYZzeHlXjQMZ2qclPmjvKrhc3zlNW3i1hGouaGlZgRUwkkstQBBF2egnjYVWyleUE7DAMAbTxFUCDbrmcc,a,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'
2017-0,8-24 14:50:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (5688 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (2403 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server sends data back to client (163,84 bytes):'
2017-08-24 14:50:11 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:8 [1, 3, 6, 9, 10]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [1, 3, 6, 10]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [1, 3, 6]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-24 14:50:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:1A2F523B-551F-43F6-8F63-E9BA6B74AA01
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14,:,50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54956
[ThaliCore] Session.disconnect() p,eer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:40409F35-D016-4907-82F5-3223812E2E18 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:40409F35-D016-4907-82F5-3223812E2E18
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:50:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
,[ThaliCore] Session.deinit peer:40409F35-D016-4907-82F5-3223812E2E18
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:81E2C700-B307-4017-AC4A-E1CFD3A79A7E
,2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
,[ThaliCore] Browser.startListening
,2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
2017-08-24 14:50:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"DD12190F-C11B-4D3D-90CA-E076C0040F6F","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DD12190F-C11B-4D3D-90CA-E076C0040F6F, (syncValue: 6Gi5EEuBUSF8RQT9GU9og3sGVAE0FgFl)'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C00,40F6F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88F25900-E82C-4806-BEBE-C7A0F07CDFEA","generation":0}'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
2017-08-24 14:50:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EAE4AA8F-4F52-4E41-A600-55B6A1A4497A","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,D12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DD12190F,-C11B-4D3D-90CA-E076C0040F6F error: max retries exceeded
2017-08-24 14:50:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6Gi5EEuBUSF8RQT9GU9og3sGVAE0FgFl","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6Gi5EEuBUSF8RQT9GU9og3sGVAE0FgFl', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49113C2E-45AB-4903-A759-BC5216FA0D18 (syncValue: NHIMrJ58UHaKLZTPJGes6YMECJ74MtEL)'
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:118523FF-7B2E-4F71-8768-9A523E661A64
[ThaliCore] Advertiser: session connected Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:118523FF-7B2E-4F71-8768-9A523E661A64 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:118523FF-7B2E-4F71-8768-9A523E661A64
,[ThaliCore] Session.session(_:peer:didChange:) peer:118523FF-7B2E-4F71-8768-9A523E661A64 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:118523FF-7B2E-4F71-8768-9A523E661A64
[ThaliCore] Session.startOutputStream(with:) peer:118523FF-7B2E-4F71-8768-9A523E661A64
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [1, 3, 6, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,Server received psk id: psk-id
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:49113C2E,-45AB-4903-A759-BC5216FA0D18 error: max retries exceeded
2017-08-24 14:50:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NHIMrJ58UHaKLZTPJGes6YMECJ74MtEL","error":"Connection could not be established","portNumber":null}'
2017-08-24 14:50:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NHIMrJ58UHaKLZTPJGes6YMECJ74MtEL', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:50:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88F25900-E82C-4806-BEBE-C7A0F07CDFEA (syncValue: Fmt25lV,Llyy5kgMRTyGKQDnPFXjXKffY)'
2017-08-24 14:50:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:35 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-24 14:50:35 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:54987
,2017-08-24 14:50:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Fmt25lVLlyy5kgMRTyGKQDnPFXjXKffY","error":null,"portNumber":54987}'
,2017-08-24 14:50:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Fmt25lVLlyy5kgMRTyGKQDnPFXjXKffY', error: 'null', listeningPort: '54987''
,Connecting to the localhost:54987
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [1, 3, 6, 11, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:54987
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed b,y remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.,closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [1, 3, 6, 11]
,2017-08-24 14:50:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:81E2C700-B307-4017-AC4A-E1CFD3A79A7E
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:54987
[ThaliCore] Session.disconnect,() peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:118523FF-7B2E-4F71-8768-9A523E661A64 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:118523FF-7B2E-4F71-8768-9A523E661A64
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:118523FF-7B2E-4F71-8768-9A523E661A64
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE55610F-A9BD-432B-9147-16B5D83,755A8
[ThaliCore] Browser.startListening
2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discover,yActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
2017-08-24 14:50:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88F25900-E82C-4806-BEBE-C7A0F07CDFEA","generation":0}'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88F25900-E82C-4806-BEBE-C7A0F07CDFEA (syncValue: jrzfxm0ovMKHLQrJu0N9b8fq2lY9dTFx)'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07,CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EAE4AA8F-4F52-4E41-A600-55B6A1A4497A","generation":0}'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] B,rowser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
2017-08-24 14:50:39 - DEBUG thaliMobileNat,iveTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
2017-08-24 14:50:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}'
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:40 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
2017-08-24 14:50:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestU,tils: 'Already running test!'
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,8F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,8F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:88F25900,-E82C-4806-BEBE-C7A0F07CDFEA error: max retries exceeded
2017-08-24 14:50:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jrzfxm0ovMKHLQrJu0N9b8fq2lY9dTFx","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jrzfxm0ovMKHLQrJu0N9b8fq2lY9dTFx', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49113C2E-45AB-4903-A759-BC5216FA0D18 (syncValue: UfoJShB,N4Tq5RnmY7J4yujY7VVLvQ9ne)'
2017-08-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49113C2E-45AB,-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870
[ThaliCore] Advertiser: session connected Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870
[ThaliCore] Session.startOutputStream(with:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,3 [1, 3, 6, 11, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:55 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
[ThaliCore] Advertiser: session connected Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F state: notConnected -> connecting
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,2017-08-24 14:50:56 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:57 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,9113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:50:58 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:58 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
,[ThaliCore] Session.session(_:peer:didChange:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
[ThaliCore] Session.startOutputStream(with:) peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [1, 3, 6, 11, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (18615 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (18544 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (8596 bytes):'
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server data flushed',
2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-24 14:50:59 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:49113C2E,-45AB-4903-A759-BC5216FA0D18 error: max retries exceeded
2017-08-24 14:51:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UfoJShBN4Tq5RnmY7J4yujY7VVLvQ9ne","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:51:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UfoJShBN4Tq5RnmY7J4yujY7VVLvQ9ne', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:51:00 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:51:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 15347059-D945-4F19-8F57-C4DCE18EF619 (syncValue: Tf52lVr,vzivs1KcFHPTtymV7NOQ7NkPB)'
2017-08-24 14:51:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15347059-D945,-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:00 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-08-24 14:51:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:51:00 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:15347059-D945-4F19-8F57-C4DCE18EF619:0 state: notConnected -> connecting
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:01 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:02 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:02 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:02 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:15347059-D945-4F19-8F57-C4DCE18EF619:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55014
2017-08-24 14:51:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Tf52lVrvzivs1KcFHPTtymV7NOQ7NkPB",,"error":null,"portNumber":55014}'
2017-08-24 14:51:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Tf52lVrvzivs1KcFHPTtymV7NOQ7NkPB', error: 'null', listeningPort: '55014''
,Connecting to the localhost:55014
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
Connected to the localhost:55014
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [1, 3, 6, 11, 13, 14, 15]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 102 got the same data back
,# teardown
,2017-08-24 14:51:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server received all data: dpe1MfmraHSgvxZ6oMBOHaCWTOEiA9aiihx7W2NEAAO0fdp0PGtoZpCyc7CAFEz5j4Eyc6XII4KFj5mjlwDr9UFVhUF82T28LpykPn3DArUD1xgT3TeuuRiZmmurDhcjHrBYX6opHDlDSaFNszKMOYFcLpkz2Ua6ggyZusBpfZ5ktb3hdm,HeljlWVIhLON0gGbQhOVxuOwT1UP3rVFgndNsRV3RRPMwkUTzZZcceVIqctgM1BuEneB4dVe6tpJPDoObBVipvkZnvrk9BtRkaS4CFzDxkgEqIDN541eGfmSpemyGN6aZSEnF60FQF7qxGoJUjhO0kZaQimOoyScZSJkEMpthLYjsWMCKIaVkyVuQodgOSmPpxGNO2scBsp2RDNhWwO6eRUD0hTkHC6pItBNWGpWvs4TotHGgng6glz28LTGUXBM,9jS7FB4y8Ey9lacbegvyNEhiTExOGZFpTQw8pchgibie81xeJQzuw1tgZotnE2yKNDMuHdAKJKJQnSB9SlnDOpMQuNkHTS6A2f79606sLI0Ay1ZZYoT70142jwWYR4W60JzMK9Y5MHrtNLwfg6A2e0KzXD5DnlZOBDxlWATAGs2r2lMUrygHFnu1P8iJT5v4IFurmcMtSBwPuJxMicoNvp1PDaMGzgY717ktjXGNefcY5RQkMzZEIKIJ7Uj4G60Y,vzXLZM0vSKoSmk5dUcpjtZFshLDBigIwjT5hCJBgcn3rlZ9ViHpWRBvWHh2x4LMzQ6rssCJ5v0o5CIVr5ZNf4eg0Q8UXi0W7BrFFisnc2lfgSoyykgTcfNWSAcpmKhUwi0efEmMPCj3x1ZFjd1df0NQPe7ep8FXuobKCeiRLmxybADLVyq1BtW0VBKEhnJMiXNp0Diwfsq055FBlWaXqXWyvRmI5tfQ924qCCXuYWyTP7E0C1kfYYzlqb9aAzlZ,e,OJ1YhB2VvrVAASPrd01ax5nrFHUsb6kq8IB6FZgvvm8zCtxkMu4yPko6HgJIa7y7tSOw1t3y2wYxJBHa5Wg7tKCE7vi382b0ktfmZxU1HS3K52IWKyIjGY2jEFNsOnzxl6jfDkN70TH4sogvoUiB3O3Jx35J18jGDnXtddZQ6VJ9ym3rP77uiHeVRXPEQbjjl9iSVqiwmlBzlrhNDQh8umbrB1UlwySMkqVypWqi3KEAHmXa7kewyUsR1tM5oFU4,J1cOTyXW0aBukZXnLxU2cPoCNkLl99PFH8QSuMFU676k3X01fzH77NXros8k2ahCipE5WufNaJ45VeKDrdgu1fJs7dtI11GDb9psDiI1IcFKOU2rqbIPd2hVtdH6Fb98n5Vge1bKbWYc2GyZ1gicsfdqcNa1uhWR2PsC2tsX9jTig0gNf3C6qcR2bwpUdfDjGxnAx1yWxH04w2SwXTJHHNbnLqH7n5Nc3YhcnyTzohbVpxehlRZmMQ1QL8aEFlwf,6lcCVzGpnkriQgmZd0ZBrANMpcVS1FqtXtsQXHHLW0PisH22sB57JKpzxko5o5FyswkZZ7fTG132ttBhsYa0oUtF5iOUI8DWyoKkgwd29ZhIxB2FaMfcdNUBDH2ibExIDQ7tYm3p9pYt3SchkBYsSOV5zvjZezEuaqDLgz5grcDO7xzvv6UAZzjFq7c7XAD3qm45g1Wpx7b7RmcwsJaeZyFt3cUH8wGEyeqRxVByKNlAklfWq94EYd5yxKErmBtY,ayaVYuPrXUCFO2Bhx2YBP2MEii7usjYqqhtaTckdqwud91nKJHgUPShHUTt7HoVCQOVP0RlqCS5Wmg0yzwMvWqZbOPzxgJkIe6hEmyV7YjZfqNG2MhAMAdL75Z0ZB3GWl9NDfwmPBeejN0hOsckasZgJVq6F1Gv7BdGvKuXGEcY3m7QmNkXZPvsnhqwM5W10oJIOjK3um97D5MrvoUAGlin5MGAv3AMkr58FaLLnRwlD28xzPnMgMhGdGO3qH0J,l,5XRNQALKq2sbYIo2viazBPU7v0mk7wsqrWVQ0bkRZbqNmRJD35IvAxBtW1Oxbr2kG4dpaTtQfVqBhQZ5jPdlhVHzCzQRymOcya68eWj1hvitDZmeJuNz5U9PQR3JIJUGYwMB0eWm6SX6kbxnmd8AkeuaUum6Y8m7IBleF9OCsgYE1ymDZJn5SfiY8J1kdgIXBK4ZWG3jeEwS6N7weCF4EpcWUUp1HQRcufPkPrBsQ8iQwYlFpL0r90CF6G5vahSd,SvccwGtpZXO2LRtdnhCYfSrbBA29BjnRQzRWb7gHVrQZ0ToDwWK40ccVbBZR58juDCP82zUqY3dOEsiXsmyjkrgM3p3RhDBeniDUk6JeR9hTcaEztdEq9wYeHMHx04ydgnH9xxJzWuj74GgZ0rzWKakUSXeqy0uHws2gVrt1CBs7ogUU47wFzUF7tg7lOzyrVc2XbKBqa4PK46JhFf9YRMKAStTalO7HhSzTCyJPTWOPoWb04vdyYxYQhmoCQ5Bf,1s3ZMXMwXMphFOTSTZfy31PxLyWnL0j4BQb1pK2W0FKaBytUbGnHLlmzsEDt9K8tRXH8QMP44MDwRvInl25Rk8O2xHnBV6RRmoZOggFB0vlmwCJD2Ae4Bae5baueba0tiRFURtnkEbvBDZdDAP7zhyjnGZJg9xCMuE4F0x6JUlJwKQIWsPVQ4qIfv9wsIASoF2Ic6hdUhnKgc6noBlwK8dnqXjgk2WYNgzwHhk12JzKiInvBbiotpKNNComUu2fF,AyrvZh7iB6EdkOAsYvkKU6vnkOer9RYyKlWSQJu0htFcf301hqXbSapBKljxI6UWt4lxWJRhHQalffLYo4eQlAT3eefbAft5bGpvpJHAfFMAF6d5IYz7jilqo5sfFtYKiCWVfmsSy0llI8n82ME47zx2qqT7OFQDQAttf4yjUzCFHQoacrFOfbw6ocN2tIuLsWtsquYXgAqkSyyNsxF1tibT2g1qWHf6X2hi7p2f0lcwPI0hTpqUHUkNYCV28s2,m,cFlZfZqUEPUjUGsoeYr0ZDhtnjhGs4BB9EEIvfbalOtrbmI87yHnrZlhDneMIxvLtY456NBLglOacf3Dw0SkGXhCMxQVF1NUmUsJiIgOyPJb9WsgMeVfELYTh6s8h3s1QPrdwk2OaAcnmVynVY9vtePVZs5VCgr4uft8VBfjY9KSw09HxLJaJAu1TAUbud7Ysops3PI7wOTNQKRlqC9N4H01egbHBNhkjG42yow33jOIj0wfYQ7RmmjkTvOnpJ6P,T3Qh3bpRbOIq944ZNq5FyXob3jLb14ocxI8U3KaZB8ibHrtxVgttMFV2Ha3oTJipLUVDPK7LUkeXNohFoIGCEZK0Q3N7rJxw797My6ztLL1vwgBewa5KPDEp7saHLA5DR90Mx0jlRhkj3Rszva8WeB4ekYpqVkyYIGPt2w8PHquh8stkHjUtZ2AoU0KwOl4e0snbiL7Oq3Zsto9LdbbhE8NzN52z7BrfIUdMR8nlG1nJig9uCm58n63UvXhV2XRH,acLunh5eB8MWJGQi8Xn3eUzARzHKrpunFPFBfU0qaHdevpxzImqi4Vc6n13DTnA8OkiwpzDkbcwJcI4c18qcssUnP3SKd0LwyzU3U66trmmL4h29QBfZ4gThXtdegFREwjRk6xmJAt7FRjajwnJ98ShrLyKVlFWRW8EIyuN5X5coOc3lZSPXmxlwUI3R18rUhE6tn3CH156EDen0w5eRCH6W8UCAYk5gYTyXgwmQr89nw4Yx80iKkfZyJfkWcbkn,y6jwTXXCqSCCVkXL2kjhRw3JfuxcRqLRRbovFIiEMLps5rmvdNRbAnkG05OUadO0G10lx1nyUy61lGHyKh0uv01D7OXkuFMoBnwYNDPcWvmpVBT5c7KxlTR245p8pUQBhgM8LsIJ4pD0zNHCzdtMAHtoksm3zKxKpMh8ag2qaKpJ0GXrE2D2ZKaxfZrBVl0KPtBWlU8kEDcdoL0lsnuSzOdmmkpOPmXIFXu1lgkDQuAsFa3s6zK7t9YmI3RFUEW,w,Qo62igDvPrW42yM7R21D26fLlHnKQBPygU3iyyL45wy9QsRvdy8pv07mkEk3JnpjW17bKMJdZyTNxjfZJLs62CAZH2XSxSaDveNMT2N9o32JSIExxtJWZ9lVkY5ZQQTDyk3FYZaRBXywJd1YUIwoSkcOYREjdqsk97fcwVyeCNmkapGrE6c8AakVg6biCfeQic86RFB30e9pi1ILiNxB4CyLawHZHwEG5FztgM8R5GWbA6SObpe8tjjNT68vu6aJ,KoGVnVrayvkxlOLiGKg6HRd2VWueBTMGQPkeaasJ6RztPK3Z7eB8sfUB5SU9o3bKcOMMV3ga9AJwxLKets889w9rywcDlPxA3W5fl64T9A4YcgC3RiUaYTFeZqKGQ5bGH93DGVyKATK5o4OqPZM7ri47sTtvlpPF3rlQdqXQrid4ej5q5667GH1jPdth0NPGIPgmOhtuOfm1lToXziDrYY4AsYl3NUJNqIwW0JQUXxVwL6WnCLBx3XQi9qACeWYn,6urtvu0dJQsrEJ0agOq3Gx9sFLev8wNw59c20QiMm7zfDFyVSnGMmkupPSuI5PdBmr4GQHFsxLxKB2Snecn7CKScewwHYagmvSCyObAicyaXSGJ1kukQMGVoM2ughBMPo0zOVSkIStXyso9VwLvCXyRihouXXZmxZGfYn1f3kBsVA9MPcjeY9ExpmVAcR1p9itHzC4Tpi9GDCCvFUcJIgwADdiKchV7H5ohUCm6zTXn8inGYpiHcgAJLVpn7X4eZ,K3F5Lp7iwCWtXXXpTWP6Cth4vUVgnGkVqz8NxEubVBmP63yhrjbvqLu3KIYiyUtzDRXelVhVUHjnQS94wGkVCLoPSZxSiklG7Sfu83pAyIUb4okkAk2zUUuUu7VbC3rxGFhAymvFMlVROteWwOh3zKK4E6eT00xArpGV4pL9aBd353IxQa24p9WxJaSz5Wyt98H4BTPGs7j1ztKefv0H2JVM3OOpk4III3W44fcLZZ6nhPQqei5wKrPGhknWDSd,Q,j2axCZ2RJwuqIWAstt05anWEpJMefBdXsxdMMtrPY4lAGZtGLzl5Hb7uJRxjPwl4hsFRvDeIJpOg366l4v8FShfrj3WY7ZdwbYxiZ77N14GUiXAeMRKalDQsqUqu17LnorciM83GHKI2QfaNhug7nsjsGtolqhVBKjW3ltNLJlru1mkI2PXOtvasTJN0avdIbXNnq9qE2EAoGWRyO9jHVx5JLIQT52zvzS9ChzW5AYkhy4ND1AxIVVe5dPDfGKLh,Et3nXkMzSCVCEsAC4dKlQk7O4d67UyEf7pUASIrOG8iA7OxKat9jtn7tvGuMS2aau0mdvact4T6dbIezs2qz4IxLGB6vtT8cbavjG5QCh2tMYqmL20AdDnzJbR5DON8X4UTesl58fEcmnVsPeB8dgpYCWRJRNzSNga6tfwPYPWTm1wr9Qc6kejbFMo0c51qUSdIIcqDaRybqvMe1z09J9HUyJm6SlEHBBXl8AYJxigMBjtQyJLyaY74Rd09a5T7K,bbIsV644mrKLLdXgvWNnhOtrI1YGihtrUvc7Sl4QMkn7fqRVfSpXYFGALR9ufP2pVW47MZbmIkyBmWrZeTnzXPGPSWLwyvinP5cAnSwhdO1eMzAbzLmtW6zlip4TceYBSMYFd2SWaSONhI7hnp4QTnzjRnrYebOihUNPph57rFf66J3Y0bgQuCSMAn35fiBxRmKhrvIMyeCKc1JAbfmbW3cxvu0V27vMj6vl5LtlpeM6gCAebjnzJ9pjRCY1qvzL,G63hLiafqcYYuJyV3KfHdotz3xGNUDA7jlUoIBHB31DX2jU1HLQQj1TnRC2kAmzTeS2lepCzX5Bg5DIuviyRKTeemdsAuUkJDlQFoOTw79KHVR5V5cFF8RaAAVXDVYisFTJ7JFJsKdiQLMG1yyE7pKmn74VuF3C4JeFBgXD1PvY7c4YSOJ5WavUpsYf6j02B7Mtj1lWWnWU0l7MbW1LLwTnqEzXtyFtZrIyNT6OsdhriElPSHlFpIfVFgcoZuQH,X,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'
2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-24 14:51:08 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [1, 3, 6, 11, 14, 15]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-24 14:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3
2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:15347059-D945-4F19-8F57-C4DCE18EF619
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55014
[ThaliCore] Session.disconnect() p,eer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
,[ThaliCore] Session.deinit peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:84C638C9-E0CA-4BFD-9EC1-6CFC2163E90F
[ThaliCore] AdvertiserRelay.deinit
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E03B4550-D241-4C03-91E6-470D21F1AE48
[ThaliCore] Browser.startListening
2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-08-24 14:51:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdv,ertisingAndListening(onPort:errorHandler:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D
2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: ',d,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:51:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":fa,lse,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start, updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
2017-08-24 14:51:10 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
2017-08-24 14:51:10 - D,E,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
BUG thaliMobileNativeWrapper:, 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wit,h {"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-08-24 14:51:10, - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received ,p,eer availability changed event with {"peerAvailable":true,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"69330754-D171-4001-A667-D359FA9BCE44","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"69330754-D171-4001-A667-D359FA9BCE44","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent du,e to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
2017-08-24 14:51:14 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}]'
2017-08-24 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"15347059-D945-4F19-8F57-C4DCE18EF619","generation":0}'
2017-08-24 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:15 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B45A10F6-472E-448E-AA1A-58B61AAD9140
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "39172A14-9817-46E8-8962-207D549FB176", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:39172A14-9817-46E8-8962-207D549FB176
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:39172A14-9817-46E8-8962-207D549FB176
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
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
2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-24 14:51:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:8a3a42b3-157d-48a5-9622-afb33c412ccc error: startListeningNotActive
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"vbnkSRTju09hZF7aSssA0mqQ45qacufj","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D137A0B9-B409-466D-A2A4-5BFA2CAE9994
[ThaliCore] Browser.startListening
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uoCO6YkAhZE5n2yNOqLtJaWNjhY5R93W","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect ,r,eturned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24, 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2A0E9C37-AFA1-460A-A5AE-3771A4A4D5FA
[ThaliCore] Browser.startListening
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24, 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:20 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:e6f1782e-369f-499f-bd71-d6fc77f132ba
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:20 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3B568BCD-8A56-4957-ABDA-851A732D225F
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForA,dvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D
[ThaliCore] Browser.startListening
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discover,yActive":true,"advertisingActive":true}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69330754-D171-4001-A667-D359FA9BCE44:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"69330754-D171-4001-A667-D359FA9BCE44","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 69330754-D171-4001-A667-D359FA9BCE44 (syncValue: 9eu2MLtztJzIjs4wgPsRNnPkkFRcR6jU)'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E9508C9A-F8A7-485A-9C73-CD057AF54A08","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88D2FFB7-883E-4729-94D5-CE3958DDC824","generation":0}'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:69330754-D171-4001-A667-D359FA9BCE44:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9330754-D171-4001-A667-D359FA9BCE44", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:69330754-D171-4001-A667-D359FA9BCE44:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,9330754-D171-4001-A667-D359FA9BCE44", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9eu2MLtztJzIjs4wgPsRNnPkkFRcR6jU","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9eu2MLtztJzIjs4wgPsRNnPkkFRcR6jU', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:51:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:51:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E9508C9A-F8A7-485A-9C73-CD057AF54A08 (syncValue: tVRbPvoa6YRfAM7fvaDIERC,MKEchb4py)'
2017-08-24 14:51:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057,AF54A08:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:69330754-D171-4001-A667-D359FA9BCE44:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
[ThaliCore] Advertiser: session connected Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55026
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tVRbPvoa6YRfAM7fvaDIERCMKEchb4py","error":null,"portNumber":55026}'
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tVRbPvoa6YRfAM7fvaDIERCMKEchb4py', error: 'null', listeningPort: '55026''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) found active relay
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sk3JACT5If7nqODpFZjlVPWroanBfoMe","error":null,"portNumber":55026}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) found active relay
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pIn997DVweP96rr1SOwsgOFimvSxaTRC","error":null,"portNumber":55026}'
ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [1, 3, 6, 11, 14, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
[ThaliCore] Session.startOutputStream(with:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [1, 3, 6, 11, 14, 15, 16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withErr,or:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[Tha,liCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[Th,aliCore] VirtualSocket.deinit vsID:17 [1, 3, 6, 11, 14, 15, 16]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
,2017-08-24 14:51:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3B568BCD-8A56-4957-ABDA-851A732D225F
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55026
[ThaliCore] Session.disconnect() peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-08-24 14:51:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-08-24 14:51:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-08-24 14:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-08-24 14:51:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-24 14:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-08-24 14:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:37 - DEBUG createNativeListener: 'listening 55030'
ok 149 Should throw
,# teardown
,2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55032'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55035'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
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
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 55039'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'listening 55044'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'listening 55048'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 55052'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node -, 0 - 0 - closed'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
ok 166 incoming should survive
ok 167 mux should have no streams
,# teardown
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:41, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 55056'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 168 we should not have gotten an error
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream, <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 170 native server is nulled out
ok 171 native server should be cl,osed
ok 172 incoming has been removed
ok 173 Incoming should be done
ok 174 The mux object should be closed
ok 175 The mux stream should be closed
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
2017-08-24 14:51:41 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'listening 55060'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'incom,ing - incoming Android TCP/IP client connection <-> Mux - 1'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux ,- 2'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
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
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
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
2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'listening 55112'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'listening 55116'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 193 serversManager must not be null
ok 194 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 195 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55119'
ok 196 port must be in range
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55120'
ok 197 second start should return same port
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 55122'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-08-24 14:51:44 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 201 Passed good id but bogus port
2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing co,nnection called on peerID foo with port 900'
ok 202 Passed right context
ok 203 Right server
ok 204 No error should be set
ok 205 Retry should be false
ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 55124
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method disc,overyAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FD09023D-741D-467A-939B-EE587D2D88D6
2017-08-24 1,4:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C
[Tha,l,iCore] Browser.startListening
2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E9508C9A-F8A7-485A-9C73-CD057AF54A08","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E9508C9A-F8A7-485A-9C73-CD057AF54A08 (syncValue: higu0LOjuyqWwUHAE5PDkH685x6VrgXW)'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3AA7804-57E2-44E7-AC1A-8164EB411284","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88D2FFB7-883E-4729-94D5-CE3958DDC824","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3CB5059A-D11F-4536-8716-32BED6C97CD6","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB
[ThaliCore] Advertiser: session connected Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E9,508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"higu0LOjuyqWwUHAE5PDkH685x6VrgXW","error":"Peer is unavailable","portNumber":null}'
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'higu0LOjuyqWwUHAE5PDkH685x6VrgXW', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:51:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3AA7804-57E2-44E7-AC1A-8164EB411284 (syncValue: GpxkAQrVCvy6CmwmFk8Nh6r,VjIta1xux)'
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B3AA7804-57E2-44E7-AC1A-8164E,B411284:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 ,14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55132
2017-08-24 14:51:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GpxkAQrVCvy6CmwmFk8Nh6rVjIta1xux",,"error":null,"portNumber":55132}'
2017-08-24 14:51:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GpxkAQrVCvy6CmwmFk8Nh6rVjIta1xux', error: 'null', listeningPort: '55132''
,ok 210 should be equal
2017-08-24 14:51:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 88D2FFB7-883E-4729-94D5-CE3958DDC824 (syncValue: zbEAFlrjLcKa1JjeXv5QGTbL3IYx70pA)'
2017-08-24 14:51:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConn,ected:) Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:88,D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,8D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zbEAFlrjLcKa1JjeXv5QGTbL3IYx70pA","error":"Peer is unavailable","portNumber":null}'
2017-08-24 14:51:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zbEAFlrjLcKa1JjeXv5QGTbL3IYx70pA', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:51:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:51:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3CB5059A-D11F-4536-8716-32BED6C97CD6 (syncValue: PJ3RYpHTpb8fwbQJuz8pCjB,EnwxZfvRS)'
2017-08-24 14:51:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3CB5059A-D11F-4536-8716-32BED,6C97CD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559
[ThaliCore] Advertiser: session connected Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55138
,2017-08-24 14:51:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PJ3RYpHTpb8fwbQJuz8pCjBEnwxZfvRS","error":null,"portNumber":55138}'
,2017-08-24 14:51:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PJ3RYpHTpb8fwbQJuz8pCjBEnwxZfvRS', error: 'null', listeningPort: '55138''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559
,[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:52:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FD09023D-741D-467A-939B-E,E587D2D88D6
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:B3AA7804-57E2-44E7-AC1A-8164EB411284
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55132
[ThaliCore] Session.disconnect() peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:3CB5059A-D11F-4536-8716-32BED6C97CD6
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55138
,[ThaliCore] Session.disconnect() peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A9F29061-D330-4331-BAAD-D8815E7AF559
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Session.deinit peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserRelay.deinit
2017-08-24 14:52:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:A9F29061-D330-4331-BAAD-D8815E7AF559
,# Multiple local http requests
,listening on 55140
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
2017-08-24 14:52:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B3AA7804-57E2-44E7-AC1A-8164EB411284","generation":0}'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B3AA7804-57E2-44E7-AC1A-8164EB411284, (syncValue: o2rcagavkrM1yi8xEzJ2O7rtmOIkY4FI)'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB4,11284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6",, generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable,":true,"peerIdentifier":"3CB5059A-D11F-4536-8716-32BED6C97CD6","generation":0}'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:52:04 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:06 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
2017-08-24 14:52:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:52:06 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:52:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B3,AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:52:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"o2rcagavkrM1yi8xEzJ2O7rtmOIkY4FI","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:52:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'o2rcagavkrM1yi8xEzJ2O7rtmOIkY4FI', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:52:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:52:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB5CF9B6-91FF-458D-826A-E357F5135E10 (syncValue: 3gklJJeSzYuLEUiJXHCTz1YhhtZROSNh)'
2017-08-24 14:52:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F,5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:52:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55154
,2017-08-24 14:52:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3gklJJeSzYuLEUiJXHCTz1YhhtZROSNh","error":null,"portNumber":55154}'
,2017-08-24 14:52:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3gklJJeSzYuLEUiJXHCTz1YhhtZROSNh', error: 'null', listeningPort: '55154''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-08-24 14:52:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01C1451B-604C-4664-8679-5A413158C4CD (syncValue: xH31aNFQfaCLiHxMlrwHToHz89R0Pfte)'
2017-08-24 14:52:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55160
2017-08-24 14:52:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xH31aNFQfaCLiHxMlrwHToHz89R0Pfte",,"error":null,"portNumber":55160}'
2017-08-24 14:52:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xH31aNFQfaCLiHxMlrwHToHz89R0Pfte', error: 'null', listeningPort: '55160''
,ok 220 should be equal
ok 221 should be equal
ok 222 should be equal
# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
[ThaliCore] Advertiser: session connected Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE095084-4180-45BE-B90B-84AF67A11861
[ThaliCore] Advertiser: session connected Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AE095084-4180-45BE-B90B-84AF67A11861 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE095084-4180-45BE-B90B-84AF67A11861
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE095084-4180-45BE-B90B-84AF67A11861 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
,[ThaliCore] Session.session(_:peer:didChange:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:52:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:FDA6AEB5-34C5-4064-AB9D-5,71BC6BA42B4
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:BB5CF9B6-91FF-458D-826A-E357F5135E10
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55154
[ThaliCore] Session.disconnect() peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TC,PListener.deinit
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:01C1451B-604C-4664-8679-5A413158C4CD
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55160
,[ThaliCore] Session.disconnect() peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AE095084-4180-45BE-B90B-84AF67A11861
,[ThaliCore] Session.deinit peer:AE095084-4180-45BE-B90B-84AF67A11861
[ThaliCore] AdvertiserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'listening 55164'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 229 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliM,obile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 55165'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:176AFE9D-B7D9-453D-9059-1B0F3560C6D9
[ThaliCore] Browser.startListening
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
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
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 55166'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD28F930-A268-4915-8585-6CE52E015B08", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:FD28F930-A268-4915-8585-6CE52E015B08
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:5,2:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD28F930-A268-4915-8585-6CE52E015B08", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:FD28F930-A268-4915-8585-6CE52E015B08
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-0,8-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD28F930-A268-4915-8585-6CE52E015B08
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD28F930-A268-4915-8585-6CE52E015B08
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
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
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'listening 55169'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,U,pdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-08-24 14:52:25 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 55170'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B96155BA-A8ED-491E-9E35-2785302A16F8
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB6F38AC-1A11-4B3B-B8ED-58BF87F7F559", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BB6F38AC-1A11-4B3B-B8ED-58BF87F7F559
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:BB6F38AC-1A11-4B3B-B8ED-58BF87F7F559
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,# TCP Servers Manager should be null when we call start on iOS
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 55173'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DDE47B88-B78E-453F-A307-60CAB1FA26F1
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BCDE0B72-82BD-4088-B394-D1DFA0CDDF24", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BCDE0B72-82BD-4088-B394-D1DFA0CDDF24
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:25 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BCDE0B72-82BD-4088-B394-D1DFA0CDDF24
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:26 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingA,ctive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSta,teUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'listening 55175'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3A880D00-2F94-4611-BD54-40F1D6CF225C
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7BC96137-2685-4B9B-8C0F-A95BDF2CC921", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7BC96137-2685-4B9B-8C0F-A95BDF2CC921
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7BC96137-2685-4B9B-8C0F-A95BDF2CC921
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-08-24 14:52:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-08-24 14:52:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
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
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-08-24 14:52:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-08-24 14:52:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-08-24 14:52:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55178'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E4BC5BBA-CC2A-4421-ABEF-5CAB1B0C3C89
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,C,P: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkT,ype":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisemen,ts()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
ok 271 advertisingActive matches
2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55179'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C1DBA0A-4F02-4464-9296-FD179BF999AC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C1DBA0A-4F02-4464-9296-FD179BF999AC
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0C1DBA0A-4F02-4464-9296-FD179BF999AC
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"adver,tisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 55181'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopListenin,gForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'listening 55182'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:112803B4-8403-4805-995E-69B73FBDF9A1
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "805C78A1-490F-40C7-87AA-67FE1AF9D933", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,805C78A1-490F-40C7-87AA-67FE1AF9D933
2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:34 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:805C78A1-490F-40C7-87AA-67FE1AF9D933
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
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
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'listening 55184'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06C6EA6F-EC7B-4A15-84AC-996513E5248B
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3304B754-50D,5-4361-A23C-5327C08FA6E5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3304B754-50D5-4361-A23C-5327C08FA6E5
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01C1451B-604C-4664-8679-5A413158C4CD (syncValue: YiHDlhuAbVYmLFT2sBXcSHb4EMYEeQN1)'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
2017-08-24 14:52:36 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}]'
2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:52:37 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,1C1451B-604C-4664-8679-5A413158C4CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:52:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YiHDlhuAbVYmLFT2sBXcSHb4EMYEeQN1","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YiHDlhuAbVYmLFT2sBXcSHb4EMYEeQN1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:52:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BB5CF9B6-91FF-458D-826A-E357F5135E10 (syncValue: TBRy8y41TmrRuuqP1oZI43q,8vTnzqYz5)'
2017-08-24 14:52:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691
[ThaliCore] Advertiser: session connected Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691
,[ThaliCore] Session.session(_:peer:didChange:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691
[ThaliCore] Session.startOutputStream(with:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [1, 3, 6, 11, 14, 15, 16, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,B5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BB5CF9B6-91FF-458D-826A-E357F5135E10 error: max retries exceeded
2017-08-24 14:52:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TBRy8y41TmrRuuqP1oZI43q8vTnzqYz5","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:52:49 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TBRy8y41TmrRuuqP1oZI43q8vTnzqYz5', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:52:49 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:52:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A21C39C3-4A3F-46BA-B16E-602CFA61B286 (syncValue: 50z5H79,YfKRsuFFuM4EH3rFuzfqJzYHo)'
2017-08-24 14:52:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A21C39C3-4A3F,-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55199
2017-08-24 14:52:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"50z5H79YfKRsuFFuM4EH3rFuzfqJzYHo",,"error":null,"portNumber":55199}'
2017-08-24 14:52:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '50z5H79YfKRsuFFuM4EH3rFuzfqJzYHo', error: 'null', listeningPort: '55199''
,2017-08-24 14:52:51 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [1, 3, 6, 11, 14, 15, 16, 18, 19]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:52:52 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:52:52 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3304B754-50D5-4361-A23C-5327C08FA6E5
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-08-24 14:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescrip,tion=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed vir,tual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [1, 3, 6, 11, 14, 15, 16, 19]
,[ThaliCore] BrowserManager.disconnect peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55199
[ThaliCore] VirtualSocket.closeStr,eams() vsID:19
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] Session.disconnect() peer:A21C39C3-4A3F-46BA-,B16E-602CFA61B286:0
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:19 [1, 3, 6, 11, 14, 15, 16]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:52:52 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:528BC149-A7D8-41DF-9FC4-97A61747F691 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:528BC149-A7D8-41DF-9FC4-97A61747F691
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:528BC149-A7D8-41DF-9FC4-97A61747F691
,# can still do HTTP requests between peers with coordinator
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 55201'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,93922256-C7C8-4DB9-B61E-DC3CCB8151D5
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
2017-08-24 14:52:53 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
2017-08-24 14:52:53 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A21C39C3-4A3F-46BA-B16E-602CFA61B286 (syncValue: PItntLoy1sdiGPP,krYLwaNayExlyeDSd)'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creat,ing a new relay
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] ,Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore,] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{,"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BB5CF9B6-91FF-458D,-826A-E357F5135E10","generation":0}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","generation":0}]'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","generation":0}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
2017-08-24 14:52:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}]'
2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,1C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,1C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}]'
2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","generation":0}'
,2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:53:02 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BB5CF9B6-91FF-458D-826A-E357F5135E10","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,1C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A21C39C3,-4A3F-46BA-B16E-602CFA61B286 error: max retries exceeded
2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PItntLoy1sdiGPPkrYLwaNayExlyeDSd","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PItntLoy1sdiGPPkrYLwaNayExlyeDSd', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:53:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 283DB3E7-9F5D-4C43-8B90-8282EA781BA5 (syncValue: byVPhFm,x7B7VamkFZXxXFI5aKwusXIgt)'
2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:283DB3E7-9F5D,-4C43-8B90-8282EA781BA5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
,2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-24 14:53:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55214
2017-08-24 14:53:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"byVPhFmx7B7VamkFZXxXFI5aKwusXIgt",,"error":null,"portNumber":55214}'
2017-08-24 14:53:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'byVPhFmx7B7VamkFZXxXFI5aKwusXIgt', error: 'null', listeningPort: '55214''
,2017-08-24 14:53:07 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [1, 3, 6, 11, 14, 15, 16, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsH,andler
,2017-08-24 14:53:08 - DEBUG testUtils: 'Got response data'
2017-08-24 14:53:08 - DEBUG testUtils: 'Got end'
ok 282 response body should match testData
ok 283 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:93922256-C7C8-4DB9-B61E-DC3CCB8151D5
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-24 14:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:08 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.d,i,sconnect peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55214
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] T,CPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Bro,wserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] Session.disconnect() peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
[ThaliCo,re] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:20 [1, 3, 6, 11, 14, 15, 16]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer,:,283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-08-24 14:53:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'listening 55216'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA49207D-F921-4FBC-BCED-B53A12F7E64B
[ThaliCore] Browser.st,artListening
2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:11 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9F56726-E546-46CD-B1A6-ABCA2203A872", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,D9F56726-E546-46CD-B1A6-ABCA2203A872
2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:11 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}]'
2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF (syncValue: pMVT7qVykN4oFpzXASwyqjEzA4xsNJ2N)'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
2017-08-24 14:53:12 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}]'
2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:53:12 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","generation":0}]'
2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","generation":0}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:53:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9F56726-E546-46CD-B1A6-ABCA2203A872:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9F56726-E546-46CD-B1A6-ABCA2203A872", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95,B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:95B1BAF0,-32BB-4CB0-ACFC-A6F2EAD6A7AF error: max retries exceeded
2017-08-24 14:53:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pMVT7qVykN4oFpzXASwyqjEzA4xsNJ2N","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pMVT7qVykN4oFpzXASwyqjEzA4xsNJ2N', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:53:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78AAC586-1402-4A0D-8C29-BFD492D2F632 (syncValue: osucMci,s9bjFU9DG7pzpSQaJIHGY45b2)'
2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78AAC586-1402,-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:55230
2017-08-24 14:53:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"osucMcis9bjFU9DG7pzpSQaJIHGY45b2","error":null,"portNumber":55230}'
2017-08-24 14:53:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'osucMcis9bjFU9DG7pzpSQaJIHGY45b2', error: 'null', listeningPort: '55230''
,2017-08-24 14:53:24 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) pee,r:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [1, 3, 6, 11, 14, 15, 16, 21]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsH,andler
,2017-08-24 14:53:25 - DEBUG testUtils: 'Got response data'
2017-08-24 14:53:25 - DEBUG testUtils: 'Got end'
ok 287 response body should match testData
ok 288 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D9F56726-E546-46CD-B1A6-ABCA2203A872
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-08-24 14:53:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:26 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:78AAC586-1402-4A0D-8C29-BFD492D2F632
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:55230
[ThaliCore] VirtualSocket.closeStr,eams() vsID:21
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] Session.disconnect() peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:21 [1, 3, 6, 11, 14, 15, 16]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 290 FIX ME, PLEASE!!!
,# teardown
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:26 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-08-24 14:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 292 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-08-24 14:53:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 293 must be stopped
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
,ok 294 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 295 specific error should be returned
,# teardown
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"84CB1FE5-6959-4935-8218-C20EE2F08B52","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-24, 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"283DB3E7-9F5D-4C43-8B90-8282EA781BA5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-24 14:53:28 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-24 14:53:28 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-24 14:53:28 - DEBUG thaliMobile,:, 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"089F34F7-2665-42AE-B516-FAD462A067E4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 296 error should be null
ok 297 error should be null
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
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 55232'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 303 error should be null
ok 304 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
,ok 305 error should be null
ok 306 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 307 error should be null
ok 308 error should be null
,# setup
,ok 309 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 55233'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AFFCC61F-07E6-4F91-880F-15F2628E1D77
[ThaliCore] Browser.st,artListening
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 310 error should be null
ok 311 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
ok 313 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Received state ({"d,iscoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:53:29 - DEBUG makeIntoCloseA,llServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 55234'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5980466-B45D-4C09-AA6A-E22312FFD42F", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:E5980466-B45D-4C09-AA6A-E22312FFD42F
2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E5980466-B45D-4C09-AA6A-E22312FFD42F", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:E5980466-B45D-4C09-AA6A-E22312FFD42F
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
,ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E5980466-B45D-4C09-AA6A-E22312FFD42F
,[ThaliCore] Advertiser.stopAdvertising() peerID:E5980466-B45D-4C09-AA6A-E22312FFD42F
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
,ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 55237'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 326 error should be null
,ok 327 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-08-24 14:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 328 error should be null
ok 329 error should be null
,# setup
,ok 330 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-24 14:53:31 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 331 This should not cause wifi to fail
ok 332 native router should be bad
,# teardown
,ok 333 error should be null
ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'listening 55238'
ok 336 first call should succeed
ok 337 first call should succeed
ok 338 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:53:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-08-24 14:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 342 error should be null
,ok 343 error should be null
,# setup
,ok 344 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-08-24 14:53:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 345 error should be null
ok 346 error should be null
,# setup
,ok 347 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-08-24 14:53:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b322f9cc-c8bb-4a3e-ba05-a0f0d43be576","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 348 should be calle,d once
ok 349 should not have been called more than once
,# teardown
,2017-08-24 14:53:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b322f9cc-c8bb-4a3e-ba05-a0f0d43be576","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 350 error should be null
ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# can get the network status
,ok 353 network status should have certain non-empty properties
,# teardown
,ok 354 error should be null
ok 355 error should be null
,# setup
,ok 356 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,2017-08-24 14:53:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-08-24 14:53:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4,675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-08-24 14:58:33 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-08-24 14:58:33 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-08-24 14:,58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-08-24 14:58:33 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-08-24 ,1,4:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - Calling stopListeningForAdvertisements without calling start is NOT an error'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
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
    at SubError@/private/var/containers/Bundle/Application/9D,40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_m,odules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-08-24 14:58:33 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-08-24 14:58:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4,675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4,675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4,675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-467,5-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9D40C6FC-4990-4675-8921-AC9C70674075/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
