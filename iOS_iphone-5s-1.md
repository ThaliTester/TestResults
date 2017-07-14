#### Test 1133518510faaea9_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/2D7433BE-3063-4C34-B44C-223BEF646F69/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/2D7433BE-3063-4C34-B44C-223BEF646F69/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518510faaea9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59515"
,(lldb)     command script import "/tmp/2D7433BE-3063-4C34-B44C-223BEF646F69/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:27:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4957A54C-550C-4720-9675-6C85DC4D4956", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4957A54C-550C-4720-9675-6C85DC4D4956
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A705D95E-B330-4C59-B4E8-65E5D5213B32
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C05496EF-,4528-42A2-B460-99F3B023D4F2
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A099C4E3-5D8E-4226-8ED4-3EABD868EA86", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A099C4E3-5D8E-4226-8ED4-3EABD868EA86
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A099C4E3-5D8E-4226-8ED4-3EABD868EA86:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A099C4E3-5D8E-4226-8ED4-3EABD868EA86", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-14 11:27:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  13
,Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.791860103607178
,2017-07-14 11:27:31 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-14 11:27:31 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A099C4E3-5D8E-4226-8ED4-3EABD868EA86:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A099C4E3-5D8E-4226-8ED4-3EABD868EA86", generation: 0)
,2017-07-14 11:27:34 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-14 11:27:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-14 11:27:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-14 11:27:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-14 11:27:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-14 11:27:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-14 11:27:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-14 11:27:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-14 11:27:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:27:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:27:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:28:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:28:16 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-14 11:28:16 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-14 11:28:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-14 11:28:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-14 11:28:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-14 11:28:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-14 11:28:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-14 11:28:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-14 11:28:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 11 should be equal
,ok 12 should be equal
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
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-14 11:28:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-14 11:28:51 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-14 11:28:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D7D7FCF4-672E-4285-8863-C7321F3CD65C
[ThaliCore] Browser.startListening
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:95E0B6DB-0DB1-4AE2-B205-9F39C0DDE20E
[ThaliCore] Browser.startListening
2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C4A2BB0-CB05-4A84-8E7D-05F86697969F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6C4A2BB0-CB05-4A84-8E7D-05F86697969F
2017-07-14 1,1:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertising,S,tateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2192D994-259B-4D7B-922E-0C07912F4347", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2192D994-259B-4D7B-922E-0C07912F4347
2017-07-14 1,1:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2192D994-259B-4D7B-922E-0C07912F4347", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:2192D994-259B-4D7B-922E-0C07912F4347
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:28:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:28:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:28:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4
2017-07-14 1,1:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:367C6C28-2118-4DF3-AE12-FBFDE32F55AC
[Thali,Core] Browser.startListening
2017-07-14 11:29:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:29:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:00 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CFDB3600-5C66-4F43-8D70-1D53F58FC5A4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CFDB3600-5C66-4F43-8D70-1D53F58FC5A4", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 93 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:7B90ADCE-E704-407C-9CE8-7BB8430AD315
2017-07-14 1,1:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E45E358F-33A0-407C-85A7-5D1F4057AA9A
,[ThaliCore] Browser.startListening
2017-07-14 11:29:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:29:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"80DF8A94-63B2-4251-838F-96CD4A4899AA","generation":0}'
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 80DF8A94-63B2-4251-838F-96CD4A4899AA (syncValue: ZC1tqkfC276XlxNwE2AChMkvrNvPzFKc)'
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"28E6A239-B69C-4274-A411-DD9E8D1E94BB","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:28E6A239-B69C-4274-A411-DD9E8D1E94BB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "28E6A239-B69C-4274-A411-DD9E8D1E94BB", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0)
[ThaliCore] Session.disconnect() peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] Browser.br,owser(_:foundPeer:withDiscoveryInfo:) found peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUt,ils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:7B90ADCE-E704-407C-9CE8-7BB8430AD315:0
2017-07-14 11:29:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:80DF8A94-63B2-4251-838F-96CD4A4899AA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "80DF8A94-63B2-4251-838F-96CD4A4899AA", genera,tion: 0)
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZC1tqkfC276XlxNwE2AChMkvrNvPzFKc","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'ZC1tqkfC276XlxNwE2AChMkvrNvPzFKc', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"80DF8A94-63B2-4251-838F-96CD4A4899AA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"80DF8A94-63B2-4251-838F-96CD4A4899A,A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F6B5DBB-1C61-4809-A491-89BBC874CDFD (syncValue: E4t0msEx9JauYQofjqt1fllL6JwKadwR)'
,2017-07-14 11:29:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459
[ThaliCore] Advertiser: session connected Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD3A8590-4641-4F73-9C1E-9811AE25043E
[ThaliCore] Advertiser: session connected Peer(uuid: "7B90ADCE-E704-407C-9CE8-7,BB8430AD315", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459 state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:AD3A8590-4641-4F73-9C1E-9811AE25043E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49952
,2017-07-14 11:29:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"E4t0msEx9JauYQofjqt1fllL6JwKadwR","error":null,"portNumber":49952}'
,2017-07-14 11:29:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'E4t0msEx9JauYQofjqt1fllL6JwKadwR', error: 'null', listeningPort: '49952''
,2017-07-14 11:29:11 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD3A8590-4641-4F73-9C1E-9811AE25043E
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD3A8590-4641-4F73-9C1E-9811AE25043E state: connecting -> connected
,2017-07-14 11:29:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49952
[ThaliCore] Session.disconnect() peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:0AD29B33-51CE-4502-8298-1BF0AFC9D459 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "7B90ADCE-E704-407C-9CE8-7BB8430AD315", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] Session.session(_:peer:didChange:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AD3A8590-4641-4F73-9C1E-9811AE25043E
[ThaliCore] Session.deinit peer:AD3A859,0-4641-4F73-9C1E-9811AE25043E
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:14DF6D47-0838-4CD4-8191-E53A4CB3D543
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:02328334-95F8-4265-8DF2-5DAB01C83275
,[ThaliCore] Browser.startListening
,2017-07-14 11:29:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:29:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
2017-07-14 11:29:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","generation":0}'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD, (syncValue: EF17vDgq01yOH2ThshEvckTcobee3ksG)'
2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F6B5DBB-1C61-4809,-A491-89BBC874CDFD:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
2017-07-14 11:29:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:630D69F0-7B0D-4353-B1D3-72041CE8B2A3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "630D69F0-7B0D-4353-B1D3-72041CE8B2A3", generation: 0)
,2017-07-14 11:29:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"630D69F0-7B0D-4353-B1D3-72041CE8B2A3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:14DF6D47-0838-4CD4-8191-E53A4CB3D543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "14DF6D47-0838-4CD4-8191-E53A4CB3D543", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", genera,tion: 0)
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EF17vDgq01yOH2ThshEvckTcobee3ksG","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'EF17vDgq01yOH2ThshEvckTcobee3ksG', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F6B5DBB-1C61-4809-A491-89BBC874CDFD (syncValue: lFthHKW,77KlV7FrwBc8H2zXKYxvo11Pb)'
2017-07-14 11:29:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDF,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", genera,tion: 0)
2017-07-14 11:29:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lFthHKW77KlV7FrwBc8H2zXKYxvo11Pb","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:24 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'lFthHKW77KlV7FrwBc8H2zXKYxvo11Pb', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:29:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F6B5DBB-1C61-4809-A491-89BBC874CDFD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:24 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3EF12D56-06E7-4BD7-B33A-43FCA5D374FE (syncValue: vJDEV6Z,mw2XCTV5nIohPysMOepqrTR7p)'
2017-07-14 11:29:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374F,E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B8364F78-AFB6-40C3-9EF2-9D0689F5A8DD", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F6B5DBB-1C61-4809-A491-89BBC874CDFD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F6B5DBB-1C61-4809-A491-89BBC874CDFD", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49960
,2017-07-14 11:29:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vJDEV6Zmw2XCTV5nIohPysMOepqrTR7p","error":null,"portNumber":49960}'
,2017-07-14 11:29:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vJDEV6Zmw2XCTV5nIohPysMOepqrTR7p', error: 'null', listeningPort: '49960''
,Connecting to the localhost:49960
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,Connected to the localhost:49960
,2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-14 11:29:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,ok 104 got the same data back
,# teardown
,2017-07-14 11:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49960
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,# setup
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:29:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:278B96CA-1D44-46A9-9D5A-17875731F8E8
2017-07-14 1,1:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7AA0CCB5-DB1B-4C44-818E-1FEE65C0EC37
[Tha,liCore] Browser.startListening
,2017-07-14 11:29:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:29:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
2017-07-14 11:29:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3EF12D56-06E7-4BD7-B33A-43FCA5D374FE, (syncValue: MNkFhH6bcbosasssUM8eLOF4oqQ0nQ2p)'
2017-07-14 11:29:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foun,dPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-14 11:29:29, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:,0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,2017-07-14 11:29:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:278B96CA-1D44-46A9-9D5A-17875731F8E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "278B96CA-1D44-46A9-9D5A-17875731F8E8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", genera,tion: 0)
2017-07-14 11:29:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MNkFhH6bcbosasssUM8eLOF4oqQ0nQ2p","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:35 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'MNkFhH6bcbosasssUM8eLOF4oqQ0nQ2p', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:29:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:35 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:35 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F12BAB81-3393-4AA2-9828-2D573BD80FEA (syncValue: qffSst8,zQmYMxDvp8pc14OrY3ETdIFPL)'
2017-07-14 11:29:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FE,A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49969
2017-07-14 11:29:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qffSst8zQmYMxDvp8pc14OrY3ETdIFPL",,"error":null,"portNumber":49969}'
2017-07-14 11:29:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qffSst8zQmYMxDvp8pc14OrY3ETdIFPL', error: 'null', listeningPort: '49969''
,Connecting to the localhost:49969
Connecting to the localhost:49969
Connecting to the localhost:49969
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
Connected to the localhost:49969
,Connected to the localhost:49969
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
Connected to the localho,st:49969
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-14 11:29:38 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 111 correct string length
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-14 11:29:39 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 112 got the same data back
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 []
,ok 114 got the same data back
,# teardown
,2017-07-14 11:29:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49969
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,# setup
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:29:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-14 11:29:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C8951314-1504-4B26-B452-4EE45DC1E5BE
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DE656F0B-E661-47B6-9F44-012BDA801F49
,[ThaliCore] Browser.startListening
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:29:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
2017-07-14 11:29:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
2017-07-14 11:29:45 - DEBUG t,haliMobileNativeTestUtils: 'Issuing multiConnect for FFF4B219-CD64-4984-A16E-09A0AC4255C5 (syncValue: 9PQ8TMucjS6eqmIgrGSFHd50cBos40cX)'
2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.conn,ectToPeer(_:syncValue:completion:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
,2017-07-14 11:29:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,2017-07-14 11:29:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8951314-1504-4B26-B452-4EE45DC1E5BE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8951314-1504-4B26-B452-4EE45DC1E5BE", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
2017-07-14 11:29:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3EF12D56-06E7-4BD7-B33A-43FCA5D374FE","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0)
[ThaliCore] Session.disconnect() peer:FFF4B219-CD6,4-4984-A16E-09A0AC4255C5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:FFF4B219-CD64-4984-A16E-09A0AC4255C5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FFF4B219-CD64-4984-A16E-09A0AC4255C5", genera,tion: 0)
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9PQ8TMucjS6eqmIgrGSFHd50cBos40cX","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '9PQ8TMucjS6eqmIgrGSFHd50cBos40cX', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:29:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FFF4B219-CD64-4984-A16E-09A0AC4255C5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F12BAB81-3393-4AA2-9828-2D573BD80FEA (syncValue: NPLkvpX,ERoCnQBpWiiAGiTovLi0mPyZd)'
2017-07-14 11:29:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FE,A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", genera,tion: 0)
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NPLkvpXERoCnQBpWiiAGiTovLi0mPyZd","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'NPLkvpXERoCnQBpWiiAGiTovLi0mPyZd', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14, 11:29:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F12BAB81-3393-4AA2-9828-2D573BD80FEA","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:29:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8F36F6-99AE-405C-9D86-AFF2583B9FB5 (syncValue: Xu4iByg,UpavQpVNmDEnIMQamNsfvHJc3)'
2017-07-14 11:29:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB,5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F12BAB81-3393-4AA2-9828-2D573BD80FEA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F12BAB81-3393-4AA2-9828-2D573BD80FEA", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3EF12D56-06E7-4BD7-B33A-43FCA5D374FE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3EF12D56-06E7-4BD7-B33A-43FCA5D374FE", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49981
2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Xu4iBygUpavQpVNmDEnIMQamNsfvHJc3","error":null,"portN,umber":49981}'
2017-07-14 11:30:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Xu4iBygUpavQpVNmDEnIMQamNsfvHJc3', error: 'null', listeningPort: '49981''
,Connecting to the localhost:49981
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49981
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-14 11:30:00 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:5 []
,# teardown
,2017-07-14 11:30:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49981
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,# setup
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AA379747-01A1-4A4B-8F7B-CD076EE4D8A4
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5C412DB4-3630-41E3-B6E7-1228683AFE89 (syncValue: 2JAFyeRabhjRrLih2jkJzD8irmpPxUVt)'
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:30:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
2017-07-14 11:30:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4101E0A-2D4F-4307-AF8E-D44CB4B5801D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C30EC80-858C-4E61-957C-3AAAD5A8369E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C30EC80-858C-4E61-957C-3AAAD5A8369E", generation: 0)
2017-07-14 11:30:03 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C30EC80-858C-4E61-957C-3AAAD5A8369E","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", genera,tion: 0)
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2JAFyeRabhjRrLih2jkJzD8irmpPxUVt","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '2JAFyeRabhjRrLih2jkJzD8irmpPxUVt', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:30:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E8F36F6-99AE-405C-9D86-AFF2583B9FB5 (syncValue: bbJGuFt,JE3fgu3ZPNVPOXQQO8Mt4mncl)'
2017-07-14 11:30:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532
[ThaliCore] Advertiser: session connected Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532
[ThaliCore] Session.startOutputStream(with:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6, [6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (7665 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (8689 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (17591 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (19710 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E8F36F6-99AE-405C-9D86-,AFF2583B9FB5", generation: 0)
[ThaliCore] Session.disconnect() peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
2017-07-14 11:30:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-14 11:30:10 - DEBUG testThaliMobileNa,tive: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:0E8F36F6-99AE-405C-9D86-AFF2583B9FB5:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "0E8F36F6-99AE-405C-9D86-AFF2583B9FB5", genera,tion: 0)
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bbJGuFtJE3fgu3ZPNVPOXQQO8Mt4mncl","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'bbJGuFtJE3fgu3ZPNVPOXQQO8Mt4mncl', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-14 ,11:30:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0E8F36F6-99AE-405C-9D86-AFF2583B9FB5","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:12 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3203DACF-B417-4CCC-94E9-26751E12B3CC (syncValue: ZdTrZ3Q,VKOkLVUXbzs2fXKH1PgkKdo9B)'
2017-07-14 11:30:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3203DACF-B417-4CCC-94E9-26751E12B3C,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49993
2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZdTrZ3QVKOkLVUXbzs2fXKH1PgkKdo9B",,"error":null,"portNumber":49993}'
2017-07-14 11:30:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ZdTrZ3QVKOkLVUXbzs2fXKH1PgkKdo9B', error: 'null', listeningPort: '49993''
Connecting to the localhost:49993
[ThaliCore] TCPL,istener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
Connected to the localhost:49993
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [6, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-14 11:30:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [6]
,ok 124 got the same data back
,# teardown
,2017-07-14 11:30:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:3203DACF-B417-4CCC-94E9-26751E12B3CC
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49993
[ThaliCore] Session.disconnect,() peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:B7417788-2AEE-41A9-B2CD-891949FE3532 state: connected -> notConnected,
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A4101E0A-2D4F-4307-AF8E-D44CB4B5801D", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adv,ertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B7417788-2AEE-41A9-B2CD-891949FE3532
[ThaliCore] Session.session(_:peer:didChange:) peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0 state: connected -> notConnected
[ThaliCore] Bro,wser: session notConnected Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
# setup
[ThaliCore] Session.deinit peer:B7417788-2AEE-41A9-B2CD-891949FE3532
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D6555B65-CFFE-4044-ACB7-BEF86261266B
[ThaliCore] Browser.startListening
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C176BE14-FC26-4A57-A85E-77356D3F97EA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C176BE14-FC26-4A57-A85E-77356D3F97EA
,2017-07-14 11:30:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-14 11:30:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}]'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}]'
2017-07-14 11:30:18 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}'
,2017-07-14 11:30:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C176BE14-FC26-4A57-A85E-77356D3F97EA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C176BE14-FC26-4A57-A85E-77356D3F97EA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
2017-07-14 11:30:19 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}]'
2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}'
2017-07-14 11:30:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3203DACF-B417-4CCC-94E9-26751E12B3CC:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3203DACF-B417-4CCC-94E9-26751E12B3CC", generation: 0)
2017-07-14 11:30:20 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}]'
2017-07-14 11:30:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"3203DACF-B417-4CCC-94E9-26751E12B3CC","generation":0}'
2017-07-14 11:30:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5C412DB4-3630-41E3-B6E7-1228683AFE89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5C412DB4-3630-41E3-B6E7-1228683AFE89", generation: 0)
2017-07-14 11:30:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}]'
2017-07-14 11:30:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"5C412DB4-3630-41E3-B6E7-1228683AFE89","generation":0}'
2017-07-14 11:30:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-14 11:30:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: ',discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndLi,stening in teardown
,# setup
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-14 11:30:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:114347F8-509E-44E1-8493-98725AD9FEAC
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "868DB82E-A055-4907-BAE8-EC55B2BA05A3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:868DB82E-A055-4907-BAE8-EC55B2BA05A3
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-14 11:30:25 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-14 11:30:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:750085b4-be8b-4b60-a067-b90d9ba13c1a error: startListeningNotActive
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vCMZJyXTwPjwXoy20Qo30yyyy1Bycrg6","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"750085b4-be8b-4b60-a067-b90d9ba13c1a","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"750085b4-be8b-4b60-a067-b90d9ba13c1a","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 162 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A6ADC45A-19E0-4CC2-8C64-3E493B335265
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qUwkmRRelc8XLz7IunyMHr1xKr90U2nI","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-14 11:30:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:30:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E34B3716-B529-4714-93FE-761F7646D79B
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 No error on starting
,ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 178 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:cbaf8e02-b3dd-41a6-a786-83b8cc18b01b
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 182 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Get same port when trying to connect multiple times on iOS
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 183 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# initial peer discovery
,2017-07-14 11:30:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-14 11:30:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-14 11:30:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 49998'
,ok 185 Should throw
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50000'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 initial connection state should be CONNECTED
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 187 final connection state should be DISCONNECTED
,# teardown
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-14 11:30:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'listening 50003'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 188 tried to connect to right port
,ok 189 failed due to refused connection
,ok 190 routerPortConnectionFailed is emitted
,# teardown
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50007'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 191 Send/recvd #1 should be equal length
,ok 192 Send/recvd #1 should be same
,ok 193 Send/recvd #2 should be equal length
,ok 194 Send/recvd #2 should be same
,ok 195 Should be exactly 2 client sockets
,# teardown
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'listening 50012'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 196 socket shouldn't close until after stream
,ok 197 incoming remains open
,# teardown
,2017-07-14 11:30:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-14 11:30:33, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-14 11:30:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50016'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should not have gotten an error
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 socket shouldn't close until after incoming
,ok 200 incoming is cleaned up
,# teardown
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'listening 50020'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 201 stream was closed
,ok 202 incoming should survive
,ok 203 mux should have no streams
,# teardown
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50024'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 204 we should not have gotten an error
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 205 Buffers are identical
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 206 native server is nulled out
,ok 207 native server should be closed
,ok 208 incoming has been removed
,ok 209 Incoming should be done
,ok 210 The mux object should be closed
,ok 211 The mux stream should be closed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:35 - DEBUG createNativeListener: 'listening 50028'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-14 11:30:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 212 native server is nulled out
,ok 213 native server should be closed
,ok 214 incoming has been removed
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-14 11:30:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50080'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 215 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 216 Buffers are identical
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 217 server should be fine
,ok 218 server should be open
ok 219 incoming has been removed
,ok 220 The mux object should be closed
,ok 221 The mux stream should be closed
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'listening 50084'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 222 we should not have gotten an error
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 223 Buffers are identical
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 224 server should be fine
,ok 225 server should be open
,ok 226 incoming has been removed
,ok 227 The mux object should be closed
,ok 228 The mux stream should be closed
,# teardown
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:37 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:38 - DEBUG createNativeListener: 'listening 50087'
ok 232 port must be in range
,# teardown
,2017-07-14 11:30:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50088'
ok 233 second start should return same port
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'listening 50090'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 234 we should be connected
2017-07-14 11:30:39 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 235 now we are disconnected
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-14 11:30:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:30:39 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 236 Passed bogus id
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 237 Passed good id but bogus port
,2017-07-14 11:30:40 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 238 Passed right context
,ok 239 Right server
,ok 240 No error should be set
,ok 241 Retry should be false
,ok 242 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 50092
,ok 243 should be equal
,# teardown
,2017-07-14 11:30:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2DAB5366-D8ED-405B-840D-3F714804033E
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 244 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BFCFC0A1-B402-43F6-83FD-40A42DC67E29
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,2017-07-14 11:30:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 245 Can call startListeningForAdvertisements without error
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","generation":0}'
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 364E65AB-A73B-46E1-BB05-C330DF77328F (syncValue: RaCFXroCS9nHGk3nZzse33A0UDTjqmbm)'
,2017-07-14 11:30:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
[ThaliCore] Session.disconnect() peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
[ThaliCore] Advertiser: session connected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Advertiser: session connected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: notConnected -> connecting
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94, (syncValue: NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2)'
,2017-07-14 11:30:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
2017-07-14 11:30:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8A025A44-AD9A-48D7-A59F-2F0C9E83D78C (syncValue: pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT)'
,2017-07-14 11:30:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0 state: connecting -> connected
[ThaliCo,re] Browser: session connected to Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50100
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT","error":null,"portNumber":50100}'
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'p,m8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT', error: 'null', listeningPort: '50100''
2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT', originalSyncValue: 'RaCFXroCS9nHGk3nZzse3,3A0UDTjqmbm''
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT', error: 'null', listeningPort: '50100''
2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectRes,olved received invalid syncValue: 'pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT', originalSyncValue: 'NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2''
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pm8su6pSiDwNpC0ZsvoCetXH9Mk0XdAT', ,error: 'null', listeningPort: '50100''
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50102
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connecting -> connected
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2","error":null,"portNumber":50102}'
,2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2', error: 'null', listeningPort: '50102''
,2017-07-14 11:30:44 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2', originalSyncValue: 'RaCFXroCS9nHGk3nZzse33A0UDTjqmbm''
2017-07-14 11:30:44 - DEBUG thaliMobileNativeTestUtils: 'Go,t multiConnectResolved -syncValue: 'NAijvXLEuIcMiUBKM4P8kWE5q1w5F8D2', error: 'null', listeningPort: '50102''
,ok 246 should be equal
ok 247 (unnamed assert)
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
,[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connecting -> connected
,ok 248 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50100
,[ThaliCore] Session.disconnect() peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50102
,[ThaliCore] Session.disconnect() peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Pe,er(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCo,re] Session.disconnect() peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Session.deinit peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0 state: connected -> notConn,ected
[ThaliCore] Browser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:30:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple local http requests
,[ThaliCore] AdvertiserRelay.deinit
,listening on 50104
,ok 249 should be equal
,ok 250 should be equal
,ok 251 should be equal
,# teardown
,2017-07-14 11:30:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:2DAB5366-D8ED-405B-840D-3F714804033E
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-14 11:30:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.session(_:peer:didChange:) peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:364E65AB-A73B-46E1-BB05-C330DF77328F:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", genera,tion: 0)
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RaCFXroCS9nHGk3nZzse33A0UDTjqmbm","error":"Connection could not be established","portNumber":null}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RaCFXroCS9nHGk3nZzse33A0UDTjqmbm', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 364E65AB-A73B-46E1-BB05-C330DF77328F (syncValue: DAgZhuw7jWu6JdZ4nUtPYUT5J3JXdYJa)'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "364E65AB-A73B-46E1-BB05-C330DF77328F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DAgZhuw7jWu6JdZ4nUtPYUT5J3JXdYJa","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DAgZhuw7jWu6JdZ4nUtPYUT5J3JXdYJa', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"364E65AB-A73B-46E1-BB05-C330DF77328F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:30:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:30:46 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94 (syncValue: ELOEmcYvOrVClzIcBecgKbGvpltkfcA9)'
,2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DAB5366-D8ED-405B-840D-3F714804033E:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
2017-07-14 11:30:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8A025A44-AD9A-48D7-A59F-2F0C9E83D78C, (syncValue: bQVpOltm9kQ4q45SChZCSnuJwUh942Qx)'
2017-07-14 11:30:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", gen,eration: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
[ThaliCore] Advertiser: session connected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50114
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ELOEmcYvOrVClzIcBecgKbGvpltkfcA9","error":null,"portNumber":50114}'
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ELOEmcYvOrVClzIcBecgKbGvpltkfcA9', error: 'null', listeningPort: '50114''
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ELOEmcYvOrVClzIcBecgKbGvpltkfcA9', error: 'null', listeningPort: '50114''
,2017-07-14 11:30:50 - WARN thaliMobileNativeTestUtils: 'multiConnectResolved received invalid syncValue: 'ELOEmcYvOrVClzIcBecgKbGvpltkfcA9', originalSyncValue: 'bQVpOltm9kQ4q45SChZCSnuJwUh942Qx''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46
,ok 254 should be equal
,ok 255 (unnamed assert)
[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50116
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bQVpOltm9kQ4q45SChZCSnuJwUh942Qx","error":null,"portNumber":50116}'
,2017-07-14 11:30:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bQVpOltm9kQ4q45SChZCSnuJwUh942Qx', error: 'null', listeningPort: '50116''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Session.session(_:peer:didChange:) peer:550B4816-A411-482D-84EA-FCB63D5B8EB9 state: connecting -> connected
,ok 256 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50114
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Session.session(_:peer:didChange:) peer:30A869D0-4B7C-4223-BAC5-91263E4AAD46 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2DAB5366-D8ED-405B-840D-3F714804033E", generation: 1)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] Session.deinit peer:550B4816-A411-482D-84EA-FCB63D5B8EB9
,[ThaliCore] BrowserManager.disconnect peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50116
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,2017-07-14 11:30:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
,ok 257 specific error should be returned
,# teardown
,ok 258 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 259 specific error should be returned
,# teardown
,ok 260 must be stopped
,# setup
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50118'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 261 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 262 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 263 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'listening 50119'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B88840F9-DA23-4F12-9280-C02212E41958
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 264 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 265 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 266 must be stopped
,# setup
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'listening 50120'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A67981FD-D1EA-4482-87DD-4CED08115D37", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A67981FD-D1EA-4482-87DD-4CED08115D37
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 267 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A67981FD-D1EA-4482-87DD-4CED08115D37", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:A67981FD-D1EA-4482-87DD-4CED08115D37
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 269 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:53 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'listening 50123'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 272 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can get the network status before starting
,ok 273 network status should have certain non-empty properties
,# teardown
,ok 274 must be stopped
,# setup
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# error returned with bad router
,2017-07-14 11:30:54 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 275 specific error expected
,# teardown
,ok 276 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are started when we call start
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50124'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:30943F37-C935-42DF-8E08-D47EC12A8474
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1B511961-879B-4A3E-B10D-6856F47055A6", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1B511961-879B-4A3E-B10D-6856F47055A6
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,ok 277 all connection succeed
,# teardown
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
,# setup
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'listening 50127'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ACFD6E81-76A6-4C52-8AC6-8BC85ED1117B
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6455A3EA-CF33-4ADF-9D55-9D457DDA7C57", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6455A3EA-CF33-4ADF-9D55-9D457DDA7C57
2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:54 ,- INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType,":null}})'
2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 279 TCP Servers Manager doesn't exists
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 1)
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:30:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:30:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 280 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# all services are stopped when we call stop
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'listening 50129'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53BFCB12-DAD3-4039-8A64-E978AF253BC3
,[ThaliCore] Browser.startListening
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3045054B-DE52-4539-BF64-47C52A998D83", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3045054B-DE52-4539-BF64-47C52A998D83
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8A025A44-AD9A-48D7-A59F-2F0C9E83D78C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(u,uid: "8A025A44-AD9A-48D7-A59F-2F0C9E83D78C", generation: 0)
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:30:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:30:5,5 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-14 11:30:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 281 is stopped after calling stop
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}]'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","generation":0}'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 282 connection should fail after stopping
,# teardown
,ok 283 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is properly hooked up
,2017-07-14 11:30:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 284 must be stopped
,# setup
,2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateConnection is return error if we get called on iOS
,ok 285 error description matches
,# teardown
,ok 286 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is properly hooked up
,2017-07-14 11:30:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 287 must be stopped
,# setup
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure terminateListener is return error if we get called on iOS
,ok 288 error description matches
,# teardown
,ok 289 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:57 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure we actually call kill connections properly
,ok 290 IMPLEMENT ME!!!!!!
,# teardown
,ok 291 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 292 must be stopped
,# setup
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-14 11:30:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 293 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 294 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-14 11:30:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 295 must be stopped
,# setup
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 296 NOT IMPLEMENTED # SKIP
,# teardown
,ok 297 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:30:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# make sure bad PSK connections fail
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 298 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peer changes handled from a queue
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 299 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 300 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-14 11:30:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 301 must be stopped
,# setup
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:30:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:30:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50132'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8C5BBC82-CE4C-4B73-8AAF-F9D47B81A1CF
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 302 discoveryActive matches
,ok 303 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 304 discoveryActive matches
,ok 305 advertisingActive matches
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50133'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "46C26100-94A6-4A2E-9D25-EE7766B09849", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:46C26100-94A6-4A2E-9D25-EE7766B09849
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 306 discoveryActive matches
,ok 307 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 308 discoveryActive matches
,ok 309 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50135'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 must be stopped
,# setup
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:00 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'listening 50136'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1B092CAB-F1CB-4823-926F-B806BBF41CF1
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8EFC9B37-2EB6-44D0-BD7D-7C8AC4629A47
,2017-07-14 11:31:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
2017-07-14 11:31:01 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}]'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":1,"portNumber":null}'
,ok 311 portNumber equal null
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 312 must be stopped
,# setup
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests between peers
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'listening 50138'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E535493C-3400-4063-8945-B413DD99AE3B
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:117A1A18-8269-454A-B098-B1D2BC0CA557
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}]'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}]'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 910AB337-4ECA-404D-A728-DA5FDCBE0C94 (syncValue: QbWscCOrhSBjD0QrRvKu1UwahPhzOSsc)'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}]'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:30EEEF58-6F93-47A9-AFF1-D262152011B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "30EEEF58-6F93-47A9-AFF1-D262152011B0", generation: 0)
2017-07-14 11:31:03 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}]'
2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","generation":0}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:117A1A18-8269-454A-B098-B1D2BC0CA557:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "117A1A18-8269-454A-B098-B1D2BC0CA557", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", genera,tion: 1)
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QbWscCOrhSBjD0QrRvKu1UwahPhzOSsc","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'QbWscCOrhSBjD0QrRvKu1UwahPhzOSsc', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDC,BE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 11:31:08 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,ier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D08813FF-67B9-418D-ADC2-3A899BCA976D (syncValue: QueraJ7ImqL6XAdXyEISee2xRRvrXpGn)'
,2017-07-14 11:31:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 1)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:910AB337-4ECA-404D-A728-DA5FDCBE0C94:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "910AB337-4ECA-404D-A728-DA5FDCBE0C94", generation: 0)
,2017-07-14 11:31:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}]'
2017-07-14 11:31:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","generation":1}'
,2017-07-14 11:31:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"910AB337-4ECA-404D-A728-DA5FDCBE0C94","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50143
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QueraJ7ImqL6XAdXyEISee2xRRvrXpGn","error":null,"portNumber":50143}'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QueraJ7ImqL6XAdXyEISee2xRRvrXpGn', error: 'null', listeningPort: '50143''
,2017-07-14 11:31:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [6, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:12 - DEBUG testUtils: 'Got end'
,ok 313 response body should match testData
,ok 314 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:1,2 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkT,ype":null}})'
2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-14 11:31:12 - DEBUG tha,liMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:12 - DEBU,G makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 must be stopped
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] BrowserManager.disconnect peer:D08813FF-67B9-418D-ADC2-3A899BCA976D
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50143
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] BrowserRelay.didCloseVirtual,SocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket.deinit vsID:8 [6]
[ThaliCore] Session.disconnect() peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,# setup
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can still do HTTP requests between peers with coordinator
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'listening 50145'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:82BB5CCD-7D08-4872-AE79-6F65FA9D0D0C
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:75A74F2C-36D7-4F68-A621-7E4E5356421E
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
2017-07-14 11:31:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}]'
2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","generation":0}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D08813FF-67B9-418D-ADC2-3A899BCA976D (syncValue: KiSb3oylLwIfu3z7bJHhc9lPs4Lnk7mU)'
,2017-07-14 11:31:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}]'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75A74F2C-36D7-4F68-A621-7E4E5356421E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D08813FF-67B9-418D-ADC2-3A899BCA976D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D08813FF-67B9-418D-ADC2-3A899BCA976D", genera,tion: 0)
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KiSb3oylLwIfu3z7bJHhc9lPs4Lnk7mU","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'KiSb3oylLwIfu3z7bJHhc9lPs4Lnk7mU', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899,BCA976D","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-14 11:31:19 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,ier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-14 11:31:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4058EBCF-2389-4A80-8739-3BC964E93946 (syncValue: BnlLc4T3YQ3bEdPyE3qhWwgDnVSSxtZk)'
,2017-07-14 11:31:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
[ThaliCore] Advertiser: session connected Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50150
,2017-07-14 11:31:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BnlLc4T3YQ3bEdPyE3qhWwgDnVSSxtZk","error":null,"portNumber":50150}'
,2017-07-14 11:31:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BnlLc4T3YQ3bEdPyE3qhWwgDnVSSxtZk', error: 'null', listeningPort: '50150''
,2017-07-14 11:31:22 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [6, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
,[ThaliCore] Session.session(_:peer:didChange:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
[ThaliCore] Session.startOutputStream(with:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [6, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-14 11:31:22 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:22 - DEBUG testUtils: 'Got end'
,ok 316 response body should match testData
,ok 317 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] Virt,ualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [6, 9]
,ok 318 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:4058EBCF-2389-4A80-8739-3BC964E93946
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50150
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
,[ThaliCore] VirtualSocket.deinit vsID:9 [6]
,[ThaliCore] Session.disconnect() peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "75A74F2C-36D7-4F68-A621-7E4E5356421E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:62DF7AE8-2B52-4E5D-9826-79DD2B8876B5
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# calls correct starts when network changes
,2017-07-14 11:31:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 319 must be stopped
,# setup
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# test to coordinate connection cut
,# teardown
,ok 320 must be stopped
,# setup
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# can do HTTP requests after connections are cut
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'listening 50153'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC9BE05F-AFF6-433D-9CB7-76BD6CCEBD78
[ThaliCore] Browser.st,artListening
2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,E89525DA-D2AA-454F-878F-E377A11FB974
,2017-07-14 11:31:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-14 11:31:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-14 11:31:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
2017-07-14 11:31:32 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49D2AE96-57F9-,4114-BFBB-AC26386E4157", generation: 0)
2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4058EBCF-2389-4A80-8739-3BC964E93946 (syncValue: 8fKZa2qCORp31uv0B01PcGxv6mUrbDTM)'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E89525DA-D2AA-454F-878F-E377A11FB974:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:31:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:31:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] Session.disconnect() peer:4058EBCF-238,9-4A80-8739-3BC964E93946:0
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}]'
2017-07-14 11:31:,37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","generation":0}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-14 11:31:37 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733
[ThaliCore] Advertiser: session connected Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4058EBCF-2389-4A80-8739-3BC964E93946:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:4058EBCF-2389-4A80-8739-3BC964E93946:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4058EBCF-2389-4A80-8739-3BC964E93946", genera,tion: 0)
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8fKZa2qCORp31uv0B01PcGxv6mUrbDTM","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '8fKZa2qCORp31uv0B01PcGxv6mUrbDTM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"4058EBCF-2389-4A80-8739-3BC964E93946","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:4058EBCF-2389-4A80-8739-3BC964E93946
,2017-07-14 11:31:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49D2AE96-57F9-4114-BFBB-AC26386E4157 (syncValue: D6H9HmZkSXiqIheoUrQXgdaneVkuBLBf)'
2017-07-14 11:31:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC,26386E4157", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733
[ThaliCore] Session.startOutputStream(with:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [6, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
[ThaliCore] Advertiser: session connected Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,[ThaliCore] Session.disconnect() peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}]'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","generation":0}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:31:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0 state: notConnected -> notConnected
,[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] Session.disconnect() peer:49D2AE96-57F9-4114-BFBB-AC26386E4157:0
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "49D2AE96-57F9-4114-BFBB-AC26386E4157", generation: 0)
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"D6H9HmZkSXiqIheoUrQXgdaneVkuBLBf","error":"Connection could not be established","portNumber":null}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'D6H9HmZkSXiqIheoUrQXgdaneVkuBLBf', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"49D2AE96-57F9-4114-BFBB-AC26386E4157","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:49D2AE96-57F9-4114-BFBB-AC26386E4157
,2017-07-14 11:31:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D5043C6C-65B0-4F29-8A29-F635EBFE335E (syncValue: 2yG7b2cLNnFBuMVQpZERm6I0DVLVToGs)'
,2017-07-14 11:31:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50163
2017-07-14 11:31:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2yG7b2cLNnFBuMVQpZERm6I0DVLVToGs","error":null,"portN,umber":50163}'
,2017-07-14 11:31:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '2yG7b2cLNnFBuMVQpZERm6I0DVLVToGs', error: 'null', listeningPort: '50163''
,2017-07-14 11:31:45 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
[ThaliCore] Session.startOutputStream(with:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [6, 11, 12]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
[ThaliCore] TCPClient: didConnectToHost, active connection,s count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [6, 11, 12, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:31:45 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:31:45 - DEBUG testUtils: 'Got end'
,ok 321 response body should match testData
,ok 322 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-14 11:31:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] Session.session(_:peer:didChange:) peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
[ThaliCore] VirtualSo,cket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnect,ing:true
[ThaliCore] VirtualSocket.deinit vsID:13 [6, 11, 12]
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
[ThaliCore] TCPList,ener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:12 [6, 11]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EFCB72AE-302D-4AF9-B318-135AFB3418A3
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:EFCB,72AE-302D-4AF9-B318-135AFB3418A3
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] Virt,ualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [6]
,ok 323 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:50163
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8990B9F-58FA-4A2E-AAB2-7242E6E86733 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E89525DA-D2AA-454F-878F-E377A11FB974", generation: 0)
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# will fail bad PSK connection between peers
,ok 324 FIX ME, PLEASE!!!
,# teardown
,ok 325 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We provide notification when a listener dies and we recreate it
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 326 must be stopped
,# setup
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-14 11:31:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-14 11:31:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-14 11:31:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 327 must be stopped
,# setup
,ok 328 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 329 specific error should be returned
,# teardown
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8A025A44-AD9A-48D7-A59F-2F0C9E83D78C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D08813FF-67B9-418D-ADC2-3A899BCA976D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"30EEEF58-6F93-47A9-AFF1-D262152011B0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'listening 50166'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 337 error should be null
,ok 338 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 339 error should be null
,ok 340 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-14 11:31:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-14 11:31:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-14 11:31:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50167'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:976DAF7E-BFE4-41FB-BBB5-E1E1CF63EB5A
,[ThaliCore] Browser.startListening
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 344 error should be null
,ok 345 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 346 error should be null
,ok 347 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'listening 50168'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F99364ED-F211-46AB-BF9C-CF1195ADBD15", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F99364ED-F211-46AB-BF9C-CF1195ADBD15
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 351 error should be null
,ok 352 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F99364ED-F211-46AB-BF9C-CF1195ADBD15", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:F99364ED-F211-46AB-BF9C-CF1195ADBD15
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 353 error should be null
,ok 354 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 355 error should be null
,ok 356 error should be null
,# setup
,ok 357 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'listening 50171'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 358 error should be null
,ok 359 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 360 error should be null
,ok 361 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-14 11:31:50 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 365 This should not cause wifi to fail
,ok 366 native router should be bad
,# teardown
,ok 367 error should be null
,ok 368 error should be null
,# setup
,ok 369 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'listening 50172'
,ok 370 first call should succeed
,ok 371 first call should succeed
,ok 372 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 373 error should be null
,ok 374 error should be null
,# setup
,ok 375 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 376 error should be null
ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-14 11:31:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 379 error should be null
ok 380 error should be null
,# setup
,ok 381 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-14 11:31:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f161b062-87e7-403c-a48e-7eb870c62894","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 382 should be called once
ok 383 should not have been called more than once
,# teardown
,2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f161b062-87e7-403c-a48e-7eb870c62894","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 384 error should be null
ok 385 error should be null
# setup
,ok 386 ThaliMobile should be stopped
,# can get the network status
,ok 387 network status should have certain non-empty properties
,# teardown
,ok 388 error should be null
,ok 389 error should be null
,# setup
,ok 390 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 391 we have not added peer to the cache yet
2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cf28eab5-1622-4d33-9dc5-86365707ee6f","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 392 peer should be available
ok 393 cache contains native peer
2017-07-14 11:31:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cf28eab5-1622-4d33-9dc5-86365707ee6f","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 394 peer should be unavailable
,ok 395 peer has been removed from cache
,# teardown
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 399 we have not added peer to the cache yet
2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d5069fb0-ee5e-4228-aaf3-579cb73f68dc","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 400 peer should be available
,ok 401 cache contains wifi peer
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d5069fb0-ee5e-4228-aaf3-579cb73f68dc","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 402 peer should be unavailable
,ok 403 peer has been removed from cache
,# teardown
,ok 404 error should be null
,ok 405 error should be null
,# setup
,ok 406 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e1eaff4f-1110-4f0e-b3a7-e80aabc94e0f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 407 first peer is available
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"69e57d8d-9727-4f04-98aa-4ebdaea65bdb","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 second peer is available
,ok 409 first and second peers are different
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e1eaff4f-1110-4f0e-b3a7-e80aabc94e0f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"69e57d8d-9727-4f04-98aa-4ebdaea65bdb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 410 error should be null
,ok 411 error should be null
,# setup
,ok 412 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 413 should not be in cache at start
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f502729b-d932-49a1-b1a7-ddc6fa8e41bd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 peer is available
,# teardown
,2017-07-14 11:31:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f502729b-d932-49a1-b1a7-ddc6fa8e41bd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 415 error should be null
ok 416 error should be null
,# setup
,ok 417 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-14 11:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 418 error should be null
ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-14 11:31:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 421 error should be null
ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bc0fbc6c-460e-4315-b255-dead3699369b","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 424 peer should be available
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bc0fbc6c-460e-4315-b255-dead3699369b","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 425 peer should be available
,ok 426 should store correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bc0fbc6c-460e-4315-b255-dead3699369b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 error should be null
,ok 428 error should be null
,# setup
,ok 429 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'listening 50173'
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"975ddb51-2696-4913-b6f9-38bf4a763930","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 430 discovered correct peer
,ok 431 got correct generation
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"975ddb51-2696-4913-b6f9-38bf4a763930","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 432 discovered correct peer
,ok 433 got correct generation
,# teardown
,2017-07-14 11:31:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"975ddb51-2696-4913-b6f9-38bf4a763930","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 434 error should be null
,ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50174'
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95f607de-7845-447f-8597-4fa78dc08dd4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 437 discovered available peer
,ok 438 peer is available
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"95f607de-7845-447f-8597-4fa78dc08dd4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 439 error should be null
,ok 440 error should be null
,# setup
,ok 441 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f43721d9-9329-429a-81f4-1deba7e9d77b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 442 peer should be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f43721d9-9329-429a-81f4-1deba7e9d77b","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 443 peer should be unavailable
,ok 444 should be removed from cache
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'listening 50175'
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5ff2f6e0-b30e-4312-b3de-0f6aa37b9570","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 448 first peer is expected to be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cee988e3-343c-4e68-9e2a-79ae53b48c80","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 449 second peer is expected to be available
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cee988e3-343c-4e68-9e2a-79ae53b48c80","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 450 peer became unavailable
,ok 451 it was wifi peer
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cee988e3-343c-4e68-9e2a-79ae53b48c80","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 452 we found peer again
,ok 453 it was wifi peer
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cee988e3-343c-4e68-9e2a-79ae53b48c80","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 454 peer became unavailable
,ok 455 it was wifi peer
,# teardown
,2017-07-14 11:31:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5ff2f6e0-b30e-4312-b3de-0f6aa37b9570","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 456 error should be null
,ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-14 11:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'listening 50176'
2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a667f215-2a0b-4235-bee5-b44fdaedb9a9","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 462 first peer is expected to be available
2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"db3462a6-9304-4f08-a580-555ffe92bb53","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 463 second peer is expected to be available
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a667f215-2a0b-4235-bee5-b44fdaedb9a9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 464 peer became unavailable
,2017-07-14 11:31:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"db3462a6-9304-4f08-a580-555ffe92bb53","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:31:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:31:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:31:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 466 error should be null
,ok 467 error should be null
,# setup
,ok 468 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-14 11:31:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 472 error should be null
ok 473 error should be null
,# setup
,ok 474 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ab83815-2e31-438b-89b3-d8cdd81e809b","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 475 peer discovered ,first time does not have new address
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ab83815-2e31-438b-89b3-d8cdd81e809b","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 476 address has not been changed
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ab83815-2e31-438b-89b3-d8cdd81e809b","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 477 new port handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ab83815-2e31-438b-89b3-d8cdd81e809b","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 478 new host handled correctly
2017-07-14 11:31:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ab83815-2e31-438b-89b3-d8cdd81e809b","connectionType":"tcp","peerAva,ilable":false,"generation":20,"newAddressPort":null}'
ok 479 newAddressPort is null for unavailable peers
,# teardown
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-14 11:31:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
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
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-14 11:31:59 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 497 error should be null
,ok 498 error should be null
,# setup
,ok 499 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 500 contains expected properties
,ok 501 the same hostAddress
,ok 502 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 503 error should be null
,ok 504 error should be null
,# setup
,ok 505 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 506 contains expected properties
,ok 507 the same hostAddress
,ok 508 the same portNumber
,# teardown
,2017-07-14 11:32:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 509 error should be null
ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50177'
2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"74fb0815-cd06-4701-a89b-22931b5dfac2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 512 Got specific error message
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"74fb0815-cd06-4701-a89b-22931b5dfac2","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'listening 50178'
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1bf5822b-1e41-4e13-9eb5-0fd64e4c30f1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:1bf5822b-1e41-4e13-9eb5-0fd64e4c30f1
,ok 516 native wrapper `disconnect` called once
,ok 517 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-14 11:32:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1bf5822b-1e41-4e13-9eb5-0fd64e4c30f1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-14 11:32:01 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 521 error should be null
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 524 error should be null
ok 525 error should be null
,# setup
,ok 526 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 527 error should be null
ok 528 error should be null
,# setup
,ok 529 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,ok 532 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-14 11:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 533 error should be null
,ok 534 error should be null
,# setup
,ok 535 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 536 error should be null
,ok 537 error should be null
,# setup
,ok 538 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-14 11:32:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 539 error should be null
ok 540 error should be null
,# setup
,ok 541 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'listening 50179'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AB8D0032-1586-4B78-BC66-C7019B0D9047
,[ThaliCore] Browser.startListening
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3e2e0c7c-5425-4dc5-8722-7277591c6a2e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 542 Peer availabilities has one entry for our connection type
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26ef70c1-2e02-42e2-804f-0c941d6861f3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 543 Peer availabilities has one entry for our connection type
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3e2e0c7c-5425-4dc5-8722-7277591c6a2e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"26ef70c1-2e02-42e2-804f-0c941d6861f3","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-14 11:32:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}]'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}'
,2017-07-14 11:32:03 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-14 11:32:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 544 No peers
,ok 545 No peers
,ok 546 No peers
,# teardown
,ok 547 error should be null
,ok 548 error should be null
,# setup
,ok 549 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'listening 50180'
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c5d0cb4b-2f7a-4e2b-b683-ea6f9601e5aa","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 550 1
,ok 551 2
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bc32afeb-af75-4b85-9a8a-d13741dba77b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c5d0cb4b-2f7a-4e2b-b683-ea6f9601e5aa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bc32afeb-af75-4b85-9a8a-d13741dba77b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-14 11:32:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 552 error should be null
,ok 553 error should be null
,# setup
,ok 554 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-14 11:32:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 555 error should be null
ok 556 error should be null
,# setup
,ok 557 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'listening 50181'
ok 558 error should be null
ok 559 error should be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "42877076-2AF7-4818-A925-8E,37D50E743E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:42877076-2AF7-4818-A925-8E37D50E743E
2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive,":true}'
,ok 560 error should be null
ok 561 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:39B8D97C-8A45-4508-9AE2-11E8F8BE0FF7
[ThaliCore] Browser.startListening
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 562 error should be null
ok 563 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
2017-07-14 11:32:05 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}]'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:32:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:32:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E (syncValue: 0)'
,2017-07-14 11:32:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","generation":0}]'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] Advertiser: session connected Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
2017-07-14 11:32:06 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","generation":0}]'
2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","generation":0}'
,2017-07-14 11:32:06 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-14 11:32:06 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42877076-2AF7-4818-A925-8E37D50E743E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42877076-2AF7-4818-A925-8E37D50E743E", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0)
[ThaliCore] Session.disconnect() peer:EC78D8CD-E2D,8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,2017-07-14 11:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}]'
2017-07-14 11:32:07 - DEBUG thaliMobileNative,Wrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","generation":0}'
2017-07-14 11:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from nati,ve layer [{"peerAvailable":false,"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","generation":0}]'
2017-07-14 11:32:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"D5043C,6C-65B0-4F29-8A29-F635EBFE335E","generation":0}'
,2017-07-14 11:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:32:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:07 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-14 11:32:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] Session.startOutputStream(with:) peer:CF906A19-8B04-431A-ACC6-1FA163302ED2
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [6, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] Advertiser: session connected Peer(uuid: "42877076-2AF7-4818-A925-8E37,D50E743E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794 state: notConnected -> connecting
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E", genera,tion: 0)
2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability cha,nged event with {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC,7,8D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for D5043C6C-65B0-4F29-8A29-F635EBFE335E (syncValue: 1)'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D5043C6C-65B0-4F29-8A29-F635EBFE335E", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) error:unavailablePeer
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 994F4DE1-7A0E-410E-9D9D-4D8018271D03 (syncValue: 2)'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-14 11:32:10 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-14 11:32:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D5043C6C-65B0-4F29-8A29-F635EBFE335E","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
,[ThaliCore] Session.session(_:peer:didChange:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] Session.startOutputStream(with:) peer:347F6BE3-9E54-4136-A461-18BE2D6B7794
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [6, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "994F4DE1-7A0E-410E-9D9D-4D8018271D03", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50189
,2017-07-14 11:32:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":50189}'
,2017-07-14 11:32:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 780F3D92-A26A-44CD-934D-636A0E30EC8B (syncValue: 3)'
,2017-07-14 11:32:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:994F4DE1-7A0E-410E-9D9D-4D8018271D03:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [6, 14, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:14 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:14 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "780F3D92-A26A-44CD-934D-636A0E30EC8B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:50193
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":50193}'
,[ThaliCore] BrowserManager.disconnect peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E
,[ThaliCore] BrowserManager.disconnect peer:EC78D8CD-E2D8-4E6D-806C-619B6CE4D33E
,[ThaliCore] BrowserManager.disconnect peer:D5043C6C-65B0-4F29-8A29-F635EBFE335E
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:780F3D92-A26A-44CD-934D-636A0E30EC8B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [6, 14, 15, 16, 17]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-14 11:32:17 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:17 - DEBUG testUtils: 'Got end'
,ok 564 received all uuids
,# teardown
,2017-07-14 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"994F4DE1-7A0E-410E-9D9D-4D8018271D03","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-14 11:32:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"780F3D92-A26A-44CD-934D-636A0E30EC8B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.deinit vsID:17 [6, 14, 15, 16]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-14 11:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-14 11:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-14 11:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-14 11:32:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] Virt,ualSocket.closeStreams() vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [6, 15, 16]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
,[ThaliCore] VirtualSocket.deinit vsID:15 [6, 16]
,ok 565 error should be null
,ok 566 error should be null
,# setup
,ok 567 ThaliMobile should be stopped
,# test for data corruption
,2017-07-14 11:32:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
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
,2017-07-14 11:32:18 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 578 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 579 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-14 11:32:19 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 586 agent is destroyed
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
,ok 624 enqueue is fine
,ok 625 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 626 is an agent
ok 627 first enqueue is fine
ok 628 is an agent
ok 629 second enqueue is fine
ok 630 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 631 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 632 is an agent
,ok 633 good enqueue
,ok 634 Identity should match
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got response data'
,2017-07-14 11:32:24 - DEBUG testUtils: 'Got end'
,ok 635 Got expected response
,ok 636 Got psk call back
,# teardown
,2017-07-14 11:32:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 647 good enqueue
,ok 648 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 649 null arg
ok 650 wrong arg type
ok 651 wrong arg type
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
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 671 Got right error
,ok 672 Start should not be called
,ok 673 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:27 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 674 Got right error
,ok 675 Start should not be called
,ok 676 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 677 Got null
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 678 is an agent
,2017-07-14 11:32:27 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 679 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 680 Got Null
,ok 681 Got another null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 682 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 683 is an agent
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 684 Action 1 killed at least once
,ok 685 Action 1 went first
,ok 686 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 687 should have gotten null
2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 688 Should have stopped nicely
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 689 Still looking for null
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-14 11:32:28 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 690 Yup, another null
,ok 691 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 692 Null 1
,ok 693 (unnamed assert)
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 694 is an agent
,ok 695 Null 3
,ok 696 Replication not yet called
,ok 697 Notification 2 not yet called
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 698 is an agent
,ok 699 Notification went first
,ok 700 Notification 2 not called yet
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 701 is an agent
,ok 702 Notification finished
,ok 703 Replication finished
,2017-07-14 11:32:29 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 704 is an agent
ok 705 First does, not throw
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 706 is an agent
ok 707 Second does not throw
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 708 is an agent
,ok 709 first ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 710 is an agent
,ok 711 second ok
,ok 712 third ok
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-14 11:32:30 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-14 11:32:31 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-14 11:32:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-14 11:32:31 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
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
,2017-07-14 11:32:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 721 Response should be HTTP_BAD_RESPONSE
,ok 722 must return null after successful call
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 723 Response should be NETWORK_PROBLEM
,ok 724 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 725 Resolution should be BAD_PEER
,ok 726 correct error message
,# teardown
,2017-07-14 11:32:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 727 Call start once
,ok 728 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 729 must return null after successful call.
,# teardown
,2017-07-14 11:32:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 730 Should be Killed
,ok 731 Start after killed
,# teardown
,2017-07-14 11:32:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 732 Should be KILLED
ok 733 must return null after successful kill
,# teardown
,2017-07-14 11:32:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 734 Should be KILLED
ok 735 must return null after successful kill
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 736 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 737 must return null after successful call
,# teardown
,2017-07-14 11:32:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-14 11:32:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 738 Should be NETWORK_PROBLEM caused closing server socket
,ok 739 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 740 Should be NETWORK_PROBLEM caused closing client socket
ok 741 Should be Could not establish TCP connection
,# teardown
,2017-07-14 11:32:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 742 publicKeysToNotify cannot be null
ok 743 ecdh for local device cannot be null
ok 744 milliseconds cannot be less than 0
ok 745 milliseconds cannot be 0
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
ok 771 keys match
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
,2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-14 11:32:51 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 11:32:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 787 notification peer dictionary contains exactly 1 peer
2017-07-14 11:32:52 - WARN thaliNotificationClient: 'peer is not available'
ok 788 notification peer dictionary does not contain any peers
,2017-07-14 11:32:52 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-14 11:32:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 789 entry exists
,ok 790 entry is resolved
,# teardown
,2017-07-14 11:32:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 791 Action should be KILLED
,ok 792 Peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 793 hostAddress must match
,ok 794 portNumber must match
,ok 795 suggestedTCPTimeout must match
,ok 796 connectionType must match
,ok 797 peerIDs must match
,# teardown
,2017-07-14 11:32:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 798 Correct error
,# teardown
,2017-07-14 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 799 hostAddress must match
,ok 800 portNumber must match
,ok 801 suggestedTCPTimeout must match
,ok 802 connectionType must match
,ok 803 peerIds must match
,# teardown
,2017-07-14 11:32:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 804 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:55 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 805 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 806 action should be resolved with NETWORK_PROBLEM error
,2017-07-14 11:32:56 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 807 action should be resolved with NETWORK_PROBLEM error
ok 808 correct number of requests
ok 809 correct number of failures
ok 810 correct final peer state
,# teardown
,2017-07-14 11:32:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-14 11:32:59 - WARN thaliNotificationClient: 'peer is not available'
2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 811 peerDictionary should become empty
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 812 failed with expected error
,ok 813 peer state should be RESOLVED
,# teardown
,2017-07-14 11:32:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-14 11:32:59 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 814 First action failed
,ok 815 second action killed
# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 816 secrets are equal
,ok 817 Public key matches with the server key
,ok 818 hostAddress must match
,ok 819 portNumber must match
,ok 820 suggestedTCPTimeout must match
,ok 821 connectionType must match
,# teardown
,2017-07-14 11:33:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 822 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 823 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 824 All entries should be expired after 1 second
# teardown
,2017-07-14 11:33:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 825 All keys need to be available in the cache
,ok 826 All entries should be expired after 1 second
# teardown
,2017-07-14 11:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 827 Size of the cache should be 2
,ok 828 Cache doesn't contain dictionary1
,ok 829 Size of the cache should be 1
ok 830 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-14 11:33:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 831 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 832 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 833 StartUpdateAdvertisingAndListening should not be called
,ok 834 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 835 no error
,ok 836 should be 204
,# teardown
,2017-07-14 11:33:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 837 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 838 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-14 11:33:08 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-14 11:33:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:33:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:33:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-14 11:34:08 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get same port when trying to connect multiple times on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-14 11:34:08 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Pass an empty parameter to ThaliNotificationServer.start, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/8059EFC0-1B4B,-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/blue,bird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-14 11:3,4:08 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-14 11:34:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:34:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:34:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:35:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:35:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:36:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:36:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:37:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:37:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:38:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:38:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:39:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:39:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:40:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:40:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:41:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:41:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:42:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:42:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:43:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:43:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:44:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:44:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:45:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:45:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:46:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:46:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-4,05A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-14 11:47:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405,A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-14 11:47:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/8059EFC0-1B4B-405A-A15E-0811F72F64A4/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
