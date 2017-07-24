#### Test 12719871034799d6_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/FF35926C-82FB-43DE-9E4E-01B4D8D5A119/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/FF35926C-82FB-43DE-9E4E-01B4D8D5A119/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53849"
,(lldb)     command script import "/tmp/FF35926C-82FB-43DE-9E4E-01B4D8D5A119/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
JXcore engine is started
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:01:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D54DEB70-5D95-4C75-9885-03777FB2A1EA", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D54DEB70-5D95-4C75-9885-03777FB2A1EA
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:60EB4489-88F3-4C08-9FB1-A5B3A3E0F248
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:687728F1-,2AE4-4B60-AFD6-A748DED5AC06
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9ABC643D-F348-4618-B673-6091EB2A7406", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9ABC643D-F348-4618-B673-6091EB2A7406
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ABC643D-F348-4618-B673-6091EB2A7406:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ABC643D-F348-4618-B673-6091EB2A7406", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
2017-07-24 11:01:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignor,ed tests:  0
,Total duration:  1.532794058322906
,2017-07-24 11:01:03 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-24 11:01:03 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9ABC643D-F348-4618-B673-6091EB2A7406:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9ABC643D-F348-4618-B673-6091EB2A7406", generation: 0)
,2017-07-24 11:01:06 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 11:01:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 11:01:06 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 11:01:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 11:01:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 11:01:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 11:01:10 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 11:01:10 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 11:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:53 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-24 11:01:53 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 11:01:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-24 11:02:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 11:02:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-24 11:02:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-24 11:02:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-24 11:02:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-24 11:02:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-24 11:02:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-24 11:02:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-24 11:02:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-24 11:02:19 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-24 11:02:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 11:02:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E382E901-C8A0-4641-8A4F-35C54F1DF0DC
[ThaliCore] Browser.startListening
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:15C7201E-507A-47D5-B6F9-B55AF82E5E4E
[ThaliCore] Browser.startListening
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "557E463A-68E1-4AA8-84EC-D7EE13024627", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:557E463A-68E1-4AA8-84EC-D7EE13024627
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:26, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:557E463A-68E1-4AA8-84EC-D7EE13024627
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:26 - INFO thaliMobile,: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8E0EADC-03C8-4DF7-AC3E-31911DDD440A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A8E0EADC-03C8-4DF7-AC3E-31911DDD440A
2017-07-24 1,1:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8E0EADC-03C8-4DF7-AC3E-31911DDD440A", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:A8E0EADC-03C8-4DF7-AC3E-31911DDD440A
,2017-07-24 11:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A8E0EADC-03C8-4DF7-AC3E-31911DDD440A
[ThaliCore] Advertiser.stopAdvertising() peerID:A8E0EADC-03C8-4DF7-AC3E-31911DDD440A,
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B
2017-07-24 1,1:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:50B4F2B6-BBC6-41F9-ACAE-103AD6D17993
,[ThaliCore] Browser.startListening
2017-07-24 11:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9699B0E1-44B9-482F-A4AC-FD3E9344992A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9699B0E1-44B9-482F-A4AC-FD3E9344992A", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) f,ound peer:489BD2DA-ED40-4C42-A931-8C514A214BF5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "489BD2DA-ED40-4C42-A931-8C514A214BF5", generation: 0)
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FD1166F3-65E0-4A9D-9015-16F0811DA565
,2017-07-24 11:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:44385B8E-CCD5-46CA-A26D-618FC8342DC1
,[ThaliCore] Browser.startListening
,2017-07-24 11:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
2017-07-24 11:02:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","generation":0}'
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01BFBF0D-498C-4989-932F-2BFF5B82FD2A, (syncValue: MDR0l9CM9F5wLmkTrOed3n4TAlcLk4bS)'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01,BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3
[ThaliCore] Advert,iser: session connected Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6FB004D3-5820,-42BE-8A1C-23C107D2FEA3 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381B7A74-7122-4015-A89E-4B737500991B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"381B7A74-7122-4015-A89E-4B737500991B","generation":0}'
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61204
,2017-07-24 11:02:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"MDR0l9CM9F5wLmkTrOed3n4TAlcLk4bS","error":null,"portNumber":61204}'
,2017-07-24 11:02:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'MDR0l9CM9F5wLmkTrOed3n4TAlcLk4bS', error: 'null', listeningPort: '61204''
,2017-07-24 11:02:38 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3
,[ThaliCore] Session.session(_:peer:didChange:) peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3 state: connecting -> connected
,2017-07-24 11:02:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:02:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FD1166F3-65E0-4A9D-9015-16F0811DA565
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61204
[ThaliCore] Session.disconnect() p,eer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Session.session(_:peer:didChange:) peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:6FB004D3-5820-42BE-8A1C-23C107D2FEA3
[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCha,nged registered to native'
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native',
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6
2017-07-24 1,1:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:19E8B9BE-AE9D-4FFF-923D-133A5A914DE0
[Thal,i,Core] Browser.startListening
2017-07-24 11:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","generation":0}'
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01BFBF0D-498C-4989-932F-2BFF5B82FD2A (syncValue: ipgTJo2P2pr7aNPMQxyxOGE4cf51AvDc)'
,2017-07-24 11:02:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
2017-07-24 11:02:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","generation":0}'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","generation":0}'
,2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,1BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,1BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D
[ThaliCore] Advertiser: session connected Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:01BFBF0D,-498C-4989-932F-2BFF5B82FD2A error: max retries exceeded
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ipgTJo2P2pr7aNPMQxyxOGE4cf51AvDc","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ipgTJo2P2pr7aNPMQxyxOGE4cf51AvDc', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:02:55 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2,A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:02:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E2A40D56-96CA-4D8D-8F53-D4CC01876154 (syncValue: jSwwYMz,Y9YD0MBtXWqXJnyiUzxpHIQtj)'
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
[ThaliCore] Advertiser: session connected Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D
,[ThaliCore] Session.session(_:peer:didChange:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D
[ThaliCore] Session.startOutputStream(with:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61213
,2017-07-24 11:02:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jSwwYMzY9YD0MBtXWqXJnyiUzxpHIQtj","error":null,"portNumber":61213}'
,2017-07-24 11:02:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jSwwYMzY9YD0MBtXWqXJnyiUzxpHIQtj', error: 'null', listeningPort: '61213''
,Connecting to the localhost:61213
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
,Connected to the localhost:61213
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312 state: connecting -> connected
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
,[ThaliCore] Session.startOutputStream(with:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,# teardown
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 11:02:58 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:02:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61213
[ThaliCore] Session.disconnect() p,eer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:A448B215-5A97-4EB5-B3F8-D3AC2616C312
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] Browser.startListening
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","generation":0}'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5ACAF211-0772-4AB0-B392-E6D7695E2A89 (syncValue: cak7KW2RCVbqLEuZtHpO2EoFsKHqdzff)'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","generation":0}'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
2017-07-24 11:03:01 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","generation":0}'
,2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15F8FDF1-E29F-4B1B-AFBA,-A337ECE93BE3:0
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93B,E3","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,CAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,CAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,CAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:5A,CAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5ACAF211,-0772-4AB0-B392-E6D7695E2A89 error: max retries exceeded
2017-07-24 11:03:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cak7KW2RCVbqLEuZtHpO2EoFsKHqdzff","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cak7KW2RCVbqLEuZtHpO2EoFsKHqdzff', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:03:11 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 11:03:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5ACAF211-0772-4AB0-B392-E6D7695E2A89","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:03:11 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:03:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7A64547-3C92-4AEA-B913-F34E280DDD7C (syncValue: XmPr9II,3Vre7PHVjnSgr4Nhxr15VLq8W)'
2017-07-24 11:03:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7A64547-3C92,-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61230
2017-07-24 11:03:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XmPr9II3Vre7PHVjnSgr4Nhxr15VLq8W",,"error":null,"portNumber":61230}'
,2017-07-24 11:03:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XmPr9II3Vre7PHVjnSgr4Nhxr15VLq8W', error: 'null', listeningPort: '61230''
,Connecting to the localhost:61230
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,Connecting to the localhost:61230
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,Connecting to the localhost:61230
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61230
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61230
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
,Connected to the localhost:61230
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,ok 91 correct string length
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:6 []
,ok 96 got the same data back
,# teardown
,2017-07-24 11:03:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:03:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8DB5C8CF-9F6C-4FCE-AE67-3,1A370211A57
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61230
[ThaliCore] Session.disconnect() peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F591386-896D-46D9-B7FC-0F4D50F2F645
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5
[ThaliCore] Browser.startListening
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
2017-07-24 11:03:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","generation":0}'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B7A64547-3C92-4AEA-B913-F34E280DDD7C, (syncValue: EmQaGoueJLU5Q8BnmGh24xa0nWB6JUJW)'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280,DDD7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
2017-07-24 11:03:18, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3","generation":0}'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADD0124E-485B-4CBD-9E05-99F82050A2E9","generation":0}'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EmQaGoueJLU5Q8BnmGh24xa0nWB6JUJW","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EmQaGoueJLU5Q8BnmGh24xa0nWB6JUJW', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B7A64547-3C92-4AEA-B913-F34E280DDD7C","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2BDCF5F5-8C04-4171-800A-A898BAF20B04 (syncValue: XIIfFWkIzxEdcyrYwjiEK3D1zIqQCQl5)'
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61247
,2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XIIfFWkIzxEdcyrYwjiEK3D1zIqQCQl5","error":null,"portNumber":61247}'
,2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XIIfFWkIzxEdcyrYwjiEK3D1zIqQCQl5', error: 'null', listeningPort: '61247''
,Connecting to the localhost:61247
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61247
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 []
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,2017-07-24 11:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:3F591386-896D-46D9-B7FC-0F4D50F2F645
2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:,03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61247
[ThaliCore] Session.disconnect() p,eer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FA2EE142-1A99-4149-AB82-FAA6044948AC
,2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4448EFB5-325D-4402-9F4B-B3F19AE2501B
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
2017-07-24 11:03:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2BDCF5F5-8C04-4171-800A-A898BAF20B04, (syncValue: gDbnwITY8DzCEmCFIKKSyl7YbP0KMYSc)'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF,20B04", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] Browser,.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTes,tUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADD0124E-485B-4CBD-9E05-99F82050A2E9","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,DCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,DCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,DCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633
[ThaliCore] Advertiser: session connected Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,DCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2BDCF5F5,-8C04-4171-800A-A898BAF20B04 error: max retries exceeded
2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gDbnwITY8DzCEmCFIKKSyl7YbP0KMYSc","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gDbnwITY8DzCEmCFIKKSyl7YbP0KMYSc', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2BDCF5F5-8C04-4171-800A-A898BAF20B04","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4F5F622-E47B-4CE5-B8AE-21666B67C798 (syncValue: JxhXq7JhGHzIiynHoJiW0RYEVQwlYIFW)'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633
,[ThaliCore] Session.session(_:peer:didChange:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633
,[ThaliCore] Session.startOutputStream(with:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (5404 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (4309 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received (3192 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61264
,2017-07-24 11:03:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JxhXq7JhGHzIiynHoJiW0RYEVQwlYIFW","error":null,"portNumber":61264}'
,2017-07-24 11:03:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'JxhXq7JhGHzIiynHoJiW0RYEVQwlYIFW', error: 'null', listeningPort: '61264''
,Connecting to the localhost:61264
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,Connected to the localhost:61264
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [8, 9]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 11:03:47 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [8]
,ok 102 got the same data back
,# teardown
,2017-07-24 11:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:FA2EE142-1A99-4149-AB82-FAA6044948AC
2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:,03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61264
[ThaliCore] Session.disconnect() p,eer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F401DB5D-F313-4E69-812E-4D05F31E1633 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F401DB5D-F313-4E69-812E-4D05F31E1633
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:F401DB5D-F313-4E69-812E-4D05F31E1633
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JxhXq7JhGHzIiynHoJiW0RYEVQwlYIFW","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:96D295B9-A679-4845-81F4-6679D5422962
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:03:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BD9D579D-72C6-46B0-B79B-4E6BA3F58861
,2017-07-24 11:03:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:03:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:03:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
2017-07-24 11:03:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}]'
2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"12089FF0-3ECC-40A2-A184-6C264C0E4B6C","generation":0}'
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[Thali,Core] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdenti,fier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}]'
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F3344D9-A0D8-45F0-B5ED-690876F8EF43:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F3344D9-A0D8-45F0-B5ED-690876F8EF43", generation: 0)
2017-07-24 11:03:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5F3344D9-A0D8-45F0-B5ED-690876F8EF43","generation":0}]'
2017-07-24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5F3344D9-A0D8-45F0-B5ED-690876F8EF43","generation":0}'
2017-07-24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:55 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BD9D579D-72C6-46B0-B79B-4E6BA3F58861
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWra,pper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:55 - DEBUG thaliMobileNati,v,eWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-24 11:03:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6FA0D312-B900-4E7A-9A29-C40FFA42EC42
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingA,ctive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1360ED1-F74B-4D26-BB83-9014BD57B72A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C1360ED1-F74B-4D26-BB83-9014,BD57B72A
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1360ED1-F74B-4D26-BB83-9014BD57B72A
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 11:03:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-24 11:03:56 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 11:03:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-24 11:03:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-24 11:03:58 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9f919a95-b9b6-4886-9464-bbc3234b689b error: startListeningNotActive
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"aAFR2biFL5Y3chIwbQr58ecpmDMSETYU","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9f919a95-b9b6-4886-9464-bbc3234b689b","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:58 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9f919a95-b9b6-4886-9464-bbc3234b689,b","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:96758EBA-9116-49D7-944A-D5028CE3EB85
[ThaliCore] Browser.startListening
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"i2Ka3ozsnaONdk9QQMPnbFtnZTQWRZTv","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-24 11:03:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:923E9648-4480-4134-9238-1312EC09B71B
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}]'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24, 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:11503383-b9f4-4c23-89b9-166685e51b0f
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5837337D-36B1-4BEE-A7F0-8A59B6E8E759
2017-07-24 1,1:04:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69714A12-7853-4890-86EC-F14734D64C88
[ThaliCore] Browser.startListening
2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:04:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4F5F622-E47B-4CE5-B8AE-21666B67C798 (syncValue: j4cuDYtZBMGh8GpUdbEBpSuYjtBGLFKQ)'
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","generation":0}'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"63BAE976-BEB5-4F9C-9652-5FC045F4AD23","generation":0}'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:04:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"j4cuDYtZBMGh8GpUdbEBpSuYjtBGLFKQ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:04:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'j4cuDYtZBMGh8GpUdbEBpSuYjtBGLFKQ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:04:06 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:04:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:04:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 11:04:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:04:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C923BA5-B7BD-4950-A19A-1BFD7C7541D1 (syncValue: RkwBRE7mmmWU5CbEa5qEXrw,QITbRb0v0)'
2017-07-24 11:04:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C923BA5-B7BD-4950-A19A-1BFD7,C7541D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE
[ThaliCore] Advertiser: session connected Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: connecting -> connected
[ThaliCore] Session.session(_:peer:didChange:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE state: connecting -> connected
[ThaliCore] ,Browser: session connected to Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61276
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RkwBRE7mmmWU5CbEa5qEXrwQITbRb0v0","error":null,"portNumber":61276}'
2017-07-24 11:04:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'RkwBRE7mmmWU5CbEa5qEXrwQITbRb0v0', error: 'null', listeningPort: '61276''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) found active relay
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hNjd3DSV8Na08doB3Q2hVgPO7WNQSOYf","error":null,"portNumber":61276}'
,ok 144 No error
,ok 145 Ports equal
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE
[ThaliCore] Session.startOutputStream(with:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,0 [8, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) found active relay
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6KFNHl9jlrEocsJrYaQRJjoRLSPK6oIU","error":null,"portNumber":61276}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [8, 10, 11]
,ok 147 No error
,ok 148 Ports equal
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:72295678-8011-4539-889C-0FE1169457D4
[ThaliCore] Advertiser: session connected Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:72295678-8011-4539-889C-0FE1169457D4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:72295678-8011-4539-889C-0FE1169457D4
,[ThaliCore] Session.session(_:peer:didChange:) peer:72295678-8011-4539-889C-0FE1169457D4 state: connecting -> connected
,2017-07-24 11:04:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5837337D-36B1-4BEE-A7F0-8A59B6E8E759
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61276
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [8, 11]
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:11 [8]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RkwBRE7mmmWU5CbEa5qEXrwQITbRb0v0","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:72295678-8011-4539-889C-0FE1169457D4
,[ThaliCore] Session.deinit peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:72295678-8011-4539-889C-0FE1169457D4
,[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-24 11:04:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-24 11:04:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-24 11:04:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-24 11:04:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 61280'
ok 149 Should throw
,# teardown
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 61282'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 61285'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 61289'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 61294'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 61298'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 61302'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 61306'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'listening 61310'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-24 11:04:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 11:04:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:35 - DEBUG createNativeListener: 'listening 61362'
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'listening 61366'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 61369'
ok 196 port must be in range
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 61370'
ok 197 second start should return same port
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 61372'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 11:04:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-24 11:04:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-24 11:04:37 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61374
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:04:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24, 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:91033B82-7A22-4EE1-8C6F-0D07A8443692
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
,[ThaliCore] Browser.startListening
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
2017-07-24 11:04:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6C923BA5-B7BD-4950-A19A-1BFD7C7541D1 (syncValue: PVcgmmKoU4ijKVZYl46BduclYP6djfW2)'
2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C,923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"63BAE976-BEB5-4F9C-9652-5FC045F4AD23","generation":0}'
2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
[ThaliCore] Advertiser: session connected Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6C,923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PVcgmmKoU4ijKVZYl46BduclYP6djfW2","error":"Peer is unavailable","portNumber":null}'
2017-07-24 11:04:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PVcgmmKoU4ijKVZYl46BduclYP6djfW2', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6C923BA5-B7BD-4950-A19A-1BFD7C7541D1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E (syncValue: vSXebUvqjAV6sg3tnhREg5dCwbCgWIva)'
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
,[ThaliCore] Session.session(_:peer:didChange:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61386
2017-07-24 11:04:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vSXebUvqjAV6sg3tnhREg5dCwbCgWIva","error":null,"portN,umber":61386}'
,2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vSXebUvqjAV6sg3tnhREg5dCwbCgWIva', error: 'null', listeningPort: '61386''
,ok 210 should be equal
,2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 750E6DFD-0414-4611-9C4A-7D7FD6C84C77 (syncValue: jNNH1BwgDpCfUNLxdjuMK97tHq0TUddE)'
,2017-07-24 11:04:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
[ThaliCore] Advertiser: session connected Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61389
,2017-07-24 11:04:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jNNH1BwgDpCfUNLxdjuMK97tHq0TUddE","error":null,"portNumber":61389}'
,2017-07-24 11:04:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jNNH1BwgDpCfUNLxdjuMK97tHq0TUddE', error: 'null', listeningPort: '61389''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:04:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:91033B82-7A22-4EE1-8C6F-0,D07A8443692
2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61386
[ThaliCore] Session.disconnect() p,eer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61389
,[ThaliCore] Session.disconnect() peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] Adve,rtiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
,[ThaliCore] Session.session(_:peer:didChange:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Advertise,rRelay.deinit
,[ThaliCore] Session.deinit peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:04:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,[ThaliCore] Session.deinit peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 61391
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:04:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24, 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:07DC7689-843B-41FF-8F84-A0AFB584488F
2017-07-24 1,1:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
[ThaliCore] Browser.startListening
2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
2017-07-24 11:04:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","generation":0}'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E, (syncValue: CARJgjslhaga4D5zH46WnF3QqhodDBOk)'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2,D6B9E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPLis,tener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","generation":0}'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
2017-07-24 11:04:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
20,17-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9E,CDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9E,CDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9E,CDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9E,CDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9ECDB81E,-7A35-4DA6-9B91-7CA4FB2D6B9E error: max retries exceeded
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CARJgjslhaga4D5zH46WnF3QqhodDBOk","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CARJgjslhaga4D5zH46WnF3QqhodDBOk', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D2BCE3C4-528F-472A-A98F-01BEF298D54C (syncValue: l0X827p,xlCd9WfrOdA5VzdyKu5f9srr5)'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2BCE3C4-528F,-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015
[ThaliCore] Advertiser: session connected Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61409
2017-07-24 11:05:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l0X827pxlCd9WfrOdA5VzdyKu5f9srr5","error":null,"portNumber":61409}'
2017-07-24 11:05:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l0X827pxlCd9WfrOdA5VzdyKu5f9srr5', error: 'null', listeningPort: '61409''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-24 11:05:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1DE2F08-A697-4531-80C7-AC50F60F4088 (syncValue: bgY80djcp9YDHLHSopkZcpEmrdLJHyWl)'
,2017-07-24 11:05:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61415
2017-07-24 11:05:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bgY80djcp9YDHLHSopkZcpEmrdLJHyWl",,"error":null,"portNumber":61415}'
2017-07-24 11:05:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bgY80djcp9YDHLHSopkZcpEmrdLJHyWl', error: 'null', listeningPort: '61415''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[ThaliCore] Advertiser: session connected Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:07DC7689-843B-41FF-8F84-A0AFB584488F
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C,
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61409
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:C1DE2F08-A697-4531-80C7-AC50F60F4088
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61415
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,2017-07-24 11:05:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[ThaliCore] Advert,iserRelay.deinit
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l0X827pxlCd9WfrOdA5VzdyKu5f9srr5","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bgY80djcp9YDHLHSopkZcpEmrdLJHyWl","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,[ThaliCore] Session.deinit peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'listening 61419'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 61420'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:278F7588-4913-4A17-BDCC-B7FB1FD4CD86
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 61421'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "990A28FF-BF43-4E65-99F9-FB6C1EB1F4AD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:990A28FF-BF43-4E65-99F9-FB6C1EB1F4AD
2017-07-24 1,1:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "990A28FF-BF43-4E65-99F9-FB6C1EB1F4AD", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:990A28F,F,-BF43-4E65-99F9-FB6C1EB1F4AD
2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:990A28FF-BF43-4E65-99F9-FB6C1EB1F4AD
,[ThaliCore] Advertiser.stopAdvertising() peerID:990A28FF-BF43-4E65-99F9-FB6C1EB1F4AD
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'listening 61424'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 236 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 11:05:27 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 61425'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A594D16E-4E88-4A3D-9AD1-3B068127A73C
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4BD8D8F8-16C2-4D76-9378-1F148D1BF0A7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4BD8D8F8-16C2-4D76-9378-1F148D1BF0A7
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4BD8D8F8-16C2-4D76-9378-1F148D1BF0A7
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:05:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 61428'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E49A845D-3780-41B9-A2D4-072BD9A23395
,[ThaliCore] Browser.startListening
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActiv,e":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D24BA5C9-FC37-4E70-9DEE-1625B6E74C0F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D24BA5C9-FC37-4E70-9DEE-1625B6E74C0F
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D24BA5C9-FC37-4E70-9DEE-1625B6E74C0F
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'listening 61430'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4EF01006-E646-499C-AFDA-D55B63A70008
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3B2D57AE-FFE0-4420-BE12-14202C931CDE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3B2D57AE-FFE0-4420-BE12-14202C931CDE
2017-07-24 1,1:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match ,with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3B2D57AE-FFE0-4420-BE12-14202C931CDE
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-24 11:05:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-24 11:05:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-24 11:05:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-24 11:05:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-24 11:05:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-24 11:05:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-24 11:05:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 61433'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9C489210-E1FC-48C9-9CE1-775FE8D2A9C7
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:05:34 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 61434'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AFE41CD7-4FA2-43B9-8724-0B487F659B41", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AFE41CD7-4FA2-43B9-8724-0B487F659B41
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:AFE41CD7-4FA2-43B9-8724-0B487F659B41
2017-07-24 11:05:34, - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 61436'
,# teardown
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}]'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 61437'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1562CA3A-5969-4183-94A5-A38AF04FE7AD
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:21C76FB1-27B2-410D-9F47-FB2CAE986934
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}]'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}]'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:34 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
2017-07-24 11:05:35 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}]'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:21C76FB1-27B2-410D-9F47-FB2CAE986934
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-07-24 11:05:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'listening 61439'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A24BFF38-9898-41C6-87EB-9ADA562612FE
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D2BCE3C4-528F-472A-A98F-01BEF298D54C (syncValue: KvazEQNQKTSyU5yaE9wInQnIEUjTtO6W)'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"BF2,6BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","generatio,n[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
":0}]'
[ThaliCore] Browser.,browser(_:foundPeer:withDiscoveryInfo:) found peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"86C127E7-58B5-42BA-8ABA,-1587918D0BF8","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'Rece,ived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86C127E7-58B5-42BA-8ABA-1587918D0BF8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2,BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2,BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from n,ative layer [{"peerAvailable":false,"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","generation":0}]'
2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"D2B,CE3C4-528F-472A-A98F-01BEF298D54C","generation":0}'
2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generatio,n":0}]'
2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:05:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:05:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D2,BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"KvazEQNQKTSyU5yaE9wInQnIEUjTtO6W","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'KvazEQNQKTSyU5yaE9wInQnIEUjTtO6W', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"D2BCE3C4-528F-472A-A98F-01BEF298D54C","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C
,2017-07-24 11:05:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 687F0B91-75C2-4D17-A950-AE8032F5F447 (syncValue: FMO250qlS2FtJV2OS6IghC5DmX1Tq1nb)'
,2017-07-24 11:05:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61449
2017-07-24 11:05:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FMO250qlS2FtJV2OS6IghC5DmX1Tq1nb",,"error":null,"portNumber":61449}'
2017-07-24 11:05:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'FMO250qlS2FtJV2OS6IghC5DmX1Tq1nb', error: 'null', listeningPort: '61449''
,2017-07-24 11:05:50 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [8, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:05:50 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:05:50 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A24BFF38-9898-41C6-87EB-9ADA562612FE
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:05:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 11:05:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:687F0B91-75C2-4D17-A950-AE8032F5F447
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61449
[ThaliCore] VirtualSocket.closeStr,eams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] Session.disconnect() peer:687F0B91-75C2-4D17-,A950-AE8032F5F447:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [8]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.dein,i,t peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'listening 61451'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1A72C93-840E-4716-A305-79B57337FFD2
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:076336D2-906B-45A8-9499-6D7BDC53DCA7
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
2017-07-24 11:05:57 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
2017-07-24 11:05:57 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 687F0B91-75C2-4D17-A950-AE8032F5F447 (syncValue: DSD2aOpQxoQBwNoTXbJyRfEnHepilY0w)'
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "68,7F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
2017-07-24 11:05:57 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":false,"generation":n,u,ll,"portNumber":null}'
2017-07-24 11:05:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":nul,l}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] Browser.brow,ser(_:foundPeer:withDiscoveryInfo:) found peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4C,A1-8FCD-469184F8E157","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event wit,h {"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}]'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","generation":0}'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:59 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,87F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,87F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,87F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:68,7F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:687F0B91,-75C2-4D17-A950-AE8032F5F447 error: max retries exceeded
2017-07-24 11:06:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DSD2aOpQxoQBwNoTXbJyRfEnHepilY0w","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:06:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'DSD2aOpQxoQBwNoTXbJyRfEnHepilY0w', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:06:08 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:08 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:08 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:06:08 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 11:06:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:06:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 11:06:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BC19DA9F-A334-4CA1-8FCD-469184F8E157 (syncValue: IypBLYvuI9PP6uM8myMyFZfTFDgmlwHK)'
,2017-07-24 11:06:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D49DF1D2-7638-45E5-924E-9788D599707C
[ThaliCore] Advertiser: session connected Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D49DF1D2-7638-45E5-924E-9788D599707C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61465
,2017-07-24 11:06:12 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IypBLYvuI9PP6uM8myMyFZfTFDgmlwHK","error":null,"portNumber":61465}'
,2017-07-24 11:06:12 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IypBLYvuI9PP6uM8myMyFZfTFDgmlwHK', error: 'null', listeningPort: '61465''
,2017-07-24 11:06:12 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [8, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:12 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:06:12 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:687F0B91-75C2-4D17-A950-AE8032F5F447:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
2017-07-24 11:06:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}]'
2017-07-24 11:06:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","generation":0}'
,2017-07-24 11:06:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:13 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"687F0B91-75C2-4D17-A950-AE8032F5F447","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D49DF1D2-7638-45E5-924E-9788D599707C
,[ThaliCore] Session.session(_:peer:didChange:) peer:D49DF1D2-7638-45E5-924E-9788D599707C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D49DF1D2-7638-45E5-924E-9788D599707C
,[ThaliCore] Session.startOutputStream(with:) peer:D49DF1D2-7638-45E5-924E-9788D599707C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [8, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:076336D2-906B-45A8-9499-6D7BDC53DCA7
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-24 11:06:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
,[ThaliCore] BrowserManager.disconnect peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61465
[ThaliCore] VirtualSocket.closeStr,eams() vsID:13
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [8, 13]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] Session.disconnect() peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:13 [8]
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D49DF1D2-7638-45E5-924E-9788D599707C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D49DF1D2-7638-45E5-924E-9788D599707C
[ThaliCore] Advert,iserRelay.deinit
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:D49DF1D2-7638-45E5-924E-9788D599707C
,# calls correct starts when network changes
,2017-07-24 11:06:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 61468'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE5E1924-9B07-4D31-896D-0D8D34B5D9C9
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2E623E57-D644-437A-B062-C493DD079F60
2017-07-24 1,1:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}]'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BC19DA9F-A334-4CA1-8FCD-469184F8E157 (syncValue: 3BRhligiDE0m5g9vt0A5fDuz6pwydKny)'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D2D069F-2F60-447B-B8BA-60B087ACB18C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D2D069F-2F60-447B-B8BA-60B087ACB18C", generation: 0)
,2017-07-24 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}]'
,2017-07-24 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}'
,2017-07-24 11:06:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BC,19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,C19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BC,19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,C19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42530266-613F-421D-BBC9-A49C425FB20F
[ThaliCore] Advertiser: session connected Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42530266-613F-421D-BBC9-A49C425FB20F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BC,19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,C19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}]'
2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:06:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:28 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42530266-613F-421D-BBC9-A49C425FB20F
,[ThaliCore] Session.session(_:peer:didChange:) peer:42530266-613F-421D-BBC9-A49C425FB20F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:42530266-613F-421D-BBC9-A49C425FB20F
[ThaliCore] Session.startOutputStream(with:) peer:42530266-613F-421D-BBC9-A49C425FB20F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,5 [8, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BC,19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:BC19DA9F,-A334-4CA1-8FCD-469184F8E157 error: max retries exceeded
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3BRhligiDE0m5g9vt0A5fDuz6pwydKny","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3BRhligiDE0m5g9vt0A5fDuz6pwydKny', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E1,57","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,,"portNumber":null,"recreated":true}'
2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.dis,connect peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157
2017-07-24 11:06:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 10087,D13-05EC-4EC5-A858-75B42091AB0B (syncValue: WdnmVOdCG52EaC2hunZXdPb8vqPUywNz)'
,2017-07-24 11:06:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61483
,2017-07-24 11:06:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WdnmVOdCG52EaC2hunZXdPb8vqPUywNz","error":null,"portNumber":61483}'
,2017-07-24 11:06:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WdnmVOdCG52EaC2hunZXdPb8vqPUywNz', error: 'null', listeningPort: '61483''
,2017-07-24 11:06:33 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [8, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:33 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:06:33 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
[ThaliCore] Advertiser: session connected Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
,[ThaliCore] Session.session(_:peer:didChange:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
,[ThaliCore] Session.startOutputStream(with:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [8, 15, 16, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2E623E57-D644-437A-B062-C493DD079F60
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Session.session(_:peer:didChange:) peer:F7A2A256-543A-410A-961E-7BCC035FB0C7 state: connected -> notConnected
[ThaliCore] Advertise,r: session notConnected Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered v,sID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserManager.disconnect peer:10087D13-05EC-4EC5-A858-75B42091AB0B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61483
,[ThaliCore] Session.disconnect() peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42530266-613F-421D-BBC9-A49C425FB20F state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) s,ocket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtual,SocketStreamsHandler disconnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remo,te peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.deinit
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [8, 15, 16]
[ThaliCore] AdvertiserRelay.disconnectNonTCPSess,ion()
[ThaliCore] Session.disconnect() peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[T,haliCore] VirtualSocket.deinit vsID:15 [8, 16]
,[ThaliCore] Session.deinit peer:F7A2A256-543A-410A-961E-7BCC035FB0C7
,[ThaliCore] Session.deinit peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 290 FIX ME, PLEASE!!!
,# teardown
,ok 291 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:06:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 11:06:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 292 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-24 11:06:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 293 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 294 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 295 specific error should be returned
,# teardown
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"951E5565-7CD1-4438-B15D-EB97D09CF081","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 296 error should be null
,ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 299 specific error should be returned
,# teardown
,ok 300 error should be null
,ok 301 error should be null
,# setup
,ok 302 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 61486'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 305 error should be null
,ok 306 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 307 error should be null
ok 308 error should be null
,# setup
,ok 309 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 61487'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:029A2102-ACCC-47D8-87CB-3466B7C6D004
[ThaliCore] Browser.st,artListening
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
,ok 311 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
ok 313 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:9D2D069F-2F60-447B-B8BA-60B087ACB18C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D2D069F-2F60-447B-B8BA-60B087ACB18C", generation: 0)
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}]'
2017-07-24 11:06:42 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","generation":0}'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9D2D069F-2F60-447B-B8BA-60B087ACB18C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 61488'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A325438-8298-47CF-86CA-510B1CB88DD8", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:9A325438-8298-47CF-86CA-510B1CB88DD8
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A325438-8298-47CF-86CA-510B1CB88DD8", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:9A325438-8298-47CF-86CA-510B1CB88DD8
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9A325438-8298-47CF-86CA-510B1CB88DD8
,[ThaliCore] Advertiser.stopAdvertising() peerID:9A325438-8298-47CF-86CA-510B1CB88DD8
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
,ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 61491'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 324 error should be null
,ok 325 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 326 error should be null
,ok 327 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 328 error should be null
,ok 329 error should be null
,# setup
,ok 330 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-24 11:06:43 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 331 This should not cause wifi to fail
,ok 332 native router should be bad
,# teardown
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'listening 61492'
,ok 336 first call should succeed
,ok 337 first call should succeed
,ok 338 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 339 error should be null
,ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-24 11:06:44 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 342 error should be null
ok 343 error should be null
,# setup
,ok 344 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 11:06:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 345 error should be null
ok 346 error should be null
,# setup
,ok 347 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"38d8babd-050d-4109-981d-df77ba1d3f29","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 348 should be called once
,ok 349 should not have been called more than once
,# teardown
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"38d8babd-050d-4109-981d-df77ba1d3f29","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 350 error should be null
,ok 351 error should be null
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
,ok 357 we have not added peer to the cache yet
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b952eb1-0c1d-4774-b5ab-aca3a1d6ebad","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 358 peer should be available
,ok 359 cache contains native peer
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b952eb1-0c1d-4774-b5ab-aca3a1d6ebad","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 360 peer should be unavailable
,ok 361 peer has been removed from cache
,# teardown
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 365 we have not added peer to the cache yet
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8d013a22-39f1-4497-9eb5-cfa35bf88de7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 366 peer should be available
,ok 367 cache contains wifi peer
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8d013a22-39f1-4497-9eb5-cfa35bf88de7","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 368 peer should be unavailable
,ok 369 peer has been removed from cache
,# teardown
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5fbdabec-4317-422b-bcfc-def92a35c589","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 373 first peer is available
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6d498849-c89b-414b-a5fd-58ca9c9d1898","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 second peer is available
,ok 375 first and second peers are different
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"5fbdabec-4317-422b-bcfc-def92a35c589","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6d498849-c89b-414b-a5fd-58ca9c9d1898","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 376 error should be null
,ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 379 should not be in cache at start
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d92a4896-7749-4af5-9dc3-3b5aac2c0c93","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 380 peer is available
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d92a4896-7749-4af5-9dc3-3b5aac2c0c93","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 11:06:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 384 error should be null
,ok 385 error should be null
,# setup
,ok 386 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-24 11:06:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e66f49c5-534c-486a-aa64-4b67721c567a","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 peer should be available
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e66f49c5-534c-486a-aa64-4b67721c567a","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 391 peer should be available
,ok 392 should store correct generation
,# teardown
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e66f49c5-534c-486a-aa64-4b67721c567a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 393 error should be null
,ok 394 error should be null
,# setup
,ok 395 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 11:06:47 - DEBUG thaliMobileNativeWrapper: 'listening 61493'
2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"37d48b31-dd2c-4e7a-9976-abc821b68148","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
,ok 396 discovered correct peer
ok 397 got correct generation
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"37d48b31-dd2c-4e7a-9976-abc821b68148","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 398 discovered correct peer
ok 399 got correct generation
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"37d48b31-dd2c-4e7a-9976-abc821b68148","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 400 error should be null
,ok 401 error should be null
,# setup
,ok 402 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'listening 61494'
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39316a28-d10b-4a40-9f93-25724ceb4dbc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 403 discovered available peer
,ok 404 peer is available
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39316a28-d10b-4a40-9f93-25724ceb4dbc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 405 error should be null
,ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fca1dd57-d963-42ea-8b20-72c584333309","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 peer should be available
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"fca1dd57-d963-42ea-8b20-72c584333309","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 409 peer should be unavailable
,ok 410 should be removed from cache
,# teardown
,ok 411 error should be null
,ok 412 error should be null
,# setup
,ok 413 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 61495'
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"80fcec5a-fa93-4b33-a87b-90872f77a0a7","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 414 first peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44ac8607-4cbf-4883-adac-d034f03d2974","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 415 second peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44ac8607-4cbf-,4883-adac-d034f03d2974","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 416 peer became unavailable
ok 417 it was wifi peer
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"44ac8607-4cbf-4883-adac-d034f03d2974","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 we found peer again
,ok 419 it was wifi peer
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"44ac8607-4cbf-4883-adac-d034f03d2974","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 peer became unavailable
,ok 421 it was wifi peer
,# teardown
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"80fcec5a-fa93-4b33-a87b-90872f77a0a7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 422 error should be null
,ok 423 error should be null
,# setup
,ok 424 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 425 error should be null
ok 426 error should be null
,# setup
,ok 427 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 61496'
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2b5de78a-554d-4b08-8eaf-34b5bce18a8d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 428 first peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2fc15fef-6da2-4727-ae97-5e84e16a5e49","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 429 second peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2b5de78a-554d-4b08-8eaf-34b5bce18a8d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 430 peer became unavailable
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2fc15fef-6da2-4727-ae97-5e84e16a5e49","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 431 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 432 error should be null
,ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 435 error should be null
,ok 436 error should be null
,# setup
,ok 437 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-24 11:06:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 438 error should be null
,ok 439 error should be null
,# setup
,ok 440 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b81f3bf-1240-4c26-aa27-7471588a29f3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 441 peer discovered first time does not have new address
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b81f3bf-1240-4c26-aa27-7471588a29f3","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 442 address has not been changed
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b81f3bf-1240-4c26-aa27-7471588a29f3","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 443 new port handled correctly
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b81f3bf-1240-4c26-aa27-7471588a29f3","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 444 new host handled correctly
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7b81f3bf-1240-4c26-aa27-7471588a29f3","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
,ok 445 newAddressPort is null for unavailable peers
,# teardown
,ok 446 error should be null
,ok 447 error should be null
,# setup
,ok 448 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-24 11:06:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 452 NOT IMPLEMENTED # SKIP
,# teardown
,ok 453 error should be null
ok 454 error should be null
,# setup
,ok 455 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-24 11:06:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
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
,2017-07-24 11:06:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 463 error should be null
,ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-24 11:06:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
,ok 467 the same hostAddress
,ok 468 the same portNumber
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 472 contains expected properties
,ok 473 the same hostAddress
,ok 474 the same portNumber
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 61497'
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8fd68670-65a4-4cb5-b13e-b6ab70212f3a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 478 Got specific error message
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8fd68670-65a4-4cb5-b13e-b6ab70212f3a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 479 error should be null
,ok 480 error should be null
,# setup
,ok 481 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 61498'
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e3d1ec0b-b704-42b5-a5dd-416f96d1539f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:e3d1ec0b-b704-42b5-a5dd-416f96d1539f
,ok 482 native wrapper `disconnect` called once
,ok 483 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e3d1ec0b-b704-42b5-a5dd-416f96d1539f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 484 error should be null
,ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-24 11:06:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 11:06:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 502 error should be null
ok 503 error should be null
,# setup
,ok 504 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-24 11:06:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 505 error should be null
ok 506 error should be null
,# setup
,ok 507 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'listening 61499'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9374184-A87F-49DD-9D84-CFAA23D200DB
[ThaliCore] Browser.startListening
2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4d9e79eb-285a-4cbf-b80f-f30abc0dab10","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 508 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"36286a66-0e12-4303-ac37-8f9eef57cb2d","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 509 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4d9e79eb-285a-4cbf-b80f-f30abc0dab10","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"36286a66-0e12-4303-ac37-8f9eef57cb2d","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:06:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 510 No peers
,ok 511 No peers
,ok 512 No peers
,# teardown
,ok 513 error should be null
,ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'listening 61500'
2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c7946d3b-07bc-4f39-b604-61f006314e6e","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 516 1
ok 517 2
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"59fbd8dc-50f6-4079-8557-b82cf46ab152","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c7946d3b-07bc-4f39-b604-61f006314e6e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"59fbd8dc-50f6-4079-8557-b82cf46ab152","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 518 error should be null
,ok 519 error should be null
,# setup
,ok 520 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-24 11:06:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 521 error should be null
,ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'listening 61501'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CAD31C85-20E6-4BD1-A48E-7A308E222915
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 526 error should be null
ok 527 error should be null
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Browser.startListening
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 528 error should be null
,ok 529 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
2017-07-24 11:06:56 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 10087D13-05EC-4EC5-A858-75B42091AB0B (syncValue: 0)'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}]'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:10,087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,0087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] Advertiser: session connected Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
2017-07-24 11:07:00 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
2017-07-24 11:07:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:07:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:07:00 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
,[ThaliCore] Session.session(_:peer:didChange:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] Session.startOutputStream(with:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [8, 16, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:10,087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,0087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF2,86-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 1)'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB,8,", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:07:02 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] Advertiser: session connected Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61510
,2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":61510}'
,2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 2)'
,2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [8, 16, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:05 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:05 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] Session.startOutputStream(with:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [8, 16, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:peer:didChange:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61516
,2017-07-24 11:07:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":61516}'
,[ThaliCore] BrowserManager.disconnect peer:10087D13-05EC-4EC5-A858-75B42091AB0B
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [8, 16, 18, 19, 20, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:08 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:08 - DEBUG testUtils: 'Got end'
,ok 530 received all uuids
,# teardown
,2017-07-24 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CAD31C85-20E6-4BD1-A48E-7A308E222915
2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":fal,se}'
2017-07-24 11:07:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 11:,07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:07:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 531 error should be null
,ok 532 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] AdvertiserRelay.didSocketDisc,onnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [8, 16, 18, 19, 20]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 [8, 16, 19, 20]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:20 [8, 16, 19]
,[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [8, 16]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
,# setup
,ok 533 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 11:07:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 534 error should be null
ok 535 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 536 getPeerIdentifier
,ok 537 getConnectionType
,ok 538 getActionType
,ok 539 getActionState
ok 540 getPskIdentity
,ok 541 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 542 initial state
ok 543 after start
2017-07-24 11:07:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 544 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 545 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-24 11:07:11 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
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
ok 590 enqueue is fine
ok 591 Everything should be off the queue
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
,2017-07-24 11:07:16 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:16 - DEBUG testUtils: 'Got end'
,ok 601 Got expected response
,ok 602 Got psk call back
,# teardown
,2017-07-24 11:07:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 613 good enqueue
ok 614 queue is not empty
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
ok 619 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 620 good enqueue
,ok 621 2nd good enqueue
,ok 622 we are in the pool
,ok 623 We are out of the pool
,ok 624 Action was killed
,ok 625 The original kill was called too
,ok 626 second item is still in queue
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
,ok 633 2nd action is in the pool
,ok 634 1st action is out of the pool
,ok 635 2st action is out of the pool
,ok 636 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 637 Got right error
,ok 638 Start should not be called
,ok 639 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 11:07:19 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 640 Got right error
,ok 641 Start should not be called
,ok 642 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 643 Got null
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 644 is an agent
,2017-07-24 11:07:19 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 645 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 646 Got Null
,ok 647 Got another null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 648 is an agent
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 649 is an agent
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 650 Action 1 killed at least once
,ok 651 Action 1 went first
,ok 652 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 653 should have gotten null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 654 Should have stopped nicely
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 655 Still looking for null
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-24 11:07:20 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 656 Yup, another null
,ok 657 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 658 Null 1
,ok 659 (unnamed assert)
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 660 is an agent
,ok 661 Null 3
,ok 662 Replication not yet called
,ok 663 Notification 2 not yet called
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 664 is an agent
,ok 665 Notification went first
,ok 666 Notification 2 not called yet
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 667 is an agent
,ok 668 Notification finished
,ok 669 Replication finished
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 First does not throw
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 672 is an agent
,ok 673 Second does not throw
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 674 is an agent
,ok 675 first ok
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 676 is an agent
,ok 677 second ok
,ok 678 third ok
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'listening 61520'
,ok 679 error should be null
,ok 680 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4F51A3C8-A689-4B82-BAD8-DD34390017FE
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] Browser.startListening
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:07:22 - INFO testThaliNotification: 'startListeningForAdvertisements'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}]'
2017-07-24 11:07:22 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 3)'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) found active relay
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":61510}'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 4)'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) found active relay
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":61516}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [8, 16, 22]
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [8, 16, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [8, 16, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 5)'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) found active relay
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":61516}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [8, 16, 23, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
,[ThaliCore] VirtualSocket.deinit vsID:24 [8, 16, 23]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 6)'
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) found active relay
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":61510}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [8, 16, 23, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [8, 16, 23]
,2017-07-24 11:07:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 7)'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) found active relay
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":61516}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [8, 16, 23, 26]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 8)'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) found active relay
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":61510}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
,[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [8, 16, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [8, 16, 23, 27]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [8, 16, 23]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:23 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","generation":0}]'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","generation":0}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 12B63DC0-3AAD-4086-9C02-4C78DF1E4303 (syncValue: 9)'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] Advertiser: session connected Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","generation":0}]'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","generation":0}'
,2017-07-24 11:07:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61516
[ThaliCore] Session.disconnect() peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) relay removed
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}]'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:07:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:07:26 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] Session.session(_:peer:didChange:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61529
[ThaliCore] Session.session(_:peer:didChange:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92 state: connecting -> connected
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":61529}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for EC9AF43F-E75B-4A72-9E65-674DD3ABC08B (syncValue: 10)'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] Session.startOutputStream(with:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,8 [8, 16, 23, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [8, 16, 23, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:26 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 61529,12B63DC0-3AAD-4086-9C02-4C78DF1E4303'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [8, 16, 23, 28]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] Session.startOutputStream(with:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [8, 16, 23, 28, 30]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [8, 16, 23, 28, 30, 31]
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
,[ThaliCore] VirtualSocket.deinit vsID:28 [8, 16, 23, 30, 31]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Advertiser: session connected Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] Session.startOutputStream(with:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [8, 16, 23, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [8, 16, 23, 30, 31]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [8, 16, 23, 30]
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61510
[ThaliCore] Session.disconnect() peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) relay removed
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}]'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","generation":0}'
,2017-07-24 11:07:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:07:27 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:07:27 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61537
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":61537}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 11)'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
,[ThaliCore] Session.session(_:peer:didChange:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E state: connecting -> connected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":"Peer is unavailable","portNumber":null}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Session.startOutputStream(with:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [8, 16, 23, 30, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8 (syncValue: 12)'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-24 11:07:29 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'han,dlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:9EED0799-F500-45EE-9882-03BB7687C630
,[ThaliCore] BrowserManager.disconnect peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [8, 16, 23, 30, 33, 34]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Session.startOutputStream(with:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [8, 16, 23, 30, 33, 34, 35]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [8, 16, 23, 30, 34, 35]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:07:30 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 61537,EC9AF43F-E75B-4A72-9E65-674DD3ABC08B'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [8, 16, 23, 30, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:34
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:34 [8, 16, 23, 30, 35, 36]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsI,D:36
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remove,d, count:0
,[ThaliCore] VirtualSocket.deinit vsID:36 [8, 16, 23, 30, 35]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:35 [8, 16, 23, 30]
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,ok 681 Peer made successful https requests to all peers
,ok 682 Peer received right amount of https requests
,ok 683 HTTPS server received zero PSK Identities. Count:0
,# teardown
,2017-07-24 11:07:37 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
,2017-07-24 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24, 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"EC9AF43F-E75B-4A72-9E65-674DD3ABC08B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4F51A3C8-A689-4B82-BAD8-DD34390017FE
,2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:07:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Brows,erManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:07:37 - INFO ,thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:07:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 11:07:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,ok 692 Response should be HTTP_BAD_RESPONSE
,ok 693 must return null after successful call
,# teardown
,2017-07-24 11:07:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 694 Response should be NETWORK_PROBLEM
ok 695 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-24 11:07:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 696 Resolution should be BAD_PEER
,ok 697 correct error message
,# teardown
,2017-07-24 11:07:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 698 Call start once
,ok 699 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 700 must return null after successful call.
,# teardown
,2017-07-24 11:07:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 701 Should be Killed
,ok 702 Start after killed
,# teardown
,2017-07-24 11:07:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 703 Should be KILLED
,ok 704 must return null after successful kill
,# teardown
,2017-07-24 11:07:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 705 Should be KILLED
ok 706 must return null after successful kill
,# teardown
,2017-07-24 11:07:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 707 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 708 must return null after successful call
,# teardown
,2017-07-24 11:07:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-24 11:07:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 709 Should be NETWORK_PROBLEM caused closing server socket
,ok 710 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 711 Should be NETWORK_PROBLEM caused closing client socket
ok 712 Should be Could not establish TCP connection
,# teardown
,2017-07-24 11:07:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 713 publicKeysToNotify cannot be null
,ok 714 ecdh for local device cannot be null
ok 715 milliseconds cannot be less than 0
ok 716 milliseconds cannot be 0
ok 717 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 718 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 719 should be equal
,ok 720 should be equal
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
ok 735 good preAmble
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
,2017-07-24 11:07:57 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-24 11:07:57 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 11:07:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 758 notification peer dictionary contains exactly 1 peer
,2017-07-24 11:07:58 - WARN thaliNotificationClient: 'peer is not available'
,ok 759 notification peer dictionary does not contain any peers
,2017-07-24 11:07:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-24 11:07:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 760 entry exists
,ok 761 entry is resolved
,# teardown
,2017-07-24 11:07:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 762 Action should be KILLED
ok 763 Peer state should be RESOLVED
,# teardown
,2017-07-24 11:07:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 764 hostAddress must match
,ok 765 portNumber must match
,ok 766 suggestedTCPTimeout must match
,ok 767 connectionType must match
,ok 768 peerIDs must match
,# teardown
,2017-07-24 11:08:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 769 Correct error
,# teardown
,2017-07-24 11:08:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 770 hostAddress must match
,ok 771 portNumber must match
,ok 772 suggestedTCPTimeout must match
,ok 773 connectionType must match
,ok 774 peerIds must match
,# teardown
,2017-07-24 11:08:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 775 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 776 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:02 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 777 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 778 action should be resolved with NETWORK_PROBLEM error
ok 779 correct number of requests
ok 780 correct number of failures
ok 781 correct final peer state
,# teardown
,2017-07-24 11:08:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-24 11:08:06 - WARN thaliNotificationClient: 'peer is not available'
2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 782 peerDictionary should become empty
,# teardown
,2017-07-24 11:08:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 783 failed with expected error
ok 784 peer state should be RESOLVED
,# teardown
,2017-07-24 11:08:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-24 11:08:07 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 785 First action failed
,ok 786 second action killed
# teardown
,2017-07-24 11:08:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 787 secrets are equal
ok 788 Public key matches with the server key
,ok 789 hostAddress must match
,ok 790 portNumber must match
,ok 791 suggestedTCPTimeout must match
,ok 792 connectionType must match
,# teardown
,2017-07-24 11:08:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 793 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 794 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 795 All entries should be expired after 1 second
# teardown
,2017-07-24 11:08:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 796 All keys need to be available in the cache
,ok 797 All entries should be expired after 1 second
# teardown
,2017-07-24 11:08:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 798 Size of the cache should be 2
ok 799 Cache doesn't contain dictionary1
,ok 800 Size of the cache should be 1
ok 801 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 11:08:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 802 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 803 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-24 11:08:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 804 StartUpdateAdvertisingAndListening should not be called
,ok 805 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 806 no error
,ok 807 should be 204
,# teardown
,2017-07-24 11:08:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 808 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 11:08:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 809 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-24 11:08:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 810 no error
,ok 811 should be 200
,ok 812 should be equal
,ok 813 should be equal
,ok 814 (unnamed assert)
,ok 815 no error
ok 816 should be 204
,# teardown
,2017-07-24 11:08:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 817 error should be null
ok 818 should be 204
,# teardown
,2017-07-24 11:08:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 819 should be 404
,# teardown
,2017-07-24 11:08:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 820 equal keys
ok 821 not equal connection type
ok 822 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-24 11:08:19 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 823 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 824 second cleared dictionary
,2017-07-24 11:08:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 825 First start and on called correctly
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
,2017-07-24 11:08:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-24 11:08:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-24 11:08:22 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'listening 61592'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Browser.startListening
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2D8CC952-620F-4C53-BCCF-6430782E2A13
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","generation":0}]'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","generation":0}'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:08:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67B1214E-E287-45D1-8BEF-EBBC94C6CCB3 (syncValue: 13)'
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Advertiser: session connected Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","generation":0}]'
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","generation":0}'
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:08:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63570569-B1AE-4581-979F-3BFBFB102A51","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61597
,2017-07-24 11:08:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"13","error":null,"portNumber":61597}'
,2017-07-24 11:08:25 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 63570569-B1AE-4581-979F-3BFBFB102A51 (syncValue: 14)'
,2017-07-24 11:08:25 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [8, 16, 23, 30, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [8, 16, 23, 30]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [8, 16, 23, 30, 38]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0 state: notConnected -> connecting
,2017-07-24 11:08:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [8, 16, 23, 30, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] Session.session(_:peer:didChange:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [8, 16, 23, 30, 38, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [8, 16, 23, 30, 38, 39, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [8, 16, 23, 30, 38, 39, 40, 41, 42]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] VirtualSocket.deinit vsID:40 [8, 16, 23, 30, 38, 39, 41, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [8, 16, 23, 30, 38, 39, 41, 42, 43]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.session(_:peer:didChange:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [8, 16, 23, 30, 38, 39, 41, 42, 43, 44]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [8, 16, 23, 30, 38, 39, 41, 43, 44]
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,6 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
,[ThaliCore] VirtualSocket.deinit vsID:49 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61613
,2017-07-24 11:08:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"14","error":null,"portNumber":61613}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48, 51]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:29 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [8, 16, 23, 30, 38, 39, 41, 43, 44, 45, 46, 48, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 11:08:29 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
2017-07-24 11:08:29 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by r,emote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnec,tHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [8, 16, 23, 30, 39, 41, 43, 44, 45, 46, 48, 51, 52]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [8, 16, 23, 30, 41, 43, 44, 45, 46, 48, 51, 52]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] VirtualSocket.deinit vsID:41 [8, 16, 23, 30, 43, 44, 45, 46, 48, 51, 52]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] Session.session(_:peer:didChange:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453 state: connecting -> connected
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 53, 54]
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 53, 54, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 53, 54, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 55, 56]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
,[ThaliCore] VirtualSocket.deinit vsID:55 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 56]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 56, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 56, 57, 58, 59]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] VirtualSocket.deinit vsID:56 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 57, 58, 59]
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountere,d vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [8, 16, 23, 30, 43, 45, 46, 48, 51, 52, 54, 57, 58, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Virtu,alSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [8, 16, 23, 30, 43, 45, 46, 51, 52, 54, 57, 58, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TC,PClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [8, 16, 23, 30, 43, 45, 46, 51, 52, 54, 58, 59, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [8, 16, 23, 30, 43, 45, 46, 51, 52, 54, 58, 59, 60, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] Session.startOutputStream(with:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [8, 16, 23, 30, 43, 45, 46, 51, 52, 54, 58, 59, 60, 61, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:08:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-24 11:08:32 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
2017-07-24 11:08:32 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [8, 16, 23, 30, 43, 45, 46, 51, 54, 58, 59, 60, 61, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:54 [8, 16, 23, 30, 43, 45, 46, 51, 58, 59, 60, 61, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:59
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:59 [8, 16, 23, 30, 43, 45, 46, 51, 58, 60, 61, 62]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
,[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:58 [8, 16, 23, 30, 43, 45, 46, 51, 60, 61, 62]
,[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [8, 16, 23, 30, 43, 45, 46, 51, 60, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Th,aliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [8, 16, 23, 30, 43, 45, 46, 51, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_,:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [8, 16, 23, 30, 43, 46, 51, 60]
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [8, 16, 23, 30, 46, 51, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(,_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:46 [8, 16, 23, 30, 51, 60]
[ThaliCore] TCPClient.socketDidDisconnect(_:wi,thError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [8, 16, 23, 30, 51]
[ThaliCore] TCPClient.socketDidDiscon,nect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:11:21 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 11:11:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 11:18:21 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 11:18:21 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-24 11:,18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-24 11:18:21 - INF,O CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can still do HTTP requests between peers with coordinator'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request coordinated'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test HTTP_BAD_RESPONSE locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns no matches'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated pull replication from notification test, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525,-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-24 11:18:21 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 11:18:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 860 failed with TimeoutError
  ---
,    operator: fail
  ...
,# teardown
,2017-07-24 11:18:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4,525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-452,5-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D2C70861-30E0-4525-B062-849B3DC3F65A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
