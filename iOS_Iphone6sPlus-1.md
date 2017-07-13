#### Test 11335185196ab692_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1E88481B-F0A5-4076-99D8-B99D2E19CB65/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/1E88481B-F0A5-4076-99D8-B99D2E19CB65/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65288"
,(lldb)     command script import "/tmp/1E88481B-F0A5-4076-99D8-B99D2E19CB65/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
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
,2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:29:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5364C8BB-37C1-4A2F-96,EA-9BF45F2C5A5D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5364C8BB-37C1-4A2F-96EA-9BF45F2C5A5D
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D257F27C-8926-4779-8DDD-,CF2D5C69C7DC
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CB301AC2-D75F-4748-9330-2FB6C3D0EC5D
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE258152-0793-4283-BB73-47F3BC10DBD8", generation: 0)
[Tha,liCore] Advertiser.startAdvertising with peerID:DE258152-0793-4283-BB73-47F3BC10DBD8
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE258152-0793-4283-BB73-47F3BC10DBD8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE258152-0793-4283-BB73-47F3BC10DBD8", generation: 0)
AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvaila,bilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
2017-07-13 08:29:09 - DEBUG UnitTest_app: 'Running unit te,sts'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.577653050422668
,2017-07-13 08:29:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-13 08:29:09 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DE258152-0793-4283-BB73-47F3BC10DBD8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DE258152-0793-4283-BB73-47F3BC10DBD8", generation: 0)
,2017-07-13 08:29:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 08:29:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 08:29:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 08:29:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 08:29:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 08:29:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 08:29:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 08:29:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 08:29:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 08:29:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 08:29:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4,272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4,272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:29:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:29:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:29:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:29:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:29:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:30:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:30:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-427,2-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:50 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 08:31:50 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 08:31:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 08:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
2017-07-13 08:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-13 08:31:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-13 08:31:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-13 08:31:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 08:32:02 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:06 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C5B152C4-3AEF-41CD-A083-A303DFC2D4DC
[ThaliCore] Browser.startListening
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:07 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED6D615E-C869-43AE-8820-1DF2F834A2CE
[ThaliCore] Browser.startListening
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdver,tisements
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActiv,e":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAd,vertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13, 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:08 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:09 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3B237593-7FCE-4E39-965A-6115E14F87B6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3B237593-7FCE-4E39-965A-6115E14F87B6
,2017-07-13 08:32:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:32:10 - DEBUG thaliMobileNativeWrapper: 'discovery,AdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:15 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:15 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "479CD8B8-FFF7-494D-93F2-BB52D08A7A3C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:479CD8B8-FFF7-494D-93F2-BB52D08A7A3C
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "479CD8B8-FFF7-494D-93F2-BB52D08A7A3C", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:479CD8B8-FFF7-494D-93F2-BB52D08A7A3C
2017-07-13 0,8:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:17 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "969A76D8-9152-4B1C-BF24-DB21FB003157", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:969A76D8-9152-4B1C-BF24-DB21FB003157
2017-07-13 08:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 08:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:49692EF1-F5CB-449C-A757-94E0B9616310
[ThaliCore] Browser.startListening
2017-07-13 08:32:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
2017-07-13 08:32:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"route,r":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AEF459FD-A12E-4767-8E65-58B69FA8326B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AEF459FD-A12E-4767-8E65-58B69FA8326B", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:35 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BFAB98DA-9CF3-43B9-91FE-CA3032A13861
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:35, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F
[ThaliCore] Browser.startListening
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adve,r,tisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
2017-07-13 08:32:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","generation":0}'
2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 088A3ACD-ECCB-41AB-9B90-34BBEFC162A9, (syncValue: jazJsyLtzlFuKq5ozfuU9XuxvUjeDybi)'
2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:088A3ACD-ECCB-,4,1AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA
[ThaliCore] Advertiser: session connected Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
[ThaliCore] Session.disconnect() peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid,: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","generation":0}'
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","generation":0}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA
,[ThaliCore] Session.session(_:peer:didChange:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", genera,tion: 0)
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jazJsyLtzlFuKq5ozfuU9XuxvUjeDybi","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'jazJsyLtzlFuKq5ozfuU9XuxvUjeDybi', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2E49934-D5B4-44BA-830F-E06FF747D0D3 (syncValue: YezM0y9ezo9fqemiT3qkGPtJ5sgnJ2Tu)'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49449
,2017-07-13 08:32:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YezM0y9ezo9fqemiT3qkGPtJ5sgnJ2Tu","error":null,"portNumber":49449}'
,2017-07-13 08:32:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YezM0y9ezo9fqemiT3qkGPtJ5sgnJ2Tu', error: 'null', listeningPort: '49449''
,2017-07-13 08:32:45 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,2017-07-13 08:32:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:F2E49934-D5B4-,44BA-830F-E06FF747D0D3
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49449
[ThaliCore] Session.disconnect() peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: ",F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:542410F8-E47D-4D09-9B3D-AB8970C059FA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:542410F8-E47D-4D09-9B3D-AB8970C059FA
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.deinit peer:542410F8-E47D-4D09-9B3D-AB8970C059FA
,2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:32:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:32:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E
2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:48, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AE4A6AC6-7D4D-4E38-A079-A38EAAF9B9D7
[ThaliCore] Browser.startListening
2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-13 08:32:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
2017-07-13 08:32:48 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
2017-07,-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9687EBC4-01F9-4F14-9B77-F38A65897F0D (syncValue: KKubLbiQpqcKAnMZm4SMuKYkRtlXOA5g)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D,3", generation: 0)
2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(wit,h:socketDisconnected:stoppedListening:)
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
2017-07-13 08:32:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
2017-07-13 08:32:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0D279F4F-B96C-44A0-AAFA-099C9029E9D0","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", genera,tion: 0)
2017-07-13 08:32:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KKubLbiQpqcKAnMZm4SMuKYkRtlXOA5g","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:53 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'KKubLbiQpqcKAnMZm4SMuKYkRtlXOA5g', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:32:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:53 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2E49934-D5B4-44BA-830F-E06FF747D0D3 (syncValue: aw8J7nz,TKbV6FhwkJU3bcbTgthgSjHAS)'
2017-07-13 08:32:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", genera,tion: 0)
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"aw8J7nzTKbV6FhwkJU3bcbTgthgSjHAS","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'aw8J7nzTKbV6FhwkJU3bcbTgthgSjHAS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61756926-9537-4B4F-AF8E-72C7D7AF849C (syncValue: XRvoss9vaGVuQrRrMnY2AiQGTynn7DCl)'
,2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49458
2017-07-13 08:33:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XRvoss9vaGVuQrRrMnY2AiQGTynn7DCl",,"error":null,"portNumber":49458}'
2017-07-13 08:33:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XRvoss9vaGVuQrRrMnY2AiQGTynn7DCl', error: 'null', listeningPort: '49458''
,Connecting to the localhost:49458
,Connected to the localhost:49458
2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCor,e] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
,# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,2017-07-13 08:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:61756926-9537-4B4F-AF8E-72C7D7AF849C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49458
[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,# setup
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:08B6D133-C3D4-4338-B019-A18C4389675A
2017-07-13 0,8:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
[Tha,l,iCore] Browser.startListening
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:03 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
2017-07-13 08:33:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","generation":0}'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61756926-9537-4B4F-AF8E-72C7D7AF849C, (syncValue: cQVrwpdJhEHxjlMOdoF3JkPhgJuvSbYL)'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61756926-9537-,4,B4F-AF8E-72C7D7AF849C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
2017-07-13 08:33:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CBE4BA45-6080-444B-B5A9-545B9189CA71","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", genera,tion: 0)
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cQVrwpdJhEHxjlMOdoF3JkPhgJuvSbYL","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'cQVrwpdJhEHxjlMOdoF3JkPhgJuvSbYL', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F2E49934-D5B4-44BA-830F-E06FF747D0D3 (syncValue: QaETZDU,ZOVnCBJHRgg0YmhYO8szLc3sE)'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D,3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Session.disconnect() peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", genera,tion: 0)
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QaETZDUZOVnCBJHRgg0YmhYO8szLc3sE","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'QaETZDUZOVnCBJHRgg0YmhYO8szLc3sE', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F2E49934-D5B4-44BA-830F-E06FF747D0D3","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A385ACA9-6BE4-4961-9C6A-7F8665F19C7C (syncValue: Hb01R0T,WJEiHj2YnLdcZMofcpGHtbAvb)'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49469
,2017-07-13 08:33:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Hb01R0TWJEiHj2YnLdcZMofcpGHtbAvb","error":null,"portNumber":49469}'
,2017-07-13 08:33:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Hb01R0TWJEiHj2YnLdcZMofcpGHtbAvb', error: 'null', listeningPort: '49469''
,Connecting to the localhost:49469
,Connecting to the localhost:49469
Connecting to the localhost:49469
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewS,ocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
Connected to the localhost:49469
Connected to the localhost:49469
Connected to the localhost:49469
,ok 109 correct string length
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-13 08:33:18 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,ok 112 got the same data back
,ok 113 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStream,s() vsID:3
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,ok 114 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 []
,# teardown
,2017-07-13 08:33:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:A385ACA9-6BE4-,4961-9C6A-7F8665F19C7C
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49469
[ThaliCore] Session.disconnect() peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCor,e] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: ",A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,# setup
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C8344525-57A7-4C58-8528-26E881A5D49E
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D68BB73-BB6B-477C-879F-EB909ABD2B12
[ThaliCore] Browser.startListening
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
2017-07-13 08:33:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","generation":0}'
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A385ACA9-6BE4-4961-9C6A-7F8665F19C7C, (syncValue: tftFvbF8fQBZpefIU9Dz3q2IGFSvJ2qq)'
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A385ACA9-6BE4-,4,961-9C6A-7F8665F19C7C:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"CBE4BA45-6080-444B-B5A9-545B9189CA71","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
2017-07-13 08:33:23 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"B4E6B4EA-B9F7-47DE-AB46-1F466A373B26","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4804A3A0-BF11-4E49-9818-17B476E274EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4804A3A0-BF11-4E49-9818-17B476E274EF", generation: 0)
2017-07-13 08:33:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4804A3A0-BF11-4E49-9818-17B476E274EF","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", genera,tion: 0)
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tftFvbF8fQBZpefIU9Dz3q2IGFSvJ2qq","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'tftFvbF8fQBZpefIU9Dz3q2IGFSvJ2qq', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"A385ACA9-6BE4-4961-9C6A-7F8665F19C7C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4E6B4EA-B9F7-47DE-AB46-1F466A373B26 (syncValue: TFikNRn,55ayvqRiVCU4L78PQqIvlCOwl)'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B2,6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541
[ThaliCore] Advertiser: session connected Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
[ThaliCore] Advertiser: session connected Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
,[ThaliCore] Session.session(_:peer:didChange:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
[ThaliCore] Session.startOutputStream(with:) peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-13 08:33:30 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:5
[ThaliCore] VirtualSocket.closeSt,reams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 []
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49481
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TFikNRn55ayvqRiVCU4L78PQqIvlCOwl","error":null,"portNumber":49481}'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TFikNRn55ayvqRiVCU4L78PQqIvlCOwl', error: 'null', listeningPort: '49481''
,Connecting to the localhost:49481
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541
,Connected to the localhost:49481
2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541 state: connecting -> connected
,ok 119 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 []
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541
[ThaliCore] Session.startOutputStream(with:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-13 08:33:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConne,ctionsAndDisconnectClients() port:49481
[ThaliCore] Session.disconnect() peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
[ThaliCore] Sessio,n.deinit peer:153DC3B8-63CF-4A5A-8EE8-E019C23F5C8C
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
[ThaliCore] Browser.startListening
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
2017-07-13 08:33:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4E6B4EA-B9F7-47DE-AB46-1F466A373B26","generation":0}'
2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B4E6B4EA-B9F7-47DE-AB46-1F466A373B26, (syncValue: YYgITRi4WwBPFZt110a0Oy3bwrYCLv8r)'
2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
2017-07-13 08:33:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADF8C929-C7FF-40EC-A17B-BF06E75C0D00","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
2017-07-13 08:33:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", genera,tion: 0)
2017-07-13 08:33:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YYgITRi4WwBPFZt110a0Oy3bwrYCLv8r","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:38 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'YYgITRi4WwBPFZt110a0Oy3bwrYCLv8r', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"B4E6B4EA-B9F7-47DE-AB46-1F466A373B26","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:33:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B4E6B4EA-B9F7-47DE-AB46-1F466A373B26","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:38 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADF8C929-C7FF-40EC-A17B-BF06E75C0D00 (syncValue: pNdX923,Ub99GjRA5jSBExsFsoheQHiEU)'
2017-07-13 08:33:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D0,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7476D46-4931-40D9-9792-45128C802C97
[ThaliCore] Advertiser: session connected Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B7476D46-4931-40D9-9792-45128C802C97 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
[ThaliCore] Advertiser: session connected Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7476D46-4931-40D9-9792-45128C802C97
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7476D46-4931-40D9-9792-45128C802C97 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7476D46-4931-40D9-9792-45128C802C97
[ThaliCore] Session.startOutputStream(with:) peer:B7476D46-4931-40D9-9792-45128C802C97
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (4593 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (7310 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (29707 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received (2239 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49493
2017-07-13 08:33:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pNdX923Ub99GjRA5jSBExsFsoheQHiEU",,"error":null,"portNumber":49493}'
2017-07-13 08:33:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pNdX923Ub99GjRA5jSBExsFsoheQHiEU', error: 'null', listeningPort: '49493''
,Connecting to the localhost:49493
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
Connected to the localhost:49493
2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [7, 8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [7, 8]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
,[ThaliCore] Session.session(_:peer:didChange:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
[ThaliCore] Session.startOutputStream(with:) peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [7, 8, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (3143 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (3427 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (6570 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [7, 8]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:33:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdv,ertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:44 - INFO thaliMobile: 'Filtered out ,discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00
[ThaliCore] BrowserRelay.closeRelay() disconne,cting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49493
[ThaliCore] Session.disconnect() peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7476D46-4931-40D9-9792-45128C802C97 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
[ThaliCore] Sessio,n.deinit peer:A238DAC4-F410-488E-BDDF-B0C8DE16D905
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DF9AE386-BF7F-41BF-91B5-E89FF24309DF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DF9AE386-BF7F-41BF-91B5-E89FF24309DF
2017-07-13 0,8:33:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 127 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42413689-3752-4EEA-BBBE-EDFF2EDCE30F
[ThaliCore] Browser.startListening
2017-07,-,13 08:33:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:33:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE67C612-B683-44B5-99A0-83F49848650A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising,()
2017-07-13 08:33:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-13 08:33:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":fals,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:50 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-13 08:33:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:51 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:452C0FA4-B6CA-47CB-9486-4192798A6F76
[ThaliCore] Browser.startListening
ok 135 discoveryActive should be false
ok 136 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "024123C2-1C55-4ACF-9CD5-141D2EE9D0F4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:024123C2-1C55-4ACF-9CD5-141D,2EE9D0F4
ok 137 discoveryActive should be false
ok 138 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 139 discoveryActive should be false
ok 140 advertisingActive sh,ould be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
ok 141 discoveryActive should be false
ok 142 advertisingActive should be true
ok 143 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-13 08:33:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 08:33:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:9e80d0fa-97d1-4562-8f85-acd30d6d6fbd error: startListeningNotActive
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValu,e":"Iybv25u78RLbWE2om9dlizDcKLZflW04","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 159 Should only get called after multiConnect returned
ok 160 SyncValue matches
ok 161 Got right error
ok 162 listeningPort is null
20,17-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9e80d0fa-97d1-4562-8f85-acd30d6d6fbd","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:55 - DEBUG thaliMobileN,ativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9e80d0fa-97d1-4562-8f85-acd30d6d6fbd,",,"peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 163 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BE0C7B4D-984C-4C83-B624-AFA62782CDF2
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 165 No error on starting
,ok 166 Got null as expected
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qwKLYpS6wfgWZV8sP1jEMDRVcsOhe0nC","error":"Illegal peerID","portNumber":null}'
,ok 167 Should only get called after multiConnect returned
,ok 168 SyncValue matches
,ok 169 Got right error
,ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16FD1141-1620-42B5-B00F-8C15AEC91187
[ThaliCore] Browser.startListening
2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 No error on starting
,ok 174 Got null as expected
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZRjpsHhCCilLqY0YyKyV8g41lq4bXHO3","error":"Peer is unavailable","portNumber":null}'
,ok 175 Should only get called after multiConnect returned
,ok 176 SyncValue matches
,not ok 177 Got right error
  ---
    operator: equal
    expected: 'Connection could not be established'
    actual:   'Peer is unavailable'
  ...
ok 178 listeningPort is null
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7f5c9577-cff5-4188-ab33-f1205e6b8f82","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"7f5c9577-cff5-4188-ab33-f1205e6b8f82","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'CoordinatedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/729135D6-557C,-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:56,7:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromi,ses@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-07-13 08:33:56 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios','
,# teardown
,2017-07-13 08:33:56 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
2017-07-13 08:34:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}]'
2017-07-13 08:34:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
2017-07-13 08:34:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
2017-07-13 08:34:01 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}]'
2017-07-13 08:34:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
2017-07-13 08:34:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:36:42 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 08:36:42 - DEBUG CoordinatedClient: 'test client failed'
2017-07-13 08:36:42 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiC,onnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978,f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/729135D6,-,557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Applic,ation/729135D6-557C-4272-A66E-0A1D7DBAE5C9/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-13 08:36:42 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
