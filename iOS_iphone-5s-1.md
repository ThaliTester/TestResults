#### Test 145917619d0aee2c_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/F4424957-E204-421E-A332-3D26EBE77074/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F4424957-E204-421E-A332-3D26EBE77074/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50589"
,(lldb)     command script import "/tmp/F4424957-E204-421E-A332-3D26EBE77074/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,JXcore Cordova bridge is ready
,JXcore engine is started
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:47:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "72CF1058-F11F-4F7F-8FCC-A6A6485BFDA7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:72CF1058-F11F-4F7F-8FCC-A6A6485BFDA7
Optional(true)
Optional(false)
App,ContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:52BBE9E4-EC37-4A9F-A500-3A5743021953
[ThaliCore] Browser.st,artListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC8A8F21-85A2-4644-8879-92BCFCC75A86
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndList,ening(onPort:errorHandler:) Peer(uuid: "C0FC574E-5B75-4BF9-B4F5-96E32B353FDC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C0FC574E-5B75-4BF9-B4F5-96E32B353FDC
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0FC574E-5B75-4BF9-B4F5-96E32B353FDC:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0FC574E-5B75-4BF9-B4F5-96E32B353FDC", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-11 11:47:02 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.984998047351837
,2017-10-11 11:47:02 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-10-11 11:47:02 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C0FC574E-5B75-4BF9-B4F5-96E32B353FDC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C0FC574E-5B75-4BF9-B4F5-96E32B353FDC", generation: 0)
,2017-10-11 11:47:06 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-11 11:47:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-11 11:47:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-11 11:47:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-11 11:47:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-11 11:47:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-11 11:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-11 11:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-11 11:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-11 11:47:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-11 11:47:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-11 11:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4,B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:50 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-10-11 11:47:50 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-10-11 11:47:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-10-11 11:47:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-10-11 11:48:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-10-11 11:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-10-11 11:48:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-10-11 11:48:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-10-11 11:48:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-10-11 11:48:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-10-11 11:48:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-10-11 11:48:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-10-11 11:48:27 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-10-11 11:48:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-10-11 11:48:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED20E5AE-4EDE-453C-9EB1-7A9328B454D0
,[ThaliCore] Browser.startListening
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A936DCB9-A4AA-4884-B0FE-973863D6A49D
[ThaliCore] Browser.startListening
2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-10-11 11:48:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.startListeningForAdvertisements
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-11 11:48:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE9476AB-5432-4B0A-B5D6-C05018537525", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DE9476AB-5432-4B0A-B5D6-C05018537525
2017-10-11 1,1:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DE9476AB-5432-4B0A-B5D6-C05018537525
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E0A60A22-F962-456A-9B3B-FC93AF92293C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E0A60A22-F962-456A-9B3B-FC93AF92293C
2017-10-11 1,1:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E0A60A22-F962-456A-9B3B-FC93AF92293C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:E0A60A22-F962-456A-9B3B-FC93AF92293C
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E0A60A22-F962-456A-9B3B-FC93AF92293C
,[ThaliCore] Advertiser.stopAdvertising() peerID:E0A60A22-F962-456A-9B3B-FC93AF92293C
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:04 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:49:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:05 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DA861A75-8005-4738-B121-D6D2FA3CB68E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DA861A75-8005-4738-B121-D6D2FA3CB68E
2017-10-11 1,1:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F03805B3-1118-42AC-9ADC-E86CEF114574
[Thali,Core] Browser.startListening
2017-10-11 11:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-11 11:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:06 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75F23093-476E-4543-93E5-6091E21DEA89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75F23093-476E-4543-93E5-6091E21DEA89", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA861A75-8005-4738-B121-D6D2FA3CB68E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA861A75-8005-4738-B121-D6D2FA3CB68E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:939B08FA-41FE-498B-B51E-E9333112CF98:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "939B08FA-41FE-498B-B51E-E9333112CF98", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DA861A75-8005-4738-B121-D6D2FA3CB68E
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B684C49D-590F-4A16-9CBA-CC5ED8CDA416
2017-10-11 1,1:49:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D02F1F86-EBDA-4870-9326-FAE8B7DE5FCA
[Thal,i,Core] Browser.startListening
2017-10-11 11:49:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-11 11:49:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-10-11 11:49:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,2017-10-11 11:49:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8","generation":0}'
,2017-10-11 11:49:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8 (syncValue: jPhE7sbmK0Hdmu5TmpoXDPR2FUhAMO37)'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB
[ThaliCore] Advertiser: session connected Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
2017-10-11 11:49:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multi,Connect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnec,ted:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketT,imeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
2017-10-11 11:49:31 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B12CCD5C-504E-4635-8DB3-BE9514508331","generation":0}'
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50208
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jPhE7sbmK0Hdmu5TmpoXDPR2FUhAMO37","error":null,"portNumber":50208}'
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jPhE7sbmK0Hdmu5TmpoXDPR2FUhAMO37', error: 'null', listeningPort: '50208''
,2017-10-11 11:49:31 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE
[ThaliCore] Advertiser: session connected Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE
,[ThaliCore] Session.session(_:peer:didChange:) peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:04B709C6-6D9C-4B90-BFB4-9A384D6EE6AB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Session.deinit peer:8D36BD79-DEDD-4C38-9337-2381DA31C6BE
,2017-10-11 11:49:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:49:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:49:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:B684C49D-590F-4A16-9CBA-CC5ED8CDA416
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:49:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50208
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-10-11 11:49:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jPhE7sbmK0Hdmu5TmpoXDPR2FUhAMO37","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9F70A025-7FB6-44F8-842A-A7168F9BD13B
2017-10-11 1,1:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42E2D5F6-4D5F-4F48-90AF-B83527681F42
[Thal,i,Core] Browser.startListening
2017-10-11 11:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:49:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B12CCD5C-504E-4635-8DB3-BE95145083,31","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B12CCD5C-504E-4635-8DB3-BE9514508331 (syncValue: U5G9lyrHV2VRgvPhJRJ5eHY7HLC1Jctq)'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8","generation":0}'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"693ACD69-7D6C-45C9-A0EE-2855E12F155B","generation":0}'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4CF963-A10F-4CDD-9A86-7AE2A53CC641","generation":0}'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-10-11 11:49:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U5G9lyrHV2VRgvPhJRJ5eHY7HLC1Jctq","error":"Peer is unavailable","portNumber":null}'
,2017-10-11 11:49:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U5G9lyrHV2VRgvPhJRJ5eHY7HLC1Jctq', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:49:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-10-11 11:49:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8 (syncValue: RKiDS0Dhu6IPC1uRvr9900wrVPeZNDHD)'
,2017-10-11 11:49:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1,FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1,FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1,FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1,FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:C1FE7B04,-FEF8-45A3-BC71-B2E4C17DCED8 error: max retries exceeded
2017-10-11 11:49:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RKiDS0Dhu6IPC1uRvr9900wrVPeZNDHD","error":"Connection could not be established","portNumber":null}'
2017-1,0-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RKiDS0Dhu6IPC1uRvr9900wrVPeZNDHD', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-11 11:49:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 693ACD69-7D6C-45C9-A0EE-2855E12F155B (syncValue: YHfpLmW,j9fllKZvvTyKajWRb1LUJtXXm)'
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:693ACD69-7D6C,-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:40D38DB4-6925-4DA1-9246-840925B80A75
[ThaliCore] Advertiser: session connected Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:40D38DB4-6925-4DA1-9246-840925B80A75 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
[ThaliCore] Advertiser: session connected Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50215
2017-10-11 11:49:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YHfpLmWj9fllKZvvTyKajWRb1LUJtXXm",,"error":null,"portNumber":50215}'
,2017-10-11 11:49:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YHfpLmWj9fllKZvvTyKajWRb1LUJtXXm', error: 'null', listeningPort: '50215''
,Connecting to the localhost:50215
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
Connected to the localhost:50215
,2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-10-11 11:49:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:1
,[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:1
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:1
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:40D38DB4-6925-4DA1-9246-840925B80A75
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
,[ThaliCore] Session.session(_:peer:didChange:) peer:40D38DB4-6925-4DA1-9246-840925B80A75 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:40D38DB4-6925-4DA1-9246-840925B80A75
,[ThaliCore] Session.startOutputStream(with:) peer:40D38DB4-6925-4DA1-9246-840925B80A75
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
[ThaliCore] Session.startOutputStream(with:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [1, 2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 20 vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:3
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:3
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:20 count:1 vsID:2
[ThaliCore] VirtualSocket.writePendingData() to write:20 written:20 count:0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [1, 3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
,[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [1]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-11 11:49:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
2017-10-11 11:49,:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networ,kType":null}})'
,2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9F70A025-7FB6-44F8-842A-A7168F9BD13B
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50215
[ThaliCore] Session.disconnect() p,eer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E7FD0F07-6302-4489-A30F-9733F1345F7A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:40D38DB4-6925-4DA1-9246-840925B80A75 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,# setup
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YHfpLmWj9fllKZvvTyKajWRb1LUJtXXm","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:E7FD0F07-6302-4489-A30F-9733F1345F7A
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B8643CF2-FE60-44D6-A9DE-05A1F25612CE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B8643CF2-FE60-44D6-A9DE-05A1F25612CE
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:310847F9-0DDB-407E-BB04-355C1C3E5A99
[ThaliCore] Browser.startListening
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-11 11:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BF4CF963-A10F-4CDD-9A86-7AE2A53CC641","generation":0}'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BF4CF963-A10F-4CDD-9A86-7AE2A53CC641 (syncValue: uiXRNw2GQY5gQXBmuMTzl7ZSwfaVvK7O)'
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"693ACD69-7D6C-45C9-A0EE-2855E12F155B","generation":0}'
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA","generation":0}'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3EAD01-0759-464B-B522-6E5D1376B433","generation":0}'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8643CF2-FE60-44D6-A9DE-05A1F25612CE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8643CF2-FE60-44D6-A9DE-05A1F25612CE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,F4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BF,4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BF4CF963,-A10F-4CDD-9A86-7AE2A53CC641 error: max retries exceeded
2017-10-11 11:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uiXRNw2GQY5gQXBmuMTzl7ZSwfaVvK7O","error":"Connection could not be established","portNumber":null}'
2017-1,0-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uiXRNw2GQY5gQXBmuMTzl7ZSwfaVvK7O', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-11 11:50:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 693ACD69-7D6C-45C9-A0EE-2855E12F155B (syncValue: BZjH97F,cueYVAwiet642X3gWALnJAiGY)'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:693ACD69-7D6C,-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,3ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,93ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,3ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,93ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,3ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,93ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-11 11:50:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BZjH97FcueYVAwiet642X3gWALnJAiGY","error":"Peer is unavailable",,"portNumber":null}'
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BZjH97FcueYVAwiet642X3gWALnJAiGY', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:50:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA (syncValue: 9hQGBPSuhg9zj8EPVtJxxiK,6qmZOP90n)'
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50239
2017-10-11 11:50:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9hQGBPSuhg9zj8EPVtJxxiK6qmZOP90n",,"error":null,"portNumber":50239}'
2017-10-11 11:50:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '9hQGBPSuhg9zj8EPVtJxxiK6qmZOP90n', error: 'null', listeningPort: '50239''
,Connecting to the localhost:50239
,Connecting to the localhost:50239
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
Connecting to the local,host:50239
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] TCPListener.socket(_:didAcceptNewS,ocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,Connected to the localhost:50239
Connected to the localhost:50239
,Connected to the localhost:50239
,ok 91 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:4
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6,E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:6
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
,[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1054 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [5]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 96 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-10-11 11:51:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:51:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B8643CF2-FE60-44D6-A9DE-05A1F25612CE
2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11,:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50239
[ThaliCore] Session.disconnect() p,eer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:51:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-10-11 11:52:18 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-10,-,11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGE,R result: passed - enqueue and run in order'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enq,ueueAtTop'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-10-11 11:52:18 - INFO CoordinatedC,lient: '***TEST_LOGGER result: passed - another'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can shift data securely, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest,.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
,    at timeoutTimeout@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-10-11 11:52:18 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-10-11 11:52:27 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-10-11 11:52:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B,9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/,containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B,9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/,containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B,9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/,containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-10-11 11:54:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B,9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/,containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-10-11 11:55:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B,9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node,_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/,containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modul,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F,-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-10-11 11:56:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4,B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9,F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/DD70AF5C-D6F2-4B9F-AA49-16EE141ED71B/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,2017-10-11 11:57:25 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
,2017-10-11 11:57:25 - DEBUG CoordinatedClient: 'test client failed'
,2017-10-11 11:57:25 - ERROR CoordinatedClient: 'reconnect_error error: 'timeout', description: 'undefined', stack: 'undefined''
,2017-10-11 11:57:25 - DEBUG CoordinatedClient: 'test client failed'
,2017-10-11 11:57:25 - DEBUG CoordinatedClient: '20000'
,2017-10-11 11:57:25 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
,2017-10-11 11:57:25 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
